# depose
Simple wrapper for docker-compose which makes dealing with multiple environments easier.

## Installation

```bash
composer require yogarine/depose
```


## How to use

```bash
Usage:
  vendor/bin/depose [STAGE] [depose options] [options] [COMMAND] [ARGS...]
  vendor/bin/depose -h|--help

Depose Options:
  -E, --env-file              .env file to use
  -C, --no-cli                If set, Compose doesn’t attempt to use the Docker
                              CLI for interactive run and exec operations
  --no-compatibility          Don't attempt to convert keys in v3 files to
                              their non-Swarm equivalent
  -F, --foreground            Foreground mode: Run containers in the foreground
```