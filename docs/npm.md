---
id: Installation 
slug: /install
---

## Using NPM

> Currently Bare is only availabel for Linux

### Prequisites 

Since **Bare** is a compiled binary, there is no need for any other dependencies, except for **NPM** and **Node** as it is required to install the binary based on the platform and architecture.

### Install using NPM
```shell
npm i -g barego
```

To check installation

```shell
bare
```

### To install the nightly build

```shell
npm i -g bare-cli/bare#dev
```
	
Revert back to `latest build` using 
```shell
npm i -g barego
```

## Build from source

- Clone the repo
	```shell
	git clone https://github.com/bare-cli/bare.git
	```
	using [gh](https://github.com/cli/cli)
	```shell
	gh repo clone bare-cli/bare <destination>
	```

- Change directory to your local copy: 
	```shell
	cd <folder-name>
	```
- Install all the go dependencies
	```shell
	make setup
	```
- Build `Bare`
	```shell
	make build
	```
	The output binary can be found in `bin` folder
