# Ansible Vancouver Meetup

## March 14, 2018

#### Follow up materials

* https://www.slideshare.net/secret/9phz1WQQc80PO

* https://github.com/f5networks

* https://github.com/f5devcentral

* f5.com/supernetops

* https://github.com/f5devcentral/f5-super-netops-container

* https://github.com/0xHiteshPatel/f5-postman-workflows

* https://github.com/ArtiomL/f5-ansible

* https://f5cloudsolutions.slack.com/

#### Tonight's demo was based off this: https://github.com/ArtiomL/f5-ansible

* https://www.youtube.com/watch?v=5QiNgWZeOw0

* https://www.youtube.com/watch?v=hy7GU2GfsWc

```
docker run -it artioml/f5-ansible

ansible-vault edit creds.yml
Vault password: password

vi ./inventory/hosts
```


```
./runsible.py app

./runsible.py -t app
```

```
./runsible.py iapp -n iapp_Web1 -i 10.100.115.115

./runsible.py iapp -n iapp_Web1 -t
```


#### To run the F5 Super-Netops container
```
docker run -p 8080:80 -p 2222:22 -p 10000:8080 --rm -it -e SNOPS_GH_BRANCH=master f5devcentral/f5-super-netops-container:jenkins
```
