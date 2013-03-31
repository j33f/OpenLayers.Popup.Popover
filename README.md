OpenLayers.Popup.Popover
========================

Twitter Boostrap Popover like Popup for OpenLayers

Licence
=======

BSD Like (see file)

Usage
=====

1. add the js file wherever you want
2. add this piece of CSS to your stylesheet <code>.popover-title span {
  		display:block;
			float: left;
			width: 236px; 
		}</code>
3. test and tweak both the CSS (width) and the dimension and delta properties in the js file
4. In your script, when you want to create a popup, use the follong code <code>	var popup = new OpenLayers.Popup.Popover(
		"popup",
		lonlat,
		"The popup content",
		"The popup title !",
		function(){
			/* this is the close popup callback function */
		}
	);
</code>
5. enjoy

Example
=======

In action, the popup looks like this : https://github.com/Modulaweb/OpenLayers.Popup.Popover/blob/master/example.png
