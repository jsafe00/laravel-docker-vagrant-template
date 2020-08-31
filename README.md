

### Dockerize existing laravel project using laradock and vagrant

### You can find the tutorial at: http://safventure.live/dockerize-existing-laravel-project-with-laradock-and-vagrant

To execute:

In the root folder:

```
vagrant up
```
```
vagrant ssh
```
```
cd /home/vagrant/laravel/code/laravel/laradock
```

```
docker-compose up -d mysql nginx
```

Accessing laravel project in the browser:

```
192.168.33.10
```