# server_ping_check
A bash script checks connectivity of server list and send mail

This is very basic script to check servers connectivity, its simply get ips from server_list file and send mail to yourmail@domain.com . Dont forget the change with your own mail.

You need 2 packages mailx and fping. You can install them;

apt install mailx fping
yum install mailx fping

You can use it with;
cd /root
git clone https://github.com/Megilindar/server_ping_check.git
cd server_ping_check/
chmod +x server_ping.sh
./server_ping.sh

