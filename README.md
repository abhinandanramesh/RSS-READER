RSS-READER
==========

A simple personalized RSS reader implemented using XML parser and PHP.

Just add the website you want the feed from and there you go, your personalized RSS feed! 

This essentially conatins just the link and the names, but the code can be edited to add more UI features as desired.

A tip before editing:

Most of the RSS feed are not feed, it is a browser's rendition of the RSS feed in a more user friendly way.

So, do "wget <URL>" which saves an output file to the system i.e. the RSS file.

Look at the HTML structure and add more buttons as desired. I have implemented a minimal UI.

UI design is left to the user.

Adding AJAX implementation for a live feed as in a social media. Checkout ajax_rss.php file. (To be implemented at the server)
