### Rebase ###

    git rebase -i HEAD~5
    git rebase -i master

### Reset from remote ###

    git reset --hard origin/master

### Get number of line ###

    git ls-files | xargs wc -l
