# Requirements
- Homestead
- artisan - link to documentation
- gulp
- ES - on the future
- Redis - on the future

# Get Started
1. git clone
2. conf homestead.yaml
3. Up homestead virtual machine
4. check your http://url.local
5. install DB / migration (check bellow)

## DB
1. vagrant ssh
2. mysql -uhomestead -psecret

Sequel Pro
host 127.0.0.1
username homestead
password secret
port 3306
ssh host 192.168.10.10
ssh user vagrant
ssh password vagrant

In case of migration update database.php
'port'      => '33060',