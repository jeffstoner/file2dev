# file2dev
A Perl script that prints the device on which a file resides.

# Usage
file2dev file1 file2 file3 ... fileN

# Example
> $ file2dev /boot/vmlinuz-3.13.0-46-generic /usr/share/dict/words
> /boot/vmlinuz-3.13.0-46-generic	sdb1
> /usr/share/dict/words	sdb6
