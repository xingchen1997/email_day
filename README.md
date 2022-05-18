# email-day

## 说明

    使用 Node.js 生成 邮件模板，使用 GitHub Actions 实现自动发送。

## 结果展示


## 配置

### GitHub Secrets 设置

在 项目 `Settings` 下的 `Secrets` 中添加以下变量
+ `START_DAY` 纪念日开始时间 eg:2017/1/28
+ `MARRY_START_DAY` 结婚纪念日 eg:2017/1/28
+ `LOCAL` 所在地 eg:"beijing/changping-district"
+ `MAIL_SERVER_ADDRESS` 邮件服务器地址 eg: smtp.163.com
+ `MAIL_SERVER_PORT` 邮件服务端口 eg: 465
+ `MAIL_USERNAME` 邮件用户名 eg: XXX
+ `MAIL_PASSWORD` 邮件密码 eg: xxx
+ `MAIN_SEND_TO`  邮件接收者 eg: yoda@dagobah.com
+ `MAIL_SEND_FROM` 邮件发送者 eg: Luke Skywalker # <user@example.com> 



```
git init

git push origin master //（正常提交）
git push origin master -f //（强制提交）

git remote add origin git@github.com:xingchen1997/email_day.git

git add .              #将当前目录所有文件添加到git暂存区
git commit -m "my commit"            #提交并备注提交信息
git push                        #将本地提交推送到远程仓库
```
