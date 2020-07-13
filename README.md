# gentoo-bashrc for archlinux #

### Sync ###

```bash

# Open the terminal and go to download folder
 $ cd ~/Downloads
 
# Download the package
 $ wget -c https://github.com/linusdan/gentoo-bashrc-arch/raw/primary/snapshot/gentoo-bashrc.tar.gz

# Check MD5SUM of file:
 $ md5sum gentoo-bashrc.tar.gz

# Sync
 $ tar -xzvf gentoo-bashrc.tar.gz && cd gentoo-bashrc
```

### Build & Use ###

```bash
# I got the magic with me... Let's go to the build...
 $ makepkg -i

# After install, the bashrc file will not be replaced immediately. You need to run the command as normal user:
 $ sudo cp -f /usr/share/gentoo-bashrc/bashrc ~/.bashrc

# And then logged as root:
 $ cp -f /usr/share/gentoo-bashrc/bashrc ~/.bashrc
 ```

View MD5SUM:
* [**MD5SUM**](https://raw.githubusercontent.com/linusdan/gentoo-bashrc-arch/primary/snapshot/MD5SUMS)
