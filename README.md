# Onboardbase CTL
Onboardbase CTL is a CLI tool for setting up Onboardbase platform to be hosted locally.

## Installation

### bash (Recommended)
```
curl https://onboardbase.github.io/obbctl-sh/ | bash
```
### npm
```
npm i -g @onboardbase/obbctl
```

<!-- ## yarn
```
yarn global add @onboardbase/obbctl
``` -->
### brew
```
brew tap onboardbase/obbctl

brew install obbctl
```
## Usage
Run the following to see all the available commands:
```
obbctl help
```
This will display information about the CLI

```
> obbctl help

A CLI for setting up Onboardbase for self-hosted deployments

Usage:
  obbctl [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  help        Help about any command
  setup       Setup deployment for either backend or frontend
  start       Start the bootstrapped services

Flags:
      --config string   config file (default is $HOME/.ctl.yaml)
  -h, --help            help for obbctl
  -t, --toggle          Help message for toggle
  -v, --version         version for obbctl

Use "obbctl [command] --help" for more information about a command.
```

### Initializing
You can find detailed instructions on how to use this CLI tool [here](https://docs.onboardbase.com/docs/selfhosting-overview).
