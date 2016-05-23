## Reproducing

Create your local image specified in the `docker-compose.yml` file with:

```bash
$ docker build -t your_image_here .
```

Then run:

```bash
$ convox start
```

You should then be able to see some similar output to the following:

```bash
invalid value "app_name-db:" for flag --add-host: invalid IP address in add-host: ""
```

## Versions
Mac OSX 10.11.5
Docker version 1.11.1, build 5604cbe
docker-compose version 1.7.1, build 0a9ab35
convox versions:
client: 20160521123902
server: 20160521030812 (console.convox.com)
