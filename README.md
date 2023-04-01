# docker_CoreDns
 
# systemd-resolved
systemctl stop systemd-resolved
systemctl disable systemd-resolved
rm /etc/resolv.conf
systemctl restart NetworkManager