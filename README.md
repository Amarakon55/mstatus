# mstatus
<img src="example.png">

mstatus is a minimal status bar for DWM that comes preconfigured out of the box including these features:
* Colored unicode icons support
* Unicode icons change based on the status of the module
* Updates every millisecond (can be changed)
* Separated by separators

## Dependencies
### Mandatory
1. lm-sensors (CPU Temperature)
1. sysstat (CPU Speed)
### Optional
1. acpi (Battery support)
1. libXft-bgra-patch (Color support)
1. nerd-fonts-symbols (Unicode icon suport) (A patched font is recemmended. I use Inconsolata.)

## (Un)Installation
### Universal
#### Installation
##### Latest Git Master (Bleeding Edge)
1. Git clone the repository.
* `$ git clone https://github.com/Amarakon55/cfetch`
2. Change working directory to cfetch.
* `$ cd cfetch`
3. Install Cfetch using the Makefile
* `# make install clean`
#### Uninstallation
##### Latest Git Master (Bleeding Edge)
1. Change working directory to cfetch.
* `$ cd cfetch`
2. Uninstall Cfetch using the Makefile
* `# make uninstall clean`
