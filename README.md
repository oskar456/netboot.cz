iPXE boot repository
====================

This repository contains files necessary to boot various
linux systems from the Internet.

To use this boot page, point your iPXE to this URL, i.e.:

    iPXE&gt; dhcp
    iPXE&gt; chain http://netboot.cz/index.ipxe

This URL can be also used as DHCP filename, for instance with QEMU:

    $ qemu … -net user,bootfile=http://netboot.cz/index.ipxe
