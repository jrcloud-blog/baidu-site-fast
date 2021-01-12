# 百度快速收录脚本
**此脚本用于让网站快速被百度收录(但不能保证100%成功)**
使用方法:  
进入百度资源平台'zn.baidu.com' 登陆并且添加站点  
然后选择'普通提交' 选择'curl提交'  
把那段'curl -H'开头的复制下来  
在Linux服务器上执行  
    git clone https://github.com/jrcloud-blog/baidu-site-fast.git
然后执行
    cd baidu-site-fast
    echo "你刚刚复制的内容" >> bash.sh
    echo "要提交的网址" >> urls.txt
    chmod +x bash.sh
最后执行
    ./uploads
开始提交  
原理:使用'API提交'方式提交3000次
