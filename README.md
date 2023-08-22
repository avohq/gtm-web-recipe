# gtm-web-recipe

# Quick start guide

To use the recipe, download the `GTM-58RX3LLN_*.json` file and import it into your container https://support.google.com/tagmanager/answer/6106997?hl=en.

When importing, choose `Merge` and `Overwrite conflicting tags, triggers, and variables`. Check that you have not accidentally owerriten any existing properties or functions. It is unlikely though, since we use Avo specific names in the recipe.

# Contributing

Avo Inspector integration recipe for web Google Tag Manager (GTM). It is hosted in the "Avo Inspector Recipe" container in our 
internal GTM account and is enabled in our internal "Segment Destination" container to run on Avo.app.

## After making changes to the tag files Avo GTM admin should do the following

1. Update the tag code in the internal "Avo Inspector Recipe" container in our GTM account
2. Export the "Avo Inspector Recipe" container as a JSON file https://support.google.com/tagmanager/answer/6106997?hl=en
3. Update the JSON recipe file (e.g. `GTM-58RX3LLN_*.json`) on the branch with changes
4. Import the JSON file into the "Segment Destination" container
5. Test that the tag is working using the preview function of the "Segment Destination" container
