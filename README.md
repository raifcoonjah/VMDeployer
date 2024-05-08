# VMDeployer

VMDeployer is a bash script that will generate a VM using qemu/kvm in a matter of seconds.

# Prerequisites

1. Working internet, please use the following guide if you require any help:
https://wiki.libvirt.org/Networking.html

2. A Cloud image, by default VMDeployer uses `Debian12 geneic` image, but this can be changed in the script directly. If the image is not found locally, VMDeployer will automatically download it in the correct directory. 

# Default variables

VMDeployer has multiple default variables set in the script, these can be changed to anything you desire, quickly.

```shell
# Defaults
DEFAULT_RAM_MB=512
DEFAULT_DISK_SIZE=4  # In GiB
```
