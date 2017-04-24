# WHAT
小米路由器 shadowsocks 插件
# USAGE
cd /tmp && rm -rf *.sh && curl -k -o miwifi.sh https://raw.githubusercontent.com/ericchenkai/miwifi-ss/master/miwifi.sh && chmod +x miwifi.sh && sh ./miwifi.sh && rm -rf *.sh
* 为curl增加了-k参数，避免SSL验证问题。相应的修改了下载链接。
