# Dotfiles
**Currently a Work-In-Progress until I get symlinks and an installation script working.**
Some things to remember and keep when getting dev environments up and running.

#### Terminal formatting
- Color Profile: HomeBrew
- Text Color: White
- Text Size: 14 pt

## Atom Installation
1) Install Atom
2) Install packages below (atom doesn't have a config file for installed packages)
3) Copy over config files from the `.atom` directory here
#### Atom Packages
- nuclide
- docblockr
- file-icons
- minimap
- minimap-git-diff
- pigments
- project-manager
#### Atom Themes
**UI Theme**
Atom Dark
**Syntax Theme**
Base16 Tomorrow Dark
**Misc. Styling**
See my `styles.less` file in the `.atom` directory
#### TODO
Sync installed packages via "starred" repos.
https://discuss.atom.io/t/bower-style-package-json-to-import-install-packages-across-devices/11587/2

## Windows
#### Node
NPM's node-gyp requires Microsoft Visual Studio.
- Install Visual Studio Community 2015
 - Include the C++ package in a "custom" install
- Run `npm install -g -msvs_version=2015 node-gyp rebuild`
