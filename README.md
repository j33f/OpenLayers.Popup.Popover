OpenLayers.Popup.Popover
========================

Twitter Boostrap Popover like Popup for OpenLayers

Licence
=======

BSD Like (see file)

Usage
=====

1. add the js file wherever you want
2. add / include Twitter's Bootstrap 2.x css (see below)
3. add this piece of CSS to your stylesheet <pre><code>.popover-title span {
	display:block;
	float: left;
	width: 236px; 
}</code></pre>
4. test and tweak both the CSS (width) and the dimension and delta properties in the js file
5. In your script, when you want to create a popup, use the follong code <pre><code>var popup = new OpenLayers.Popup.Popover(
		"popup",
		lonlat,
		"The popup content",
		"The popup title !",
		function(){
			/* this is the close popup callback function */
		}
);
</code></pre>
6. enjoy

Twitter's Bootstrap CSS
=======================
Include the latest version of [Twitter's Bootstrap 2.x](https://github.com/twitter/bootstrap) CSS in your project. Or add css/openlayerspopovers.css if you don't use Twitter's Bootstrap else where in your project.

Example
=======

In action, the popup looks like this :
![ ] (https://raw.github.com/Modulaweb/OpenLayers.Popup.Popover/master/example.png)
