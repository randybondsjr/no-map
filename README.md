#No Map Feature Layer Add Attributes
This script is an example of how to add to geocode an address, adding it's point to a feature layer with the appropriate attributes without loading a map to the dom. 

It uses jQuery and jQuery validate to validate the input before it is passed to the editable feature layer. 

This is not a dop in script, you'll have to edit it for it to work in your environment.

Edit the following lines with your own information:
> 1. **LINE 33** - esri.config.defaults.io.proxyUrl = "proxy.php"; ---change to your proxy
> 2. **LINE 35** - locator = new Locator("http://geocode.arcgis.com/arcgis/rest/services/World/GeocodeServer"); -- change to your geo location service
> 3. **LINE 115** - var featureLayer = new FeatureLayer("http://yourserver.com/yourfeaturelayer", { -- change to your feature layer
