# Docker 101 - Docker Desktop installation for Mac

Docker Desktop ships with a local Kubernetes installation.

## Prerequisites

- Mac running macOS with the latest Intune compliant version
- Homebrew

## Installation


## Running

Now you have Docker desktop up and running, let’s explore.

First of all, let’s check if docker CLI is usable so in your shell run:

	docker --version

This shows you the Docker client  version.

Let’s check if there are any containers running:

	docker ps

If you are following along while connected to the office or the VPN, you need to disconnect the internal network and perform the rest of the commands in the workshop with your home network or hotspot.
Run the following next:

	docker run -d -p 80:80 docker/getting-started

