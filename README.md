# Script for install linux kernel on OpenSUSE Tumbleweed

If you are using OpenSUSE Tumbleweed, and encounter an error like `Cannot find LILO.` when installing your manually built kernel by `make install`, you can try to solve it by dropping the `installkernel` script into `/sbin`. This script was extracted from the deleted file of [this commit](https://raw.githubusercontent.com/openSUSE/dracut/e5fc2048dc7c6db9bb4f916bf88db7425b923ce4/suse/dracut-installkernel).
