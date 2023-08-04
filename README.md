# bytes at work AG BSP base files for AM62x based modules

This repository is intended to setup a working Yocto Project environment to
build software for byteDEVKIT AM62x by [bytes at work AG](https://www.bytesatwork.io).

## Usage

This repository is used with [meta-bytesatwork](https://github.com/bytesatwork/meta-bytesatwork)
and [meta-bytesatwork-ti](https://github.com/bytesatwork/meta-bytesatwork-ti).

Example:

	MACHINE=bytedevkit-am62x DISTRO=poky-bytesatwork EULA=1 . setup-environment build

Please have a look at the mentioned repositories for possible combinations of
images, machines, and distros.

For an easier setup, have a look at
[bsp-platform-ti](https://github.com/bytesatwork/bsp-platform-ti).
