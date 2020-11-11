# hubspot-proposals
The sample code here modifies the HubSpot Quotes (Simple) and adds an additional column for Product Images.

Requirements:
Create a custom property `images` in  `Products`.
Store the image URL in images. For example "https://f.hubspotusercontent20.net/hubfs/7248622/SE_Logo_RGB-01.png"

Clone the HubSpot default proposals theme:
1) Navigate to the Design Manager (Marketing > Design Manager > Files & Templates > *Design Tools*)
2) Navigate to the default Simple quote: @hubspot > cms-proposals-theme > templates > quote__simple.html
3) A prompt to clone the theme should pop up. Click "Clone theme" and name your folder.
4) Navigate to your cloned version of the theme > quote__simple.html
5) Replace the quote_simple.html with the code linked.

You can rename the quote template name on line 4 after `label`. Default = label: Quote (simple)
