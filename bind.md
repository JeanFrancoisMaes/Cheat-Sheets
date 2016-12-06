|yum install -y bind | installs bind |
|service named status | check if DNS services are active. | 
|service named start | start the DNS |

*use root*
## edit and change resolv.conf

/etc/resolv.conf 
cat it to see input

config the inward network interface 
network-scripts... 
DNS1=127.0.0.1 -> contents of resolv.conf
ifdown eth
ifup eth 
or network reload

date -s "2016-12-6 10:10:00"


##configuring forward and reverse lookup zones 






