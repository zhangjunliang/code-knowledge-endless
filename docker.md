# Docker

## 安装

### linux安装

```
 安装Docker-CE
    yum install -y yum-utils device-mapper-persistent-data lvm2

 增加最新版本的Docker安装仓库
    yum-config-manager --add-repo \
        https://download.docker.com/linux/centos/docker-ce.repo
    
 安装Docker-CE版本
    yum install -y docker-ce docker-ce-cli containerd.io

 启动docker
    systemctl start docker 
    
 允许开机启动
    systemctl enable docker  
```

## 基础命令

- 拉取镜像
    ```
    docker pull  所需要的组件名:版本号
    ```
- 从容器创建一个新的镜像
    ```
    docker commit 容器id 版本号:镜像名
    ```
- 将指定镜像保存成 tar 归档文件 并直接压缩
    ```
    docker save redis:test |gzip > test.tar.gz
    ```
-  导入使用 docker load 命令导入镜像
    ```
    docker load < test.tar.gz
    ``` 
-  标记本地镜像，将其归入某一仓库。
    ```
    docker tag redis:test project/redis:v1
    ```  

- 停止
    ```
    docker stop 容器id

- 创建一个新的容器并运行一个命令                                                                                                 
    ```
        docker run -d  -p 宿主机端口映射:docker容器端口  -v /etc/localtime:/etc/localtime --name 现有镜像名称 镜像名称（自己设定）:版本号  /usr/sbin/sshd -D 
     ```
- 查看启动的docker容器
     ```
        docker ps / docker ps -a  docker容器
     ```
- 在运行的容器中执行命令
    ```
    # 进入交互模式的终端
    docker exec -it 容器id bash
    ```
- docker容器拷贝
    ```
    1、宿主拷贝到docker中： docker cp 宿主文件名 容器id:docker容器路径
    2、docker容器拷贝到宿主 : docker cp 容器id:docker容器路径   宿主路径
    ```
### 自动化部署
