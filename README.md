# Drone

## Install Docker
https://docs.docker.com/engine/installation/linux/ubuntu/#install-using-the-repository

```
sudo apt-get install \
    apt-transport-https \
    ca-certificates \
    curl \
    software-properties-common
```

```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```

```
sudo add-apt-repository \
   "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
   $(lsb_release -cs) \
   stable"
```


```
sudo apt-get update
```

```
sudo apt-get install docker-ce
```

```
sudo apt-get install python-pip
```

```
sudo pip install docker-compose
```

```
sudo adduser YOURUSERNAME docker
```

## Setup drone for you

see http://readme.drone.io/admin/setup-bitbucket/

edit `docker-compose.yml`

add your oauth key and secret.
