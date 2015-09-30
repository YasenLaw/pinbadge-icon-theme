# Pinbadge
Pinbadge is meant to be a circle icon pack with light gray glyphs.

# Installation
### For Ubuntu
```bash
sudo add-apt-repository ppa:pinbadge/ppa
sudo apt-get update
sudo install pinbadge-icon-theme
```

### For other distributions (assuming `git` is installed)
```
git clone https://github.com/crutchcorn/pinbadge-icon-theme.git
cd pinbadge-icon-theme
sudo make install
```

# Guidelines
### General
Circle is 182 px x 182 px
Background has to be at lease 400 numbers away from each other. EG 500 --> 900
Glyphs MUST have 1px shade 1px below the glyph
Glyph MUST be gradient from Gray 50 --> Gray 300
Glyph MUST have 1PX 100% tint
You should use 6.25px spaces between other objects

### Linux
Circle is 45.5px x 45.5px
