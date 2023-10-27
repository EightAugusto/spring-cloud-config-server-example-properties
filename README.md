# Spring Cloud Config Server Example Properties

This project is part of [Spring Cloud Config Server Example](https://github.com/EightAugusto/spring-cloud-config-server-example) and can be consumed following the README.md instructions.

---
## Consume properties

```bash
SPRING_CLOUD_CONFIG_SERVER=http://localhost:8888; \
APPLICATION=example-service; \
APPLICATION_PROFILE=develop; \
curl -X GET ${SPRING_CLOUD_CONFIG_SERVER}/${APPLICATION}/${APPLICATION_PROFILE}
```