# api-firstTest

#app run on : localhost:8081

Set SE-Linux: setenforce 0

Set firewalld : firewall-cmd -permanent --add-port=8081/tcp

Set permission file : chmod 755 -R ./NodejsRestAPI 

Install module package : npm install express --save 

Run app : node app.js
