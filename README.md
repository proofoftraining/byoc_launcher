# Project Repository README

## Prerequisites

Before you can use this repository, ensure you have the following prerequisites installed:

- **NVIDIA Drivers**: Check if NVIDIA drivers are installed by running `nvidia-smi` in your terminal.
- **Docker**: Docker must be installed on your system.
- **NVIDIA Docker Toolkit**: Required for Docker to utilize GPU capabilities.
- **Docker Compose Plugin**: Install this by running the following commands:
  ```bash
  sudo apt-get update
  sudo apt-get install docker-compose-plugin
  ```


Additionally, ensure that port 5000 is exposed on your server. This port is configurable by editing the Docker compose file if needed.
Installation

## Installation

```bash
git clone https://github.com/proofoftraining/byoc_launcher.git
cd byoc_launcher/
sudo bash launcher.sh
```

This process will take a while to download the base model. Once the download is complete you will be prompted for your server key from the tromero website.

## Usage
After completing the installation

```bash
curl ifconfig.me
```
This will output your public IP address, which you will need to enter on the website. In the format
```bash
http://<your_ip_address>:5000
```
