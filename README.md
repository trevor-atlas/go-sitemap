# go-sitemap

## A very simple web crawler
Operations proceed as follows:

1. GET given webpage
2. parse all the links on the page
3. build proper urls with our links
4. filter out links from a different domain than the one given
5. find all the pages using Breadth First Search (BFS)
6. return xml sitemap as output
