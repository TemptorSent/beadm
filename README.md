beadm
=====

Utility to manage Boot Environments on ZFS filesystems.

Originally written for FreeBSD as found in https://github.com/vermaden/beadm.
Port to Linux by TemptorSent with additional functionality included from port in https://github.com/b333z/beadm fork; code style of original followed.
Bind/unbind and chroot functionality have only been tested on Linux; Alternate BSD flavoring may be needed for them to function cross-platform.
This port should still function properly on BSD, but has not yet been tested.
Inactive BEs are set to 'canmount=noauto' without altering their mountpoints.
Mounting BE's to alternate root is accomplished by altering the moutpoint property as opposed to 'legacy' mount handling used by prior linux ports.

