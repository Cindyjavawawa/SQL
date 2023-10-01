# SQL

# Build docker
Switch to administrator
```
su root
```
View the OS version
```
cat /etc/redhat-release
```
Check whether docker is created
```
docker --version 
```
OR
```
docker -v
```
Install docker
```
sudo yum install -y yum-utils
```
```
sudo yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
```
```
sudo yum install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
```
When the 'Complete!' display, it has been completed.

```
sudo systemctl start docker
```
```
sudo docker run hello-world
```
Check whether docker is created
```
docker --version 
```
It will show as following
```
Docker version 24.0.6, build ed223bc
```
