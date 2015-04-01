SASS Build Script for Sublime Text 3
====================================

Author
------

Created by **Hendrik Schuster** ([@journal.deviantdev.com](http://www.journal.deviantdev.com)).
Corresponding [journal entry](http://www.journal.deviantdev.com/sublime-text-build-system-sass)

License: [BSD 2 Licence](http://opensource.org/licenses/BSD-2-Clause)

Description and Usage
-----------

Provides a working build script for SASS and SCSS files. This Build script will generate a uncompressed refernece file and a minified working file with a sourcemap. It is recommended to remove the sourcemap link and file for deployment, because it is not needed and a extra file to load.

After installing you will find a new option in `Tools > Build system`: **SASS - Build**. This build script will be used as default for your `.scss` and `.sass` files.

To change the default folder of your generated CSS you can edit the build like follow (saving your CSS files into a `css` folder:):
`[...], "$file:${file_path}/../css/${file_base_name}.css"], [...]`

Requirements
-------------

Requires **Ruby** and **SASS** installed as command line tools.

1. Install Ruby library

	**OS X and Linux**: It's already installed. Easy! :)

	**Windows**: Download Ruby. Install Ruby using the option *Add Ruby executables to your PATH*. Reboot after install it.

2. Installing SASS

	Open your console and execute `gem install sass` as command


Installing
-------------

Download the latzest zip or clone the project from the [Github](https://github.com/DeviantDev-Dev/xxx) repository. Move the files into a new folder named like `SASS-Build` in your Sublime Text "Packages" folder.

Thanksgivings
----------------

Thanks to the former work of **Jaume Fontal** ([Github](https://github.com/jaumefontal/SASS-Build-SublimeText2)).

