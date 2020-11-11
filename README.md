# hubspot-proposals
The sample code here modifies the HubSpot `Quotes (Simple)` template and adds an additional column for Product Images.

Requirements:
Create a custom property `image` in  `Products`.
Store the image URL in images. For example "https://f.hubspotusercontent20.net/hubfs/7248622/SE_Logo_RGB-01.png"

Clone the HubSpot default proposals theme:
1) Navigate to the Design Manager (Marketing > Design Manager > Files & Templates > *Design Tools*)
2) Navigate to the default Simple quote: @hubspot > cms-proposals-theme > templates > quote__simple.html
3) A prompt to clone the theme should pop up. Click "Clone theme" and name your folder.
4) Navigate to your cloned version of the theme > quote__simple.html
5) Replace the quote_simple.html with the code linked.

Additional Notes:
> You can rename the quote template name on line 4 after `label`. The default label is `Quote (simple)`
> To pull a product image into Preview, modify mock_data.html and add your new custom property (image) in the lineItems JSON array. I added `"image": "https://f.hubspotusercontent20.net/hubfs/7248622/SE_Logo_RGB-01.png",` after line 66.
