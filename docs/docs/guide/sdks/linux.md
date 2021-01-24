
# Linux

## The 'Linux' Target

Wonkey uses the **`gcc`** command line tools to build desktop apps for Linux.

You will also need to install all the developer libraries required by the compiler and modules. This will differ depending on the precise version of Linux you have, but to get you started:

```
sudo apt-get update && sudo apt-get upgrade
sudo apt-get install g++-multilib libopenal-dev libpulse-dev libsdl2-dev
```
