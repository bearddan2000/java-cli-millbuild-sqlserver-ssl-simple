# java-cli-millbuild-sqlserver-ssl-simple

## Description
A java gradle build, that connects to sqlserver database.

Sql server uses self-signed ssl.

## Tech stack
- java
- millbuild
  - 6.8.2

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- nightscape/scala-mill

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
