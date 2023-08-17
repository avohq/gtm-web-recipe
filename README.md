# gtm-web-recipe

Avo Inspector integration recipe for web Google Tag Manager (GTM). It is hosted in the "Avo Inspector Recipe" container in our GTM account 
https://tagmanager.google.com/?authuser=1#/container/accounts/3136949393/containers/137425955/workspaces/11

# Contributing

After making changes to the tag files

1. Update the tag code in the "Avo Inspector Recipe" container in our GTM account
https://tagmanager.google.com/?authuser=1#/container/accounts/3136949393/containers/137425955/workspaces/11
2. Export the "Avo Inspector Recipe" container as a JSON file https://support.google.com/tagmanager/answer/6106997?hl=en
3. Update the JSON recipe file (e.g. `GTM-58RX3LLN_*.json`) on the branch with changes
4. Import the JSON file into the "Segment Destination" container
https://tagmanager.google.com/?authuser=1#/container/accounts/3136949393/containers/95381118/workspaces/35
5. Test that the tag is working using the preview function of the "Segment Destination" container
