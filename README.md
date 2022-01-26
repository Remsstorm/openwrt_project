# openwrt_project
install module kmod-br-netfilter
###directory for arp interfaces 
echo 1 > /sys/class/net/br-guestlan/bridge/nf_call_iptables


for isolation clients
