# Mac

### brew does not link ###
After `brew install vim` the vim's version didn't change

    hash -d vim


### I changed my host file but the domain is not available ###

    dscacheutil -flushcache

### Stop using sudo with npm ###

    sudo chown -R $(whoami) ~/.npm
