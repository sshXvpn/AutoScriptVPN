
## AutoscriptVPN V23 Version 1.3.3 beta

## INSTALLATION
<pre><code>sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/sshXvpn/AutoScriptVPN/main/V23/V1.3.3/install.sh && chmod +x install.sh && sed -i -e 's/\r$//' install.sh && screen -S install ./install.sh</code></pre>

## V1.3.2 ADD SLOWDNS 
<pre><code>wget -q "https://raw.githubusercontent.com/sshXvpn/AutoScriptVPN/main/V23/V1.3.3/slowdns.sh" && chmod +x slowdns.sh && screen -S slowdns ./slowdns.sh</code></pre>

Dont forget run update on panel menu 100

## UPDATE
* Add auto delete expiry users every 00.00
* Add Auto reboot every 00.00
* Fix Instalation
* Add Custom DNS
* Add SlowDNS
* Add Backup System
