# groovy-web-maven-spring-thyme-ssl-postgres

## Description
A POC for springboot web app with thymeleaf support
connecting to a database.

Uses self-sign ssl.

## Tech stack
- java
- maven
  - springboot
  - thymeleaf
  - postgres connector
- bootstrap
- jquery
- dataTable

## Docker stack
- alpine:edge
- postgres
- openjdk:11-jdk

## To run
`sudo ./install.sh -u`
Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://spring.io/guides/gs/accessing-data-mysql/
- https://medium.com/@gustavo.ponce.ch/spring-boot-jquery-datatables-a2e816e2b5e9
