# java-web-millbuild-spring-jsf-cockroachdb-single-node-without-ssl-simple

## Description
A jsf springboot java gradle build,
that connects to cockroach database.

A java gradle build, that connects to single node
cockroach database without ssl.

## Tech stack
- springboot
  - jsf
- millbuild
  - postgres drivers
  - lombok
- bootstrap
- jquery
- dataTable

## Docker stack
- cockroachdb/cockroach:v19.2.2
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`
- [web app](http://localhost)
- [webui](http://localhost:8080)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Cockroach setup](https://github.com/s0rg/cockroach-compose)
