# Monitor System Resources Using Netdata

## install netdata in your system 
sudo add-apt-repository universe
sudo apt update

## Install Netdata directly using APT
sudo apt install netdata
## Enable and start the Netdata service:
sudo systemctl enable --now netdata

## Run netdata in docker container 
 docker run -d --name netdata -p 19999:19999 -v /var/log:/host/var/log:ro netdata/netdata
 ![docker container]()
## view container in docker desktop (only if you are using)
![docker container]()


from desktop click the port currently container is running you will redirected to net data page 
![docker container]()



sign in as a first time user
![docker container]()


select the space
![docker container]()


create a private key to access dshboard and metrics for your running container
![docker container]()


here are the screen shots
![docker container]()

![docker container]()
