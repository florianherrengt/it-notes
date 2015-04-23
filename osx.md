### Disable Pop-up Accent Window ###

    defaults write -g ApplePressAndHoldEnabled -bool false

### Show Hidden Files in Finder ###

    defaults write com.apple.finder AppleShowAllFiles TRUE

### Update OSX software ###

    sudo softwareupdate -l
    sudo softwareupdate -ia

### Prevent from sleeping ###

    caffeinate

### Create a testing file to upload ###

    mkfile <size> <name>
    mkfile 1g test.zip


### Turn off Dashboard ###

    defaults write com.apple.dashboard mcx-disabled -boolean TRUE
    killall Dock


### Search in commands history ###

    Ctrl + R

### Move to start/end of line ###

    Ctrl + A / Ctrl + E

### Clear terminal ###

    Cmd + K

### Switch between windows application ###

    Cmd + ~