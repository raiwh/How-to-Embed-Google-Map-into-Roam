# How-to-Embed-Google-Map-into-Roam
This short document outlines how to embed a google map into Roam
Uses Google My Maps functionality.

Go to Google My Maps - need to have a Google Account. - https://www.google.com.au/mymaps

Create a new map and name it.

Zoom into the area you wish to embed, set the default view (scale) and add a layer. (the map must have layer in order to make the map public).  Your layer can be empty. Your map is automatically saved to your google drive.

To make your map public - Click the Share button and enable  link sharing and make public. 

To embed - Click on the three dot menu in your Map settings and choose “Embed on my site”. Copy the url ONLY.

Go to your Roam Page and use {{iframe: with the URL you just copied...

Your map should now be embedded.

This works (apparently) because you are using a public map in your Google Account.
Does not appear to work if Iframe is a child of a block.  Must be a top level indent.

I also suspect this will only work in Chrome and only if your browser is signed into Google (haven’t tested)

This is a hacky way of doing it - but it works

Check out various screen shots depicting various steps.

