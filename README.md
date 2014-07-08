steps-dropbox-deploy
====================

Concrete Step to Deploy an xcode archive to Dropbox. You need to register on Dropbox's website https://www.dropbox.com and create an app to utilize this step. You also have to create an access token for your app.

This Step depends on steps-xcode-builder's Archive step

# Input Environment Variables


# Output Environment Variables
- HOCKEYAPP_DEPLOY_STATUS	[success/failed]
- HOCKEYAPP_DEPLOY_PUBLIC_URL