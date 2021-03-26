# ALMA Presets for Manjaro

[ALMA](https://github.com/r-darwish/alma) presets for creating persistent USB Manjaro installs, based on [philmmanjaro/alma](https://github.com/philmmanjaro/alma/tree/master/presets).

WIP, don't use for important stuff.

## Usage

```sh
git clone https://github.com/Kornelijus/alma-presets-manjaro
cd alma-presets-manjaro
```

```sh
sudo ALMA_USER=<username> alma create --presets <xfce|kde|gnome>
```

Then select the drive you want to create a persistent installation in from the list. 

This will wipe everything currently on the drive!
