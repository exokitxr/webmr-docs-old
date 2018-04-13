# Windows Startup
   * For Windows:

      * [Install Node.js v10](https://nodejs.org/download/nightly/v10.0.0-nightly2018040808a36a0666/), find your OS, download from there.

      * Download Git: https://git-scm.com/download/win

      * Head [here](https://desktop.github.com/), download github desktop and sign in/open it.

      * Go to the top left of Github Desktop and hit `File`, `Clone Repositor`, then type `webmixedreality/exokit` in the top bar, and go with the default path for download. (should be C:\users\NAME\foldername, here's [a picture](https://imgur.com/a/oC8F9) for reference on the download)

      * Ctrl-Shift-F to open the directory to see the files and be sure they are there.

      * Open `node.js command prompt` from start menu BE SURE ITS IN ADMIN MODE, type `npm i -g windows-build-tools` into the window.

      * Open `node.js command prompt again` and copy in `set PYTHON=C:\Users\YOURNAME\.windows-build-tools\python27\python.exe` be sure to replace YOURNAME with your username for the path, then punch in `git`, some stuff should happen no worries.

       * Now that that's done, in the command prompt, type `cd (YOURPATHNAME)\exokit`.

       * Be sure you do the cd path name\exokit thing again, then type `git submodule init` and `git submodule update`, then type `npm install` after that first bit is done, it should install.

