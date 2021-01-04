

### Dockerize existing laravel project using laradock and vagrant

### You can find the tutorial at: https://josafebalili.com/posts/Dockerize-existing-Laravel-project-with-Laradock-and-Vagrant/

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
