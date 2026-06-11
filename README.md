# Summorist devops project

## Run

### Preparation

You need to have microservices
(they are listed in [shared repository](https://github.com/Azat201003/summorist-shared))
directories for any `root` directory like this:

```
root/summorist-mores
root/summorist-users
...
root/summorist-devops
```

If you wanna use users service, you need to export keys environment variables,
script `scripts/generate_keys.sh` of summorist-users repository does it
(with source command). It made for security.

``` bash
cp .env.example .env
docker compose up
```
