# PROOT Installer

## Overview

This shell script is designed to automate the installation of Ivan Ssl / @ivansslo [CertVeis], a lightweight any operating system environment using Proot.

## Prerequisites

- Bash shell environment
- Internet connectivity
- Wget installed
- Supported CPU architecture: x86_64 (amd64) or aarch64 (arm64)

## Installation

step 1. Clone the repository:

    
    git clone https://github.com/ivansslo/accroot && cd accroot
    
    
step 2. Run script:

  ```sh
  bash root.sh # exit reconnect
  ```
  
You can move chroot in home.(ex: mv accroot/chroot /home/master/chroot )
Execute On Acrh in home:
    
  ```sh
  
  bash accroot/chroot # In cloud type: su - root
  ```

## Supported Architectures

- x86_64 (amd64)
- aarch64 (arm64)

## License

This Proot Installer script is released under the [MIT License](LICENSE).

## Launch your vps with proot
[![Binder](https://mybinder.org/badge_logo.svg)](https://certveis.space/v2/gh/ivansslo/chroot.git/HEAD)
