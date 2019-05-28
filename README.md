# SublimeSync

## Sublime text2's Key
```
ZYNGA INC.
50 User License
EA7E-811825
927BA117 84C9300F 4A0CCBC4 34A56B44
985E4562 59F2B63B CCCFF92F 0E646B83
0FD6487D 1507AE29 9CC4F9F5 0A6F32E3
0343D868 C18E2CD5 27641A71 25475648
309705B3 E468DDC4 1B766A18 7952D28C
E627DDBA 960A2153 69A2D98A C87C0607
45DC6049 8C04EC29 D18DFA40 442C680B

1342224D 44D90641 33A3B9F2 46AADB8F！
```

Backup & Restore SublimeText's plugins

## Install PackageControl

[Package Control](https://packagecontrol.io/):The simplest method of installation is through the Sublime Text console. The console is accessed via the **ctrl*+*`** shortcut or the **View *>* Show Console** menu. Once open, paste the appropriate Python code for your version of Sublime Text into the console.

```bash
import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```

## Install PackageSync

[PackageSync](https://packagecontrol.io/packages/PackageSync):Sync sublime text packages & user settings across devices.

The preferred method of installation is via [Sublime Package Control](https://packagecontrol.io/).

1.  [Install Sublime Package Control](https://packagecontrol.io/installation)
2.  From inside Sublime Text, open Package Control's Command Pallet: CTRL SHIFT P (Windows, Linux) or CMD SHIFT P (Mac).
3.  Type `install package`, select command `Package Control: Install Package` and hit Return. A list of available packages will be displayed.
4.  Type `PackageSync`, select the `PackageSync` package and hit Return. The package will be downloaded to the appropriate directory.

## Clone SublimeSync

[SublimeSync](https://github.com/GregGe/SublimeSync):backup the sublime plugins

```bash
git clone https://github.com/GregGe/SublimeSync
```

## Backup / Restore 

Tools -> PackageSync -> Backup / Restore -> Backup Installed Packages List Only

Tools -> PackageSync -> Backup / Restore -> Restore Installed Packages List Only
