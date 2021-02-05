#create user ipfs
adduser ipfs
chown -R ipfs:ipfs /home/ipfs
cd /home
chmod -R 750 ipfs
su - ipfs
ipfs init
exit
chsh -s /usr/sbin/nologin ipfs
