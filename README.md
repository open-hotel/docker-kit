# Docker Kit

Docker Kit is a docker-environment with built-in to run open-hotel
automatically. You just need to have [docker-compose](https://docs.docker.com/compose/install/)
installed to run it.

Our packages:

- [Client](https://github.com/open-hotel/open-hotel-client/)
- [Orion Emulator](https://github.com/open-hotel/orion-emulator)

## How to run the environment

Clone the repositories:

```bash
git clone git@github.com:open-hotel/orion-emulator.git
git clone git@github.com:open-hotel/open-hotel-client.git
# or
./start.sh
```

Build the compose environment:

```bash
docker-compose build
docker-compose up
```

Now you should be up and running!

Any problems? [Create an issue](https://github.com/open-hotel/docker-kit/issues/new)
