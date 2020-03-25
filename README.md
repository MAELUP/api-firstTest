# api-firstTest
app run on > http://localhost:8081

# install
Set SE-Linux > setenforce 0

Set firewalld > firewall-cmd -permanent --add-port=8081/tcp

Set permission file > chmod 755 -R ./NodejsRestAPI 

Install module package > npm install  

Run app > node app.js
