# SublimeSync

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