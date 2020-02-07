![Node.js CI](https://github.com/jpeerz/fourpagesdotcom/workflows/Node.js%20CI/badge.svg)

## Setup osx development environment

	git clone git@github.com:jpeerz/fourpagesdotcom.git .
	brew install docker-machine
	docker-machine create devone
	eval `docker-machine env devone`

## Create nodejs app

	docker run -it -w /home/node/app -v $PWD:/home/node/app node:12-alpine /bin/sh

