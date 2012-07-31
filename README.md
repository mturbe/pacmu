pacmu
=====

A simple mirrorlist updater for pacman (Arch Linux) written in Bash.

Inspired by <https://wiki.archlinux.org/index.php/Mirrors#Script_to_automate_use_of_Pacman_Mirrorlist_Generator>.

Usage
=====

**[-c COUNTRY]**

Fetch mirrors from specific country.

If option is omitted, all countries will be used.

**[-f]**

Fetch FTP mirrors.

**[-s]**

Fetch HTTP mirrors.

**[-4]**

Fetch ipv4 mirrors.

**[-6]**

Fetch ipv6 mirrors.

**[-m]**

Fetch mirrors based on mirror status.

**[-n MIRRORS]**

MIRRORS is the number of mirrors to be placed in the generated mirrorlist.

If option is omitted, or a number is not supplied, number of mirrors will default to 5.

**[-r]**

Replace /etc/pacman.d/mirrorlist with the generated mirrorlist.

Move /etc/pacman.d/mirrorlist to /etc/pacman.d/mirrorlist.old

**[-h]**

Display usage.



