# Docker Swarm Visualization

Here are a bunch of scripts that help you visualise a Swarm. It's a bit of a mess, and in a "works for me" state, so no guarantees it'll work for you.

Props to [Sean](https://github.com/Elesant), [Jeff](https://github.com/jeffdm) and [Alvin](https://github.com/alvinr) for building most of this.

## Running

1. Install [Docker Toolbox](https://www.docker.com/docker-toolbox).
2. Open the Docker Quickstart Terminal app to create a default machine and give you a Docker shell.
3. Set up a Swarm with Machine: https://docs.docker.com/swarm/install-w-machine/
4. Run `scripts/up.sh swarm-master` (assuming your Swarm master is called `swarm-master`)
5. Browse to port 3000 on your default machine (`open http://$(boot2docker ip default):3000` in your shell will do that for you)

