# k3s on OpenWrt
Makefile to generate OpenWrt .opkg packages from official k3s binaries.

## Usage
Run `make` to build the default version for `x86_64`. You can override ARCH and
VERSION, e.g `make ARCH=armhf`. See ARCHS and VERSIONS files for available
architectures and versions.
