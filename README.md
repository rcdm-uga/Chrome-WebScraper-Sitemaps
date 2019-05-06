# Web Scrapper

This is a repository made to store sitemaps for the Chrome Browser that makes webscrapping easier, especially for data thats hidden with javascript on web pages. The plugin takes a string of values called a sitemap which tells the plugin what data to grab and where and how to format it. These will be sitemaps so all you have to do is feed in the sitemap and pull the data  you want from that site. 

The perfered structure of this repositry, if one wishes to add, will be to store the sitemap in its own directory with a simple README with how the data will look once pulled from the web.

### Installation
You will need to have [Chrome](https://www.google.com/chrome/?brand=CHBD&gclid=Cj0KCQiAheXiBRD-ARIsAODSpWOzmLkpF-4dXwZN7xKLbjCymg2NFrwTPbMZSUchNROTjo-ISWqgzYQaAuS-EALw_wcB&gclsrc=aw.ds) downloaded before you can install this plugin.
Once you have the correct browser up and running, you can download the [Web Scraper](https://chrome.google.com/webstore/detail/web-scraper/jnhgnonknehpejjnehehllkliplmbmhn?hl=en) plugin.

### How to use 
The filename will have the website that the sitemap is created for. 

If you right click anywhere on the page (doesn’t have to be the one you want to scrape) and click on “Inspect (Element)”. There should be a tab at the top of the inspector that is called WebScraper. This is the plug in! Next click on Create new sitemap > Import Sitemap, then you can paste the sitemap, or any other sitemap that has already been created here. So after you paste the sitemap into the webscraper, change what is inside “startUrl”:[“PUT URL IN HERE BETWEEN QUOTATION MARKS”].

So for the GoodReads sitemap, you will have to use the URL of the book youre trying to grab the comments from. That one will not work for any other site. Don’t change anything else to the sitemap besides the URL itself. Once this is imported, you can click on Sitemaps [name of sitemap] at the top of the inspector, and click Scrape. You will be asked to put request intervals, 2000 is plenty of time for both request and page load. This is just to show the browser that you are a human and not a robot.

Let the plugin do it’s thing, and you might have to click on the refresh data button once it is done. Then you can export the table as a csv and now you have your data!

### Lets get to webscrapping!!!
