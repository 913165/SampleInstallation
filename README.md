# SampleInstallations

1 : Apache Ignite web console installation on local

- docker pull apacheignite/web-console-standalone
- docker run -d -p 80:80 -v localhost:/var/lib/mongodb --name web-console-standalone apacheignite/web-console-standalone

2 : Mysql installation on docker

- docker run --name mysql1 -e MYSQL_ROOT_PASSWORD=root -d mysql:latest
- docker run --link 9c06450d7f65:db -p 8080:8080 adminer




