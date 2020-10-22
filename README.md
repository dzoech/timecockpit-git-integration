# timecockpit-git-integration
Integrates git commits into the time tracking software 'time cockpit'.

This is achieved by 
- utilizing time cockpit's [file signal tracker](https://help.timecockpit.com/doc/signal-tracker/import-signals.html)
- global git hooks

## Installation
git clone https://github.com/dzoech/timecockpit-git-integration.git
cd ./timecockpit-git-integration
git config --global core.hooksPath $pwd/git-hooks