# SimpleWebCrawler
This is Web Crawler Project
Parse the root web page ("XXXXXX.XXX"), and get all links from this page. To access each URL and parse HTML page, we will use JSoup which is a convenient web page parser written in Java.
Using the URLs that retrieved from step 1, and parse those URLs
When doing the above steps, we need to track which page has been processed before, so that each web page only get processed once.

Retrieve a web page from a website
Collect all the links on that document
Visit the next link

To run the application - > run CrawlerTest.java file which contains main method.

To Build the Application ->
mvn clean install command on Any IDE.

It will create the jar file in target folder location:  target\SimpleWebCrawlerApplication-0.0.1-SNAPSHOT.jar
