# WargamesHelper
A password manager and connector for Wargames.

## System
```sh
Ubuntu 20.04.4 LTS
```

## Install

```sh
apt install sshpass gnome-shell
pip3 install click
```

## Usage

### Commands

```sh
$ ./helper --help
Read: ./config.json
Usage: helper [OPTIONS] COMMAND [ARGS]...

Options:
  -n, --name TEXT
  -p, --password TEXT
  --help               Show this message and exit.

Commands:
  bandit
  config
```

### Config

```sh
$ ./helper config --help
Read: ./config.json
Usage: helper config [OPTIONS] NAME VALUE

Options:
  --help  Show this message and exit.
```

### Bandit

```sh
$ ./helper bandit --help
Read: ./config.json
Usage: helper bandit [OPTIONS] LEVEL

Options:
  -p, --password TEXT
  --connect / --dont-connect
  --remember / --dont-remember
  --help                        Show this message and exit.
```
