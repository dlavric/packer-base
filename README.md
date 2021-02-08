## Packer Base for learning

### Repository creates a Vagrant virtual box with Ubuntu LTS

### This repo is based on the following repo: [packer-xenial64](https://github.com/nielsabels/packer-xenial64)

### Prerequisites
- [X] [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

- [X] [Vagrant](https://www.vagrantup.com/downloads)

- [X] [Packer](https://www.packer.io/downloads)

## How to Use the Repo
- Clone this repo:
```shell
$ git clone git@github.com:dlavric/packer-base.git
```

- Go to the directory where the repo is stored
```shell
$ cd packer-base
```

- Start Packer
```shell
$ packer build newtemplate.json
```

