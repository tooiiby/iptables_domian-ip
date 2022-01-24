上游项目地址

https://github.com/arloor/iptablesUtils

修改内容

1、通过 ip.sb 获取公网IPV4地址，方便NAT GCE AWS 阿里云等内网ip机型获取公网IP

2、修改 dnat.sh 地址

用法

wget -N --no-check-certificate "https://raw.githubusercontent.com/tooiiby/iptables_domian-ip/main/iptables.sh" && chmod +x iptables.sh && ./iptables.sh
