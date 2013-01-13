ST2-user-settings
=================

personal SublimeText2 user configuration

##setting up##
1. Install [SublimeText2](http://www.sublimetext.com/dev)
2. Launch and register ST2, install [Sublime Package Control](http://wbond.net/sublime_packages/package_control/installation)
3. Close ST2
4. Navigate to your ST2 installation's package directory:
    * Windows: `pushd "%AppData%\Sublime Text 2\Packages"`
    * OSX:  `pushd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages`
    * Linux: `pushd ~/.Sublime Text 2/Packages`
    * Portable: `'path_of_ST2'/Data/Packages`
5. Delete (or rename) the already existing `User` directory
6. Clone this repo as the new User directory:
   `git clone https://github.com/davidjenni/ST2-user-settings.git User`
7. Launch ST2 again; there will likely be error messages about missing packages and themes
8. Let the Package Control do its thing; observe the status line at bottom of screen until it has finished downloading and updating packages.
9. Close and relaunch ST2 and get to work
