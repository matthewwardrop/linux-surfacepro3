# linux-surfacepro3
Arch Linux package to compile the Linux kernel with patches designed to improve user experience on the Surface Pro 3.

This is based on the offical Linux kernel package provided by Arch Linux at: https://projects.archlinux.org/svntogit/packages.git/tree/trunk?h=packages/linux .

This AUR package adds the following patches to the official Linux kernel package:
 - Battery patch from https://github.com/nuclearsandwich/surface3-archlinux/issues/16 (patch from `colorprint`)
 - Camera patch from https://github.com/nuclearsandwich/surface3-archlinux/issues/12 (patch from `colorprint`)
 - Buttons and Wakeup patches from http://bugzilla.kernel.org/show_bug.cgi?id=84651 (patches from Chen Yu, comments #56 and #57)
 - Multitouch patches* (backported from the 4.0 patch) from https://gist.github.com/felipeota/afb5f510f5b315f8bed8


* The multitouch patches add two-finger scroll support, but you lose secondary (right) click. You will be prompted when you run makepkg as to whether or not to use this.
