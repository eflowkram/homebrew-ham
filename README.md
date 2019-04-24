# homebrew-ham

### [Homebrew](https://brew.sh/) formulae for ham radio software.

If you don't have Homebrew installed, make sure to [visit their website](https://brew.sh) to install it first. It's a free trusted open source package manager for macOS that makes finding, installing, and updating software packages (such as CHIRP) incredibly easy. It can be installed with a single command.

I just cloned tdsmith repo so I could run more up to date software, mainly chirp as I have recently purchased some Yaesu RDA1846 chipsets.


---

## CHIRP

### Programs amateur radios

[Homepage](http://chirp.danplanet.com/projects/chirp/wiki/Home)

To install CHIRP via the command line:
* `brew install tdsmith/ham/chirp`

To run CHRIP via the command line:
* `chirp`

To uninstall CHIRP via the command line:
* `brew uninstall chirp`

---

To update everything from Homebrew via the command line, run these three commands:
* `brew update` (checks for new versions)
* `brew upgrade` (downloads and installs new versions)
* `brew cleanup` (deletes old versions once the new ones are installed)

If you've uninstalled everything from tdsmith/ham, you can remove the tap via the command line:
* `brew untap eflowkram/ham`
