Ansible Vancouver Meetup

March 14, 2018

Follow up materials

* https://github.com/f5networks

* https://github.com/f5devcentral

* f5.com/supernetops

* https://github.com/f5devcentral/f5-super-netops-container

* https://github.com/0xHiteshPatel/f5-postman-workflows

* https://github.com/ArtiomL/f5-ansible

* https://f5cloudsolutions.slack.com/



docker run -it artioml/f5-ansible


bigip_user: "admin"
bigip_pass: "admin"
slack_token: "T9BG53PNW/B9P06ECU9/6TCk2ajPYlAfqCYRdW01xtZF"



./runsible.py app

./runsible.py -t app


./runsible.py iapp -n iapp_Web1 -i 10.100.115.115

./runsible.py iapp -n iapp_Web1 -t



docker run -p 8080:80 -p 2222:22 -p 10000:8080 --rm -it -e SNOPS_GH_BRANCH=master f5devcentral/f5-super-netops-container:jenkins
