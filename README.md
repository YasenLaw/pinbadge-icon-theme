# Pinbadge
Pinbadge is meant to be a circle icon pack with light gray glyphs.

# Installation
### Ubuntu
```bash
sudo add-apt-repository ppa:pinbadge/ppa
sudo add-apt-repository ppa:numix/ppa
sudo apt-get update
sudo apt-get install pinbadge-icon-theme
```

### Arch
Arch users can install this community maintained [AUR package](https://aur.archlinux.org/packages/pinbadge-icon-theme/).

### For other distributions (assuming `git` is installed)
```
git clone https://github.com/crutchcorn/pinbadge-icon-theme.git
cd pinbadge-icon-theme
sudo make install
```

# Guidelines
### General
* Icons must be named all lower case with any spaces being replaced by underscores (_)
* Canvas is 192px x 192px
* Whole circle is 182 px x 182 px
* Background has to be at lease 400 numbers away from each other. EG 500 --> 900
* Glyphs MUST have 1px shade 1px below the glyph
* Glyph MUST be gradient from Gray 50 --> Gray 300
* Glyph MUST have 1PX 100% tint
* You should use 6.25px spaces between other objects

### Linux
* Canvas is 48px x 48px
* Whole circle is 45.5px x 45.5px

# Special thanks
* [Philippe Loctaux] (https://github.com/loctauxphilippe) for setting up the Linux package, the PPA, and the AUR package
* [Material Open Source] (https://github.com/materialos) for letting me use their graphical assets
