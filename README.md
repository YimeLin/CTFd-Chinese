# CTF在线平台

## 项目介绍

本项目在CTFd的基础上进行了部分修改

个人模式基本完成全部汉化

主题使用了Neon

采用Docker部署

软件源换成了国内源

基本上实现了CTFd平台的一键部署

------

## 平台截图

![QQ截图20221103203254](http://img.assets.cotar.cn/i/2022/11/07/6368ca0603364.jpg)

![QQ截图20221103203303](http://img.assets.cotar.cn/i/2022/11/07/6368ca0b22e7c.jpg)

![QQ截图20221103203311](http://img.assets.cotar.cn/i/2022/11/07/6368ca0f3482b.jpg)

## 部署教程

### 1.安装Docker

```
curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun 
```

### 2.安装docker-compose

```
curl -L https://get.daocloud.io/docker/compose/releases/download/v2.2.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```

### 3.克隆本项目

```
git clone https://github.com/WaYime/CTFd-Chinese.git
```

### 4.使用Docker构建

```
docker-compose up -d
```

### 5.安装完成后访问IP进行初始化

------

### 本项目在github众多优秀项目的基础上修改完成，十分感谢！

[CTFd/*CTFd*](https://github.com/CTFd/CTFd)

[Gu-f/*CTFd*_*chinese*_CN](https://github.com/Gu-f/CTFd_chinese_CN)

[chainflag/*ctfd*-neon-*theme*](https://github.com/chainflag/ctfd-neon-theme)



=======
# CTF在线平台

## 项目介绍

本项目在CTFd的基础上进行了部分修改

个人模式基本完成全部汉化

主题使用了Neon

采用Docker部署

软件源换成了国内源

基本上实现了CTFd平台的一键部署

------

## 平台截图

![Home](/img/Home.jpg)

![Challenges](/img/Challenges.jpg)

![Login](/img/Login.jpg)

------

## 部署教程

### 1.安装Docker

```
curl -fsSL https://get.docker.com | bash -s docker --mirror Aliyun 
```

### 2.安装docker-compose

```
curl -L https://get.daocloud.io/docker/compose/releases/download/v2.2.2/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```

### 3.克隆本项目

```
git clone https://github.com/YimeLin/CTFd-Chinese.git
```

### 4.使用Docker构建

```
docker-compose up -d
```

### 5.安装完成后访问IP进行初始化

------

### 本项目在github众多优秀项目的基础上修改完成，十分感谢！

[CTFd/*CTFd*](https://github.com/CTFd/CTFd)

[Gu-f/*CTFd*_*chinese*_CN](https://github.com/Gu-f/CTFd_chinese_CN)

[chainflag/*ctfd*-neon-*theme*](https://github.com/chainflag/ctfd-neon-theme)
