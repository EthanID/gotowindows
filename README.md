# gotowindows

gotowindows is a script that allows booting into a Windows EFI partition from the command line.

# Installation

`make install`

# Uninstallaion

`make uninstall`

# Usage

`gotowindows` places the first Window EFI entry as the first in the boot order *and* reboots the system. If one would like to only change the EFI entries than run `gotowindows -d`.
