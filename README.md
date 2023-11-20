# HowToUseSSH
这个项目是教会小白用户如何使用SSH
# 如何使用ssh?

## Windows 10 | Windows 11 用户
> ssh 是windows10 和 windows 11 系统自带的命令。windows 7的老系统不带，但是你可以下载[Putty](https://www.putty.org/) 来替代。

> 使用方法：

## 1. 点击 开始, 输入cmd 找到命令行


<img src="https://github.com/wukongdaily/HowToUseSSH/assets/143675923/c3a0c2ab-2879-4f1d-aa4e-5eb5f6949ad1" width="592" height="492"/>

## 2. 在命令行中输入
<img src="https://github.com/wukongdaily/HowToUseSSH/assets/143675923/7cf70a2d-a1ac-4239-92d8-a7608651b751" width="50%"/>
<br>
ssh 用户名@服务器地址 

## 3. 输入密码
<img src="https://github.com/wukongdaily/HowToUseSSH/assets/143675923/0c63a1d8-da1b-49e0-9f1c-b433ebcd2ce8" width="50%"/>
<br>

## 4. 连接成功
<br>
<img src="https://github.com/wukongdaily/HowToUseSSH/assets/143675923/d613a1fc-cedf-4c12-8136-e395c95298fe" width="50%"/>

# 常见问题
### 提示主机密钥发生了变化
<img src="https://github.com/wukongdaily/HowToUseSSH/assets/143675923/bcb99038-e012-496b-8168-4d794eac5da0" width="50%"/>
<br>


### 解决办法

* 删除上次存储的ssh密钥即可。然后再重新连接ssh

<img src="https://github.com/wukongdaily/HowToUseSSH/assets/143675923/470ea6c4-98a4-42c5-9654-7277de97c860" width="80%"/>

# For windows 10/11 执行下列命令
```
del /q %userprofile%\.ssh\known_hosts

```
# For macOS 执行下列命令
```
rm -f "$HOME/.ssh/known_hosts"

```
<img src="https://github.com/wukongdaily/HowToUseSSH/assets/143675923/77ae42b8-c870-499a-9c18-9f5c146f01d3" width="50%">

# 如果你经常使用ssh 还是建议使用第三方ssh工具
## final shell
https://www.hostbuf.com/t/988.html



