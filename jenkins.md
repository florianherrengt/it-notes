### Add login ###
- Go to Manage Jenkins
- Configure Global Security
    - Jenkins’ own user database + Allow users to sign up
- Go back to Manage Jenkins
- Manage Users
- Add a user
- Go back to Configure Global Security¬
    - Matrix-based security
    - User/group to add (your user)
    - Administer

### Add GitHub hook ###
- Manage Jenkins
    - Manage Plugins
        - Install GitHub Plugin
    - Configure
        - Give git informations
        - GitHub Web Hook
            - Let Jenkins auto-manage hook URLs
                - GitHub Credentials: Empty
-               - Token: https://help.github.com/articles/creating-an-access-token-for-command-line-use/
- Open a task
    - Configure
    - Set GitHub url in GitHub project
    - Source Code Management
        - Git
        - Repositories > Same URL
    - Build Triggers
        - Build when a change is pushed to GitHub
