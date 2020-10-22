A quick overview:

 1. Refactor UI5 namespaces and module names in yaml (optional)
 2. Fix destination name in xs-app.json
 4. Deploy app
 5. (If you are not using Workflow Management on your subaccount) Make sure that the workflow service permissions (WorkflowInitiator etc.) are assigned
 6. Create a destination using the app-router of this mta
 7. Integrate the tiles in "real" launchpad / portal using screenshots from the folder "screenshots" and using the destination from step 6.
 
Based on https://help.sap.com/viewer/e157c391253b4ecd93647bf232d18a83/Cloud/en-US/97c079f9317c42bba31cc9ca9d4cc7c3.html