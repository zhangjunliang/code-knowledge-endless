## docker 安装及命令
- 一、
  - 1.1
  > docker linux中如何安装
    ```
     安装Docker-CE
        yum install -y yum-utils device-mapper-persistent-data lvm2

     增加最新版本的Docker安装仓库
        yum-config-manager --add-repo \
            https://download.docker.com/linux/centos/docker-ce.repo
        
     安装Docker-CE版本
        yum install -y docker-ce docker-ce-cli containerd.io

     启动docker
        systemctl enable docker

     允许开机启动
        systemctl start docker  
  ```
- 二、
    - 2.1
  > docker 如何从docker容器中，将现有的docker容器镜像提交到 docker images:
     ```
        docker commit 容器id 版本号:镜像名
     ```
  > docker 如何从镜像中将现有commit的镜像从 docker images拉取:
     ```
        docker save -o  镜像名  镜像id
     ```
  > docker 将镜像加载到 docker images中:
     ```
        docker load -i  镜像名  版本号:镜像名
     ``` 
  > docker更改镜像名称:
     ```
        docker tag 镜像id 镜像名称:版本号
     ```                                                                                                    
    - 2.2
   > 停止启动的docker容器
     ```
        docker stop 容器id
     ```                          
   > 启动之前现有的docker容器
     ```
        docker stop 容器id
     ```
   > 启动docker image中的镜像                                                                                                      
    ```
        docker run -d  -p 宿主机端口映射:docker容器端口  -v /etc/localtime:/etc/localtime --name 现有镜像名称 镜像名称（自己设定）:版本号  /usr/sbin/sshd -D 
     ```
   > 查看启动的docker容器
     ```
        docker ps / docker ps -a  docker容器
     ```
   > 进入docker容器内编辑:
     ```
        docker exec -it 容器id bash
     ```
   > docker容器拷贝:
     ```
        1、宿主拷贝到docker中： docker cp 宿主文件名 容器id:docker容器路径
        2、docker容器拷贝到宿主 : docker cp 容器id:docker容器路径   宿主路径
     ```
