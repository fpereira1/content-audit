Content Audit
-------------

A Python script that extracts meta tags (keywords, description, title) from a provided list of URLs and dumps the results into an Excel spreadsheet.

Requirements
------------
* BeautifulSoup

  Content Audit relies on Beautiful Soup v4 for parsing webpages. See more [here](http://www.crummy.com/software/BeautifulSoup/). You can also run:

  `easy_install beautifulsoup4`

* xlwt

  Content Audit relies on xlwt to write to an Excel spreadsheet without the need for COM Interop. See more [here](http://www.python-excel.org/). As with BeautifulSoup, you can use easy_install to install the library. Like so:

  `easy_install xlwt`

Big thanks to John Machin for the xlwt library and Leonard Richardson for BeautifulSoup.
