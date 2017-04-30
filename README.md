# gv.sh
使用 chrome 浏览器，用 F12 打开检查工具，然后，选择一个号码，点提交，切换到 network 选项卡，会看到一个请求，右击选择 “Copy” > “Copy as cURL (bash)”

替换掉下面 result=$() 括号中的内容，并将 curl 改成 curl -s 。

nohup bash gv.sh &
