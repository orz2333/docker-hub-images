# Arukas CLI [![Circle CI](https://circleci.com/gh/arukasio/cli.svg?style=shield)](https://circleci.com/gh/arukasio/cli)

* Website: https://arukas.io

## What is Arukas

[https://arukas.io/](https://arukas.io/)

## arukasio/arukas

arukasio/arukas:latest [![](https://badge.imagelayers.io/arukasio/arukas:latest.svg)](https://imagelayers.io/?images=arukasio/arukas:latest 'Get your own badge on imagelayers.io')
arukasio/arukas:dev [![](https://badge.imagelayers.io/arukasio/arukas:dev.svg)](https://imagelayers.io/?images=arukasio/arukas:dev 'Get your own badge on imagelayers.io')

## QuickStart

* Get API key here https://app.arukas.io/settings/api-keys
* `docker run --rm -e ARUKAS_JSON_API_TOKEN=<YOUR_API_TOKEN> -e ARUKAS_JSON_API_SECRET=<YOUR_API_SECRET> arukasio/arukas`

## Help

```
usage: docker run --rm arukasio/arukas [<flags>] <command> [<args> ...]

A CLI for Arukas Cloud

Flags:
  --help  Show context-sensitive help (also try --help-long and --help-man).

Commands:
  help [<command>...]
    Show help.

  ps [<flags>]
    Show status of containers

  rm <container_id>
    Remove a container

  run --instances=INSTANCES --mem=MEM --ports=PORTS [<flags>] <image>
    Create and run a container. The container must run as a daemon.

  start <container_id>
    Start one stopped container

  stop <container_id>
    Stop one running container

  version
    Print version information and quit
```