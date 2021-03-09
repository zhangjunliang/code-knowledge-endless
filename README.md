# code-knowledge-endless

            ______________
            ___________(_)__  /
            ___  /____  /__  / 
            __  /____  / _  /  
            _____/__  /  /_/   
               /___/  2021 day day up
    
    编程相关的一些知识点说明，目的构建清晰知识体系，以及一些简单demo            

## [网络 + 协议](./network.md)

## [算法 + 数据结构](./algorithm.md)

## [linux](./linux.md)

- [read more](./linux.md)

- [docker](./docker.md)
    

## 语言

- [python](https://github.com/zhangjunliang/python-package)
    
    - [read more](https://github.com/zhangjunliang/python-package)
        
    > 请点击链接点击前往另一个项目查看
    
## 数据


- [mysql](./mysql.md) 
    
    - [read more](./mysql.md)

    > MySQL 是最流行的关系型数据库管理系统，在 WEB 应用方面 MySQL 是最好的
      RDBMS(Relational Database Management System：关系数据库管理系统)应用软件之一。

- [redis](./redis.md) 

    - [read more](./redis.md)

    > REmote DIctionary Server(Redis) 是一个由Salvatore Sanfilippo写的key-value存储系统。 
      Redis是一个开源的使ANSI C语言编写、遵守BSD协议、支持网络、可基于内存亦可持久化的日志型、Key-Value数据库，
      并提供多种语言的API。它通常被称为数据结构服务器，因为值（value）可以是 字符串(String), 哈希(Hash), 
      列表(list), 集合(sets) 和 有序集合(sorted sets)等类型。

## 其他

1. selenium 
    > selenium 是一个 web 的自动化测试工具，不少学习功能自动化的同学开始首选 selenium ，因为它相比 QTP 有诸多有点：
    免费，也不用再为破解 QTP 而大伤脑筋小巧，对于不同的语言它只是一个包而已，而 QTP 需要下载安装1个多 G 的程序。
    这也是最重要的一点，不管你以前更熟悉 C、 java、ruby、python、或都是 C# ，你都可以通过 selenium 完成自动化测试，
    而 QTP 只支持 VBS支持多平台：windows、linux、MAC ，支持多浏览器：ie、ff、safari、opera、chrome
    支持分布式测试用例的执行，可以把测试用例分布到不同的测试机器的执行，相当于分发机的功能
2. Appium 
    > Appium 是一个开源工具，用于自动化 iOS 手机、 Android 手机和 Windows 桌面平台上的原生、移动 Web 和混合应用。
    「原生应用」指那些用 iOS、 Android 或者 Windows SDKs 编写的应用。「移动 Web 应用」是用移动端浏览器访问的应用
    （ Appium 支持 iOS 上的 Safari 、Chrome 和 Android 上的内置浏览器）。「混合应用」带有一个「webview」
    的包装器——用来和 Web 内容交互的原生控件。类似于 Apache Cordova 或 Phonegap 项目，创建一个混合应用使得用 Web 
    技术开发然后打包进原生包装器创建一个混合应用变得容易了。重要的是，Appium 是跨平台的：它允许你用同样的 API 对多平台
    （iOS、Android、Windows）写测试。做到在 iOS、Android 和 Windows 测试套件之间复用代码。

3. [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/) 
    > DNSmasq是一个小巧且方便地用于配置DNS和DHCP的工具，适用于小型网络，它提供了DNS功能和可选择的DHCP功能。
    它服务那些只在本地适用的域名，这些域名是不会在全球的DNS服务器中出现的。
    yum install -y dnsmasq
    chkconfig dnsmasq on #开机自动启动
    /etc/init.d/dnsmasq restart #重启

4. 免费https证书
    - 阿里云[建议使用]
    - GetHTTPSforFree ->> https://gethttpsforfree.com/

5. 5W2H2R
    > 5W-> why, who, when, where, what: 为什么要做，希望谁，在什么时间，什么地方，完成什么事情
    > 2H-> how, how much: 希望怎么做，做到什么程度
    > 2R-> resource, result: 有什么资源支持，希望获得什么结果

6. 图床
    > 图床一般是指储存图片的服务器，有国内和国外之分。国外的图床由于有空间距离等因素决定访问速度很慢影响图片显示速度。
    国内也分为单线空间、多线空间和cdn加速三种。

7. [Source Code Pro 字体](https://github.com/adobe-fonts/source-code-pro)
    > 由Adobe开发，为程序代码设计，免费开源！ 等宽字体！
    - 行距和字距是目前编程字体中控制的最完美的，Monaco 的行距错乱严重，与 Sorce Code Pro 完全不能比。
    - 0和o、O辨别分明，Droid Sans Mono 与其质量相似，但是在这点上远远不及。与其类似的还有小写 l 和大写 I。
    - 字形非常优美，弧线内敛而且恰到好处。但是最常用的编程变量小写 i 和 j 又很有编程之风，这点我非常喜欢。
    - （仅限于 OS X 或者 Mactype 等反锯齿算法）各个字号都清爽漂亮，比起 Courier New 真是太漂亮了，无论是放大还是缩小都优美简洁。
    - 开源免费，比起盗版字体来说要心安不少。

8. scrum实施规定
    - scrum介绍
    > Scrum是一种迭代式增量软件开发过程，通常用于敏捷软件开发。
    - Scrum角色
    > 包括：产品经理（PO）、教练（SM）和团队（Team）。
    - Scrum流程包括
    > 包括：计划会议、晨会、demo演示和回顾会议。
    - 计划会议时间
    > 目前sprint周期为3天，每次计划会议时间为a(2小时),demo演示时间为b(1.5个小时)，人数为c(team成员数量)，每天每个成员工作时间为d(8小时)，每次sprint工时为q(包括开发和功能测试时间)，即工时
    q = (d * c * 3 – (a + b) * c) * 80%;
   
    > 例如：众测团队成员数为5人，工时为：q = (8 * 5 * 3 – (2 + 1.5) * 3) * 80%,约等于80个小时；
    计划会议时间定为每周周一和周四上午10点；

    - 计划会议内容                                                                                                                                                                                                                                                                                                                            
    > 产品经理提出本次sprint要完成的需求，并讲解需求细节，排出优先级;
    教练员或team负责人分解需求到多个子任务，要求每个成员都清楚每个子任务；
    Team全体成员根据卡罗牌出牌，直到team全体成员通过卡罗牌上面的时间；
    根据产品经理制定任务的优先级以及每个sprint工时来安排任务；
    Team负责人把每个任务的详情描述都录到redmine;
    - 晨会时间和内容
    > 晨会定在研发工位每天上午10点，有team成员主动组织，如果有计划会议，晨会就取消；
    - 晨会内容
    > 每个team成员回答3个问题：昨天完成什么工作、今天准备完成什么工作和遇到什么问题;
    晨会时间理论上最好不要超过15分钟；
    - demo演示时间
    > demo演示时间可以根据每个任务的紧急状态来定，一般在每周周三（上午11点）和周六（下午2点）。
    - 回顾会议
    > 回顾会议定在每个sprint计划会议开始之前，时间为每周周三（下午6点）和周六（下午5点）。
    每个人提出2-3个需要改进的问题；
