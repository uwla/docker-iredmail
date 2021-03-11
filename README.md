# DOCKER IREDMAIL

Deploy of [iRedmail](https://www.iredmail.org/) using `docker-compose`.

## SET UP

Configure the `env` file. You can simply run `cp .env.sample .env` and then change it according to your needs.

Before running the container, you need to have a proxy container to forward the requests to `iRedMail` container. An example of that is [my nginx proxy you can find in gitlab](https://gitlab.com/andresouzaabreu/docker-webproxy). Any proxy container should work fine.

## LICENSE

Do whatever you want with the code of this repo.
