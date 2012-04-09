_FDT icon (named 'fdt-icon.png') used with permission from Powerflasher GmbH_

See the following blog post for more details:
http://iqandreas.github.com/actionscript/actionscript-in-ubuntu/ubuntu-adding-fdt-to-the-list-of-applications/


### Instructions

* Make sure FDT is installed to `/opt/fdt5/` and that the file permissions are set properly.
* Save `fdt-icon.png` to the same folder as the FDT install directory, `/opt/fdt5/`.
* Save `fdt5` and `fdt5-clean` to `/usr/bin/` (may require admin rights)


If you want FDT to be available to _all users on the computer_, save `FDT5.desktop` (may hide the extension and show up as just plain `FDT5` if using Nautilus) to `/usr/share/applications/`.

If you want FDT to only be available to _the currently logged in user_, save `FDT5.desktop` (may hide the extension and show up as just plain `FDT5` if using Nautilus) to `~/.local/share/applications/`.

