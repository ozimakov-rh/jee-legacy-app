# Java EE Modernization Story - Initial Java EE 8 project

[![Maven Build](https://github.com/ozimakov-rh/jee-legacy-app/actions/workflows/default.yaml/badge.svg)](https://github.com/ozimakov-rh/jee-legacy-app/actions/workflows/default.yaml)

- Java 8
- Java EE 8
- H2 (datasource managed by application server)
- Form authentication (managed by application server)

Tested with Wildfly / JBoss EAP 13 ([download](https://download.jboss.org/wildfly/13.0.0.Final/wildfly-13.0.0.Final.zip))

Build by running `./mvnw package`

Access web application
* http://localhost:8080/user-webapp
* http://localhost:8080/admin-webapp
