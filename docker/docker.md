# Delete all containers

    docker rm $(docker ps -a -q)

# Delete all images

    docker rmi $(docker images -q)

# Stop all

    docker stop $(docker ps -a -q)

# Linux: Stop using sudo

    sudo groupadd docker
    sudo gpasswd -a ${USER} docker
    sudo service docker restart

# How to change docker machine ip address using VirtualBox

First get the current address:  (default is the name of the machine)

```
$ docker-machine ip default
192.168.99.100
```

Go to VirtualBox preferences:

[VBPref](./VBpref.png)
