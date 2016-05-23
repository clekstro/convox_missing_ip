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
