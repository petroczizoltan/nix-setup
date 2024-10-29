# Installation

## Install Nix

Run command:

```shell
curl --proto '=https' --tlsv1.2 -sSf -L https://install.determinate.systems/nix | \
    sh -s -- install --determinate
```

## Setup the machine

Run command:

```shell
nix run nix-darwin --switch --flake .#work
```
