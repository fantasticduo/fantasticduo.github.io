## Python SSL错误

### 1. pip 安装模块提示SSL错误

- 原因：电脑已经安装过Python3.6后又安装了Python3.7，此时电脑有两个Pyton版本，系统的openssl版本对于Python3.7过老，更新一下openssl即可

- [<<安装包网站>>](<https://slproweb.com/products/Win32OpenSSL.html>)

  ![001](.\001.png)

选择适合自己系统的版本即可，安装好后，cmd->import ssl 测试是否成功。