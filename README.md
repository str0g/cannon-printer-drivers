# canon-printer-drivers
canon printer drivers cups only.

Building process:
Its required to download drivers directly from https://www.canon.pl/support/consumer_products/products/

There are two possibilites some printers can work directly with CUPS and are not CPU architecture specific
* UFRII - platform independent but most likely desire device will not be supported.
* cque - only x86_64 unless modified PKGBUILD and download for x86, however it seems to support greater range of devices.
