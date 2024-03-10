# IntelliJ HTTP Client

This repo contains a variety of requests configured for use with the IntelliJ HTTP Client.

## Secret Env

The file `./environment/http-client.private.env.json` must be created after cloning this repo with the following contents:

```json
{
  "openai": {
    "key": "..."
  }
}
```