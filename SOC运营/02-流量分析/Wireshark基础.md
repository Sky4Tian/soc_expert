## 显示过滤器速查表

**IP与端口过滤**
ip.addr == 192.168.1.1             # 显示所有源或目的是 1.1 的流量
ip.src == 192.168.1.1              # 仅显示源 IP
ip.dst == 10.10.10.10              # 仅显示目的 IP
tcp.port == 443                    # TCP 端口 443
udp.port == 53                     # UDP 端口 53 (DNS)
tcp.port == 443 || tcp.port == 80  # 逻辑或，显示 HTTP 或 HTTPS
!(ip.addr == 192.168.1.1)          # 排除某 IP（注意括号）


smtp.data.fragment                  # 显示所有传输邮件内容的包
