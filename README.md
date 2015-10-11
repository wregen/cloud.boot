# cloud.boot
A demo of booting PC from the cloud.

In order to perfor this demo, you need to have VirtualBox (I am using v.5) installed.

1. Open [https://github.com/4clouds/cloud.boot](https://github.com/4clouds/cloud.boot) in your browser.
2.  Download [ipxe-4clouds-boot.iso](https://github.com/4clouds/cloud.boot/raw/gh-pages/ipxe-4clouds-boot.iso). It is customized version of [ipxe.iso](http://boot.ipxe.org/ipxe.iso) from [http://ipxe.org/](http://ipxe.org/). The only difference is that instead of booting to the IPXE shell, it executes boot script stored in the repository: [boot.ipxe](https://github.com/4clouds/cloud.boot/blob/gh-pages/boot.ipxe). Boot.ipxe remotely boots customized Porteus Kiosk LiveCD linux, that starts [http://4clouds.io](http://4clouds.io)
3. Create new VirtualBox VM, it can be made without a HDD, but ipxe-4clouds-boot.iso should be mounted to the VM's DVD drive.
4. Once mounted it will start IPEX bootloaded, which will load Porteus Kiosk LiveCD linux from the github and start it.

[![Booting from github](https://raw.githubusercontent.com/4clouds/cloud.boot/gh-pages/yt.jpg)](https://www.youtube.com/watch?v=nqMk_LYQsXQ)



