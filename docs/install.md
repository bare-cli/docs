---
id: Installation 
slug: /install
---

## Using snapstore 

> Currently Bare is only availabel for Linux

### Prequisites 

Since **Bare** is a compiled binary, there is no need for any other dependencies, except for [Snap](https://snapcraft.io/docs/installing-snapd)
> Get more information about [Bare snap](https://snapcraft.io/bare-cli)

### Install using Snap 
```shell
sudo snap install bare-cli --beta
```

To check installation

```shell
bare
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
