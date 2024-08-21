# Wiremock

A simple repo to spin a wiremock server and map the local directory for stored mappings.

Use the following command to start a wiremock server with te APIs already imported from local directory 'mappings'.

```
docker-compose up -d
```

APIs are available at http://localhost:8080. You can configure the `docker-compose` file to change the port or mappings directory.
