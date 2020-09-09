# HRD_RSP_NAS

Server 101 With Pi
- Components of a server
- How server works and securing it
- Getting close with Linux and Shell

STEPS (working with Windows)
1. Fit Raspberry Pi for Server(Static IP, passwd, sshd_config, ufw)
2. Create shh keys with PuTTY and send public key to Pi(Server)
3. Configure RAID array (2x32Gb, RAID 1)
4. Install Docker and edit systemd unit file (/lib/systemd/system/docker.service)
5. Run Nginx with docker (connect to http://< hostname >.local/)


with help from
1. https://blog.alexellis.io/hardened-raspberry-pi-nas/
2. https://gist.github.com/leandrofilipe/f9636be272f97d414652ce1f21e6b1f4
