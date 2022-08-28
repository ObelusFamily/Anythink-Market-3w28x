# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Install docker tools.
- [Install Docker Desktop](https://docs.docker.com/get-docker/)
- Install OS package
   - docker engine from Ubuntu seems compatible
   - docker-compose is NOT compatible
      - Download binary from [Compose Releases](https://github.com/docker/compose/releases)
      - Copy binary to ~/.docker/cli-plugins
      - Rename to docker-compose
      - Run ```sudo chmod +x docker-compose``` to make binary executable
      - Create alias
         - If alias file does not exist, create ```~/.bash_alias```
         - Add ```alias docker-compose='$HOME/.docker/cli-plugins/docker-compose'

