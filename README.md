#一键脚本安装复制以下命令在VPS中执行，选择安装trojan，然后输入解析到VPS的域名并回车（不要带http：//，只输入域名，例如atrandys.com或xxx.atrandys。 com），开始安装，然后等待安装完成即可。

注意：如果提示SELinux状态问题，请按要求输入Y重启VPS，然后再执行本脚本，否则可能https证书申请出错

curl -O https://raw.githubusercontent.com/DuoBaoX/trojan/master/trojan_mult.sh && chmod + x trojan_mult.sh && ./trojan_mult.sh


安装BBR加速，指向下面命令

cd /usr/src && wget -N --no-check-certificate "https://raw.githubusercontent.com/DuoBaoX/Linux-NetSpeed/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh
