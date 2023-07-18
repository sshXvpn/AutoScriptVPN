
## AutoscriptVPN V23 Version 1.0 beta

<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/sshXvpn/AutoScriptVPN/main/V23/v1.3.2/install.sh && chmod +x install.sh && sed -i -e 's/\r$//' install.sh && screen -S install ./install.sh</code></pre>

## UPDATE
* Add auto delete expiry users every 00.00
* Add Auto reboot every 00.00
* Fix Instalation
* Add Custom DNS
