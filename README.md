# bundesrat-beratungsvorgaenge

This is a Python-based webscraper for collecting data on all public sessions of the German Bundesrat (Federal Council). 

It scrapes [this website](http://www.bundesrat.de/DE/dokumente/beratungsvorgaenge/2016/beratungsvorgaenge-node.html) containing session information on public sessions of the German Bundesrat in 2016 (as well as the ones for [2015](http://www.bundesrat.de/DE/dokumente/beratungsvorgaenge/2015/beratungsvorgaenge-node.html) and [2014](http://www.bundesrat.de/DE/dokumente/beratungsvorgaenge/2014/beratungsvorgaenge-node.html)).

More specifically, it collects information on the unique identifier of the session ("Beratungsvorgang") and on the committee(s) involved in the decision-making. 

I first thought of using [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) for this project, but after doing some research and reading [this](http://stackoverflow.com/questions/17436014/selenium-versus-beautifulsoup-for-web-scraping) StackoverFlow post, I realized that [Selenium](http://selenium-python.readthedocs.io/getting-started.html) would be a more adequate solution for the dynamic content of the website. 
    
***
I've done this little project as a favor for a colleague and a small exercise for my webscraping skills. 

The data should be of interest to scholars of political science and public administration.
