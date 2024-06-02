# Wiremock

A simple repo to spin a wiremock server and map the local directory for stored mappings.

To spin the wiremock server, use the following command:

```
docker-compose up -d
```

Each mocked API has to be defiend ONLY in one json file. Wiremock cannot process array of mock definitions in one json file.
