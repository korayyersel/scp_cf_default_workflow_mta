A quick overview:

 1. Refactor UI5 namespaces and module names in yaml (optional)
 2. Fix destination name in xs-app.json
 3. (If you are not using Workflow Management on your subaccount) Make sure that the workflow service permissions (WorkflowInitiator etc.) are assigned

How to integrate the workflow tiles in portal:

 1. Create a destination using the app-router URL of this mta. (Proxy Type: Internet, Authentication: NoAuthentication)
 2. Integrate the tiles in "real" launchpad / portal using screenshots from the folder "screenshots" and using the destination from step above.

Based on https://help.sap.com/viewer/e157c391253b4ecd93647bf232d18a83/Cloud/en-US/97c079f9317c42bba31cc9ca9d4cc7c3.html