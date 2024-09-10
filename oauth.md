## oAuth


## Token

POST /realms/iocasta/protocol/openid-connect/token HTTP/1.1
Host: auth.iocasta.com.br:8443
Content-Type: application/x-www-form-urlencoded
Content-Length: 153
client_id=webapp&
client_secret=C7f3c0Jms9xNeIrt7O7WGjvJJ5pmCTGo&
grant_type=password&
username=wilson.duarte%40aecom.com&
password=Wilci5w78%23&
scope=openid


## Userinfo

``` curl
GET /realms/iocasta/protocol/openid-connect/userinfo HTTP/1.1
Host: auth.iocasta.com.br:8443
Content-Type: application/x-www-form-urlencoded
Authorization: Bearer 
scope: openid
```

## introspect
``` curl
POST /realms/iocasta/protocol/openid-connect/token/introspect HTTP/1.1
Host: 209.126.127.17:8443
Content-Type: application/x-www-form-urlencoded
Cookie: KEYCLOAK_LOCALE=pt-BR
Content-Length: 1935

grant_type=password&
client_id=webapp&
client_secret=C7f3c0Jms9xNeIrt7O7WGjvJJ5pmCTGo
&token=
```


## Artigo
https://medium.com/@prashikh2/end-to-end-role-based-authentication-and-authorization-using-keycloak-springboot3-and-react-js-849254f2a3c7



## FastAPI
https://github.com/ilyesAj/keycloak-fastAPI-integration
https://github.com/fastapi/fastapi/discussions/9066

##  fastapi-keycloak-middleware
https://fastapi-keycloak-middleware.readthedocs.io/en/latest/index.html
https://github.com/code-specialist/fastapi-auth-middleware/tree/main
https://fastapi-auth-middleware.code-specialist.com/

## .well-known/openid-configuration
https://auth.iocasta.com.br:8443/realms/iocasta/.well-known/openid-configuration

# pyoidc
https://pyoidc.readthedocs.io/en/latest/examples/rp.html
https://github.com/CZ-NIC/pyoidc

## Muito bom
https://www.keycloak.org/docs-api/21.1.1/rest-api/#_attack_detection_resource
https://www.oauth.com/
https://www.keycloak.org/docs/latest/authorization_services/#_overview_terminology
https://openfinancebrasil.atlassian.net/wiki/spaces
https://www.appsdeveloperblog.com/role-based-access-control-to-rest-api-with-keycloak/

https://datatracker.ietf.org/doc/html/rfc6749

https://www.appsdeveloperblog.com/keycloak-authorization-code-grant-example/

https://openid.net/specs/openid-connect-basic-1_0.html#UserInfoRequest
