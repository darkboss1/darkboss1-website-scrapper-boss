darkboss1-website-scrapper-boss
<h2> Installation Steps:</h2><br>

```
git clone https://github.com/darkboss1/darkboss1-website-scrapper-boss.git
```
```
cd Uscrapper/install/ 
chmod +x ./install.sh && ./install.sh      #For Unix/Linux systems
```

<br><h2> Usage:</h2>

<p>To run darkboss1-website-scrapper-boss, use the following command-line syntax:</p>

```
python darkboss1-website-scrapper-boss.py [-h] [-u URL] [-O] [-ns] [-c CRAWL] [-t THREADS] [-k KEYWORDS [KEYWORDS ...]] [-f FILE]
```
<br><b>Arguments:</b>

*  -u URL, --url URL     (URL of the website)
*  -O, --generate-report (Generate a report)
*  -ns, --nonstrict      (Display non-strict usernames (may show inaccurate results))
*  -c CRAWL, --crawl     (CRAWL) specify max number of links to Crawl and scrape within the same scope
*  -t THREADS, --threads THREADS (Number of threads to utilize while crawling (default=4))
*  -k KEYWORDS [KEYWORDS ...], --keywords KEYWORDS [KEYWORDS ...]    (Keywords to search for (as space-separated arguments)
*  -f FILE, --file FILE  (Path to a text file containing keywords)

<br><h2> Note:</h2>
* darkboss1-website-scrapper-boss relies on web scraping techniques to extract information from websites. Make sure to use it responsibly and in compliance with the website's terms of service and applicable laws.

* The accuracy and completeness of the extracted details depend on the structure and content of the website being analyzed.

* To bypass some Anti-Webscrapping methods we have used selenium which can make the overall process slower.

<br><h2> Contribution:</h2><br>
<b>Want a new feature to be added?</b><br>
* Make a pull request with all the necessary details and it will be merged after a review.
* You can contribute by making the regular expressions more efficient and accurate, or by suggesting some more features that can be added.

<h2> License:</h2><br>
This project is licensed under the <a href="https://github.com/darkboss1">MIT-LICENSE</a><br><br>
