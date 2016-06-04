```
   ______              __           __
  /\__  _\          __/\ \__       /\ \
  \/_/\ \/     ___ /\_\ \ ,_\      \_\ \
     \ \ \   /' _ `\/\ \ \ \/      /'_` \
      \_\ \__/\ \/\ \ \ \ \ \_  __/\ \L\ \
      /\_____\ \_\ \_\ \_\ \__\/\_\ \___,_\
      \/_____/\/_/\/_/\/_/\/__/\/_/\/__,_ /
```

Batch scripts for Ruby production environment install on Ubuntu Server.

## Requirements

* Ubuntu Server 14.04

## Usage

Install packages first

```bash
sudo apt-get update
sudo apt-get install -y curl
curl -sSL https://git.io/vovQ1 | bash
```

### Install Nginx

Nginx [official package](http://nginx.org/packages/ubuntu/)

```bash
curl -sSL https://git.io/vovQM | bash
```

### Install RVM + Ruby

```bash
curl -sSL https://git.io/vovQS | bash
```

Use Ruby China mirror site for RubyGems and Ruby:

```
MIRROR=1 curl -sSL https://git.io/vovQS | bash
```

### Install MongoDB

```bash
curl -sSL https://git.io/vovQH | bash
```

### Install Redis

```bash
curl -sSL https://git.io/vovQ7 | bash
```
