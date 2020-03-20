# gia-midpoint-keycloak
Docker compose contenant midpoint openldap et keycloak interconnectés


```
docker exec ldap-host ldapsearch -x -H ldap://localhost -b dc=localhost,dc=diplomatie,dc=gouv,dc=fr -D "cn=admin,dc=localhost,dc=diplomatie,dc=gouv,dc=fr" -w MaE12345
```
