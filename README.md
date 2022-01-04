# elk-keycloak
1) change your Domain or Ip address in all the config file and setup proper keyclok and kibana details.

CMD: docker-compose -f keycloak.yml up -d

2) Run keycloak first and import oauth2.json in client

3) Get securty token and change in kibana.yaml

4) Run docker-compose.yaml file

CMD: docker-compose -f  up -d
