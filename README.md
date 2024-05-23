# nginx-conf-template

如何使用？

‘cd /etc/nginx/sites-available’ 
在当前目录下拉取对应的‘conf’模版，比如
‘wget https://raw.githubusercontent.com/xyychenchen/nginx-conf-template/main/linkstack.conf’
按照你的实际情况进行修改 

然后‘cd /etc/nginx/sites-enabled’
在当前目录运行‘sudo ln -s /etc/nginx/sites-available/linkstack.conf’ 
以上所有路径都必须根据自己实际情况进行修改

