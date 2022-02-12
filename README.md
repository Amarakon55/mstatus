# Mstatus
<img src="example.png">

Mstatus is a minimal status bar for DWM that comes preconfigured out of the box including these features:
* Colored unicode icons support
* Unicode icons change based on the status of the module
* Updates every millisecond (can be changed)
* Separated by separators

## Dependencies
### Mandatory
1. lm-sensors (CPU Temperature)
1. sysstat (CPU Speed)
1. acpi (Battery support)
### Optional
1. nerd-fonts-symbols (icon suport) (A patched font is recemmended. I use Inconsolata.)
1. [DWM status2d patch](https://dwm.suckless.org/patches/status2d/) (color support)

## (Un)Installation
### Universal
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Git clone the repository.
* `$ git clone https://github.com/Amarakon55/mstatus`
2. Change working directory to mstatus.
* `$ cd mstatus`
3. Install Mstatus using the Makefile
* `# make install`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Change working directory to mstatus.
* `$ cd mstatus`
2. Uninstall Mstatus using the Makefile
* `# make uninstall`

### Gentoo
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Add my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using [eselect-repository](https://packages.gentoo.org/packages/app-eselect/eselect-repository)
* `# eselect repository add amarlay git https://github.com/Amarakon55/amarlay`
2. Sync my personal [Gentoo overlay](https://github.com/Amarakon55/amarlay) using `emerge`
* `# emerge --sync amarlay`
3. Emerge the Mstatus package
* `# emerge app-misc/mstatus` or `# emerge mstatus`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Unmerge the Mstatus package
* `# emerge -c app-misc/mstatus` or `# emerge -c mstatus`
2. (Optional) Remove my overlay
* `# eselect-repository remove -f amarlay`
3. (Optional) Sync using `emerge`
* `# emerge --sync`
