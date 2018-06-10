# Appartement Search

This project was a little side idea I had while looking for new appartements. It is very time consuming to flip through pages and pages of appartement offers on different portals so I was wondering if there is a better way to get a quick overview. Currently the data gets crawled from [immobilienscout42](https://www.immobilienscout24.de/) and [wg-gesucht](https://www.wg-gesucht.de/) which are two big German platforms to find an appartement. 

![Data](https://github.com/vkakerbeck/AppartementSearch/blob/master/examples/CrawledData.png)

The first step is to visualize some statistics over the city you are looking at appartements for. 

![PriceSizeScatter](https://github.com/vkakerbeck/AppartementSearch/blob/master/examples/PriceSizeScatter.png)

For example I plot the average prices-size relation for the different areas of my city (Osnabrück) as a scatterplot or a histogram of all price-size relations to get a general idea of what is a good price in my area. 

![PriceSizeBox](https://github.com/vkakerbeck/AppartementSearch/blob/master/examples/PriceInAreas.png)

Then the appartements get visualized on an interactive map. Each appartement is a circle whose size represents the size of the appartment and the color represents the prize-size relation ship. A red dot therefore represents an appartement which is expensive for its size while a green dot represents an appartement with a good price. When clicking on a circle you can see the exact price and size and find a link to the original page to find more detailed information as well as pictures of the place.

![MapView](https://github.com/vkakerbeck/AppartementSearch/blob/master/examples/mapView.png)
