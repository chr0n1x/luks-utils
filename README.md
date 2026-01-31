LUKS Util Scripts
===

Stupid scripts to interact with LUKS drives, generalized for anyone to use.

# Prerequisites

Most of this was taken from [this nixCraft article](https://www.cyberciti.biz/security/howto-linux-hard-disk-encryption-with-luks-cryptsetup-command/)

1. need a system and user with `cryptsetup` and the `LUKS` plugin (e.g.: `apt install cryptsetup cryptsetup-luks`)
2. a drive that you can mount and want to store data to

# Installation

1. clone this repo to a location owned by a user on your system that can interact with `cryptsetup`
2. `ln -sf /path/to/cloned/repo /symlink/path/in/your/PATH`
