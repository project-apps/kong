# kong
Kong Configurations
-------Commands------
kong config -c kong.conf parse kong.yml

kong.conf path: /etc/kong/kong.conf

declarative_config = /usr/local/kong/kong.yml

Start Kong----> kong start [-c /etc/kong/kong.conf]

curl -i http://localhost:8001/
