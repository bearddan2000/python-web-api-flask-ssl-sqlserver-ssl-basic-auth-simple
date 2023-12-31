# python-web-api-flask-ssl-sqlserver-ssl-basic-auth-simple

## Description
Creates an api of `dog` for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.
Uses basic authentication and self-signed ssl.

| username | password |
-----------------------
| user | pass |

Sql server uses self-signed ssl.

## Tech stack
- python
- flask
- sql server

## Docker stack
- alpine:edge
- python:latest
- mcr.microsoft.com/mssql/server:2017-CU17-ubuntu

## To run
`sudo ./install.sh -u`
- Endpoint
  - [Availble](https://localhost/dog)

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
- https://stackoverflow.com/questions/27766794/switching-from-sqlite-to-mysql-with-flask-sqlalchemy
