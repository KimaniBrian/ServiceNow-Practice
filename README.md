# Gemstar

## GitHub
### Create fork
    Fork this repository
    From your forked repository select 'Clone or Download'
    Copy 'Clone with HTTPS' URL
### Create token
    Open User Settings
    Click 'Developer Settings'
    Click 'Personal access tokens'
    Click 'Generate new token'
    Add Note to identify this token
    Select 'public_repo'
    Click 'Generate token'
    Make sure to copy your new personal access token now. You won’t be able to see it again!
## On your computer
   Open termial
   Make directory 'ServiveNow'
   Change to directory ServiceNow
   Run command 'git clone [URL from 'Create fork' step]'
## ServiceNow
    Login into developer instance
### Import XML Files
    Open 'System Update Sets' -> 'Retrieve Update Sets'
    Click 'Import Update Set from XML'
    Click 'Choose File' and navigate to ServiceNow -> Service-Practice -> Gemstar Groups directory
    Select file
    Upload file
    Repeat steps above for each file
### Create Credentials
    Open 'Connections & Credentials' -> 'Credentials'
    Click 'New'
    Select 'Basic Auth Credentials'
    Add 'Name'
    Add 'User name' [Note from 'Create token' step)
    Add 'Password' [Token from 'Create token' step]
    Click 'Submit'
### Create Credentials
    Open 'System Applications' -> 'Studio'
    On Studio Tab click 'Import From Source Control'
    Network protocol: 'https'
    URL: [URL from 'Create fork' step]
    Credential: [Name from 'Create Credentials' step]
    Branch: main
    Click 'Import'
    Click 'Select Application'
    Open 'Gemstar'
