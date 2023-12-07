# Usefull commands 

==> to copy one file to remote ssh 
```
cat file1 | ssh remotehost 'cat > file2'
```

===> remove all containers even stopped one 
```
docker container prune
```

===> remove all running containers
```
docker rm $(docker ps) 
```


```
gcloud config list
```



```
gsutil ls
```

```
ipconfig
ssh -L 8080:localhost:8080 172.21.192.1 -N

```

```
sudo groupadd docker
```

```
sudo gpasswrd -a $USER docker
```

put docker-compose executable in /bin and add it in PATH var in bashrc.sh


==> generate ssh keys for gcloud 
``` 
ssh-keygen -t rsa -f ~/.ssh/strong -C USERNAME -b 2048
```
