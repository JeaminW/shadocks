# ShaDocks

## Introduction

Just a Docker image for Shadowsocks. Thanks to Alpine Linux, it has amazing light weight, just 7.67 MB after decompression.

## Basic Usage

### Step 0: Install Docker

### Step 1: Run command

    docker run -e SS_METHOD="<YOUR_DESIRED_METHOD_HERE>" -e SS_PASSWORD="<SET_YOUR_PASSWORD_HERE>" -p <YOUR_DESIRED_PORT_HERE>:8388 -d bohan/shadocks

or just

    docker run -p <YOUR_DESIRED_PORT_HERE>:8388 -d bohan/shadocks

with default password `shadowsocks` and default method `aes-256-cfb`.

## Other Usage

You can edit the Dockerfile for further customization or just reference.

## License

WTFPL
