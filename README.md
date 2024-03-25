# IntelliJ HTTP Client

This repo contains a variety of requests configured for use with the IntelliJ HTTP Client.

## Secret Env

The file `./environment/http-client.private.env.json` must be created after cloning this repo with the following contents:

```json
{
  "openai": {
    "key": "..."
  },
  "apps-dev": {
    "craigmiller_username": "...",
    "craigmiller_password": "...",
    "postman_clientId": "...",
    "postman_clientSecret": "...",
  },
  "apps-prod": {
    "craigmiller_username": "...",
    "craigmiller_password": "...",
    "postman_clientId": "",
    "postman_clientSecret": ""
  }
}
```