<p align="center">
   <img src="https://raw.githubusercontent.com/linuxmuster/archive/master/.github/media/lmn-logo.svg" alt="LMN logo" width="70%" />
</p>

<p align="center">
  <a href="https://github.com/linuxmuster/archive/actions/workflows/build-and-deploy.yml"><img src="https://github.com/linuxmuster/archive/actions/workflows/build-and-deploy.yml/badge.svg" /></a>
  <a href="https://ask.linuxmuster.net"><img src="https://img.shields.io/discourse/users?logo=discourse&logoColor=white&server=https%3A%2F%2Fask.linuxmuster.net" alt="Community Forum"/></a>
  <a href="https://www.gnu.org/licenses/agpl-3.0" ><img src="https://img.shields.io/badge/License-AGPL%20v3-blue.svg" /></a>
</p>

<p align="center">
This is the Linuxmuter.net archive. It is the place where you can get the latest versions of all Linuxmuster.net software.
</p>

# Setup

To use the repository, please follow these steps:

## 1. Import key:

```bash
wget -qO - "https://deb.linuxmuster.net/pub.gpg" | sudo apt-key add -
```

## 2. Add repo:

Currently, the `linuxmuster 7.1` testing and `linuxmuster-linuxclient7` and `linuxmuster-webui7` packages are here available.

### Linuxmuster 7.1 testing (including base, linbo & webui pkgs)

```bash
sudo sh -c 'echo "deb https://deb.linuxmuster.net/ lmn71 main" > /etc/apt/sources.list.d/lmn71.list'
```

### Linuxclient7

Choose ONE of these depending on your system:

##### Ubuntu 20.04 Focal:

```bash
sudo sh -c 'echo "deb https://deb.linuxmuster.net/ focal main" > /etc/apt/sources.list.d/lmn7.list'
```

##### Ubuntu 18.04 Bionic:

```bash
sudo sh -c 'echo "deb https://deb.linuxmuster.net/ bionic main" > /etc/apt/sources.list.d/lmn7.list'
```

### Webui7 (Linuxmuster 7.0 stable)

```bash
sudo sh -c 'echo "deb https://deb.linuxmuster.net/ lmn70 main" > /etc/apt/sources.list.d/lmn7.list'
```


## 3. Apt update

```bash
sudo apt update
```
