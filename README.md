# HaukaiRestaurant

1b) I introduced a W3 schools navigation bar to begin with but found that it didnt fit accesibility guidelines. It didnt work with tabbing so i changed to a bootstrap template which satisfied this criteria. 

I used light and dark text colouring to ensure that readability was clear and colours were clearly different to avaoid visibility issues. ARIA labels were used to identify areas with a screenreader. I tested with a screenreader to ensure readability.

I used H1 for main headings and H2 elements for sub headings. The P element was used for paragraphs and Ul used for unorganised lists. This was to aid the screenreader.

2c) Attempted to optimise pages with the suggested <meta http-equiv="Cache-control" content="public, max-age=3600, must-revalidate">. When validating this html with html5.validator i received error messaged so decided to leave this out to prevent issues with the html document.I optimised the images within each document as suggested to improve speeds.

2c) When undertaking Chrome DevTools there was no preset for a 2G network so i completed this testing in Firefox where there was a preset for this. This preset is attached in the compressed folder.

2d) HTTP caching can further improve responsiveness. It does this by creating a copy of a web page for a defined setg of time. This is usually defied within the html code. The means that the user doesnt have to download the web page each time and a copy of it is stored locally on their device. This reduces download speed time and improves the responsiveness of the web page. The browser would only request the page again if any changes have been made to the web page.

A content delivery network (CDN) works by placing cachesin different areas of the world. This is more important to international companies where they could have users accessing their web pages from around the world. Each cache contains a copy of the web pages. When customers access from different areas they can have the same download speeds and therefore improving responsiveness. The speeds with only one cache in different areas of the world could vary substantially based upon the distance the data has to travel. 

