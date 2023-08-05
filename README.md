# gtm-web-recipe

This is a repo for our inspector integration recipe for web GTM. It is hosted in the "Avo Inspector Recipe" container in our GTM account 
https://tagmanager.google.com/?authuser=1#/container/accounts/3136949393/containers/137425955/workspaces/11

And enabled in our "Segment Destination" container to run on Avo.app
https://tagmanager.google.com/?authuser=1#/container/accounts/3136949393/containers/95381118/workspaces/35

# Contributing

After making changes to the tag files

1. update the tag code in the "Avo Inspector Recipe" container in our GTM account
https://tagmanager.google.com/?authuser=1#/container/accounts/3136949393/containers/137425955/workspaces/11
2. export the "Avo Inspector Recipe" container as a json file https://support.google.com/tagmanager/answer/6106997?hl=en
3. update the json recipe file (e.g. `GTM-58RX3LLN_*.json`) on the branch with changes
4. import the json file into the "Segment Destination" container
https://tagmanager.google.com/?authuser=1#/container/accounts/3136949393/containers/95381118/workspaces/35
5. test that the tag is working using the preview function of the "Segment Destination" container
