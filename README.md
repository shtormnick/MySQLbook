# SQLbook

SQL tutorial

## Install
```
vagrant up
```
#### Ssh tunnel
ip: `192.168.33.10`

proxy user `vagrant`

proxy password `vagrant`

#### Db connection
login `bunny`

password `1234`

database `movie`

## pgAdmin 4
```
cd /home/vagrant/pgAdmin4/
source bin/activate

python $(find . -wholename "*pgadmin4/setup.py")
python $(find . -wholename "*pgadmin4/pgAdmin4.py")
```

after settings for auto start run `sudo systemctl enable pgadmin4`

## DataGrip

```
Ctrl+Alt+U - ERD diagramm
```
