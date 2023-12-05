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
ssh -L 8080:localhost:8080 your_local_ip -N
```
