# Installation
Clone the repository

Change .env variables to your actual .env variables.



## On Linux VM
Setup the basics in the VM.

### Installing Docker
```
sudo apt install docker.io
sudo apt install docker-compose -y
sudo usermod -aG docker $USER
exit
```

### Cloning the repository
```
git clone <rep>
```

### Changing the .env file
```
cd /<folder>
ls -la
mv .env-example .env
nana .env
CTRL + O
CTRL + X
```

### Starting the container
```
docker-compose up -d
```