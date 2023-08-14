# Keycloak Test Auth

---
Este proyecto surge como parte la práctica con el sistema Keycloak. El objetivo principal es probar la seguridad de una aplicación de spring boot básica teniendo a keycloak como emisor de credenciales. Esta aplicación será una API de un solo endpoint.

## Librerías

-  keycloak-spring-boot-starter -> Depreciado así que no se debe usar.
- spring-boot-starter-oauth2-client -> Usen esta
- spring-boot-starter-oauth2-resource-server -> Para validar token de keycloak
- keycloak-core -> Acceso a métodos de kaycloak
- keycloak-policy-enforcer 