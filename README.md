#Markdown Sitemap

A markdown-based visual sitemapping tool.

This project is based on [Slickmap](https://www.astuteo.com/slickmap) CSS styles to render the sitemap.



###How To Use

1. Create an HTML file with an unordered list of links. SlickMap was
designed to style actual linked navigation, not simply lists, so make
sure to include anchor tags. See index.html for the correct formatting.

2. Apply slickmap.css as you would any other stylesheet, using it for both
"screen" and "print" media as seen here:

`<link rel="stylesheet" type="text/css" media="screen,print" href="slickmap.css" />`

3. Within your HTML file, the link to your home page should be at the top
of the unordered list and have the id of #home. This is required to pull
the home page link out above the rest of the site tree.

4. The SlickMap default is 4 columns. In order to change the number of
columns, you simply need to change the class of the PrimaryNav unordered
list (col4, col5, etc.) SlickMap CSS will accomodate 1 to 10 columns,
some much better than others.

5. Depending on how you use these files, you may need to correct the image
paths within the CSS file.


##Credits
[Slickmap](https://www.astuteo.com/slickmap): created by Matt Everson of Astuteo  
