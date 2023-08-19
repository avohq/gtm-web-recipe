# gtm-web-recipe

# Quick start guide

To use the recipe, download the `GTM-58RX3LLN_*.json` file and import it into your container https://support.google.com/tagmanager/answer/6106997?hl=en.

When importing, choose `Merge` and `Overwrite conflicting tags, triggers, and variables`. Check that you have not accidentally owerriten any existing properties or functions. It is unlikely though, since we use Avo specific names in the recipe.

# Contributing

Avo Inspector integration recipe for web Google Tag Manager (GTM). It is hosted in the "Avo Inspector Recipe" container in our 
internal GTM account 

And is enabled in our internal "Segment Destination" container to run on Avo.app

## After making changes to the tag files

1. update the tag code in the "Avo Inspector Recipe" container in our GTM account
2. export the "Avo Inspector Recipe" container as a json file https://support.google.com/tagmanager/answer/6106997?hl=en
3. update the json recipe file (e.g. `GTM-58RX3LLN_*.json`) on the branch with changes
4. import the json file into the "Segment Destination" container
5. test that the tag is working using the preview function of the "Segment Destination" container
