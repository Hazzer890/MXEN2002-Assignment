# DFM2021

# Getting Started
* Install TeXLive: https://www.tug.org/texlive/acquire-netinstall.html (install-tl-windows.exe). You won't need the GUI (untick Frontend on the installer)
* Make sure you also have git installed on your computer (https://git-scm.com/download/win)
* Install VSCode.
* Install the "LaTeX Workshop" Extension (https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
* Clone this repository:
* In VSCode: CTRL + SHIFT + P > Git: Clone > https://github.com/SamGoh99/DFM2021.git
* Checkout your branch! In the botton left corner, there's a branch selector. Choose the branch with your name
* The first time, this will be `origin/yourname`. Subsequent times, it'll just be `yourname`

# Editing 
* Open the assign.tex file
* Goto the TeX extension tab > Build LaTeX project
* Open the assign.pdf file
* Edit away. As you make changes, LaTeX will rebuild the .pdf file

# Making changes
* Sync your branch (bottom left corner, sync button)
* Make your changes, commit
* Sync your branch (bottom left corner, sync button)

# Merging your changes
* Sync your branch
* In GitHub, goto Pull Requests -> Create. Make sure you're merging FROM your_name TO master

# Getting changes from master to your branch
* Make sure all your changes are committed on your branch and sync
* Open the VSCode Terminal (CTRL + SHIFT + ~)
* Run `git fetch origin`
* Run` git merge origin/main`
* Sync
