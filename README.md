<a href="https://www.boid.com/"><img src="https://raw.githubusercontent.com/Boid-John/eos-airdrops/master/logos/BoidLogo-lg.png" title="Boid" alt="Boid"></a>

<p align="center">
    <a href="https://t.me/Boidcom_official">
        <img src="https://img.shields.io/discord/431917998102675485.svg" alt="Telegram">
    </a>
    <a href="LICENSE">
        <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg" alt="MIT License">
    </a>
    <a href="https://twitter.com/boidcom">
        <img src="https://img.shields.io/twitter/url/http/shields.io.svg?style=social&style=plastic" alt="Twitter">
    </a>
</p>


# Boid-Cluster CLI

> A linux command line interface for creating Boid clusters 

### From a fresh Debian/Ubuntu install:
```shell
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash

command -v nvm

nvm install node
```
##### This CLI has only been tested on Debian based distributions.


### Setup

> install this package first

```shell
$ npm install boidcmd-cluster -g
```

> now setup boid 

```shell
$ boidcmd-cluster setup
```
##### Note: The setup phase runs: 
sudo apt install boinc-client -y
##### If you want to manually install boinc, you can run this line yourself before running setup.


> additional commands can be found in the help menu

```shell
$ boidcmd-cluster help
```