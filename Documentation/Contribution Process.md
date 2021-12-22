# Contribution Process

## Before starting new feature
### GitHub
#### Fetch Upstream
    Click 'Fetch upstream' -> 'Fetch and merge'
### On your computer
    Open terminal
    Navigate to ServiceNow -> Service-Practice
    Run command 'git pull'
### ServiceNow
    Open 'System Applications' -> 'Studio'
#### Apply Remote Changes   
    If 'Gemstar' is NOT current application
        From menu select 'File' -> 'Switch'
        Select 'Gemstar'
    From menu select 'Source Control' -> 'Apply Remote Changes'
#### Create Branch
    From menu select 'Source Control' -> 'Create Branch'
    Enter branch name
    Click 'Create Branch'
    This will make your new branch current
## During feature development
### ServiceNow
#### Commit Changes
    From menu select 'Source Control' -> 'Commit Changes'
    Select the chnages you want to commit
    Click 'Continue'
    Add 'Commit Comment'
    Click 'Commit Files'
### On your computer
    [Add process to include files not captured in Update Sets here]
## When feature is complete
### GitHub   
#### Create Pull Request
    Select branch [Name from 'Create Branch' step]
    Click 'Contribute' -> 'Open pull request'
    Add Title and Leave a comment describing changes
    Click 'Create pull request'
