# Web-scraping for Social Science Research

## Frequently Asked Questions

The following is a sample of questions that have been posed during the *Web-scraping for Social Science Research* webinar series.

### Q. Is web-scraping legal?
In the United Kingdom (UK) there is no specific law prohibiting the capture or use of data from websites. However, many websites have Terms of Service/Use that must be abided when you use them. The information stored on websites can also be subject to copyright or data laws.

### Q. Can I collect qualitative data using web-scraping?
Yes, in fact most of the information contained on websites is stored as text. It is relatively simple to capture this information using web-scraping techniques, and save the results to a file. 

### Q. Is there a code of ethics for web-scraping?
There isn't one we have come across. However, from an academic perspective web-scraping is a research method and thus part of a wider research design. Therefore research involving this method needs to receive ethical approval from your institution. This will typically involve demonstrating approaches, solutions and mitigations in terms of participant consent, harm to researcher and participant, data security and protection etc.

In terms of good practice specific to web-scraping:
* Unless explicitly stated in the Terms of Service/Use, always seek permission to scrape data from a website.
* Think very clearly about how you will process, store and share data, especially those relating to individuals.
* Do not make unneccessary requests to a website. Web-scraping can overload a website and cause it to crash.

### Q. Can I conduct web-scraping in R / Stata / other packages?
Yes. We have chosen Python as we think it is particularly good and easy to learn for this task. However many other programming languages and software applications have web-scraping modules. While the exact commands will differ, the underpinning logic remains the same.

### Q. What kinds of data can you scrape from websites?
While websites tend to mainly contain text (e.g., paragraphs or tables of interest), it is possible to scrape other types of data such as files, images etc. This is possible because these types of data tend to be stored as links on a web page; therefore you scrape these links and then request them using Python's `requests` module. However, there may be issues with permissions around the collection and use of certain images, files, videos etc.

### Q. Can you scrape data from social media sites?
In theory yes, but social media platforms (and many other organisations producing large amounts of data) prefer you to access their data via an Application Programming Interface (API) that connects to their online database. There are still restrictions around the nature, volume and use of data that you can access but these tend to be well documented.
