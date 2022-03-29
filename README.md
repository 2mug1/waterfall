# waterfall

`docker-compose.yml`
```yml
version: '3'

services:

  waterfall:
    container_name: waterfall
    image: ghcr.io/takagi-minecraft-lab/waterfall
    volumes:
      - ./waterfall:/app
    tty: true
    stdin_open: true
    environment:
      JAVA_OPTS: "-Xms256M -Xmx512M"
```

## LICENSE
MIT License