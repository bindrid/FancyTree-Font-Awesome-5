"# FancyTree-Font-Awesome-5" 

When I first addressed the FancyTree Font Awesome 5 compatibility, I made the the stand alone ext.

After that point, wwwendt addressed Font-Awesome 5 for Web Fonts, however he did not address it for Font Awsome API/SVG/JavaScript.
Using the Javascript version will still break FancyTree.

For the second iteration, I addressed the issue directly in the jquery.fancytree.qlyph file listed here. All changes were restricted to the setIcon function.

In the process, I also added the ability to use callbacks to make the icon updates dynamic.
