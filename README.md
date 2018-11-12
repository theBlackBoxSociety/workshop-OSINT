Syllabus for workshop taught at Media Art, KASK during projectweek1 Autumn 2018

# workshop OSINT
 
    11-13 November 2018, Media Arts studio
    
## Description
During this project week we institute the _Black Box Society_. BBS is a codelab with teachers and (former) students Media art with whom we want to write and share code that can be applied within art and design projects. All the BBS code and ideas will be published on the [BBS github page](https://github.com/theBlackBoxSociety) and are open source.

The overarching themes of this project week are [OSINT](https://en.wikipedia.org/wiki/Open-source_intelligence) (open source intelligence) and webscraping. With different scripts and tools, it is possible to explore and investigate the web and its data in a different way. OSINT data is collected from publicly available sources. In the intelligence community, the term &#39;open&#39; refers to publicly available public sources (as opposed to secret or clandestine sources). With OSINT and webscraping it becomes possible to pick data that you can&#39;t immediately find with a google search. An example is that you can download all Instagram pictures or tweets from a certain user.

The obtained data is then used as input for a [speed project](http://fffff.at/speed-project/). We will provide various resources to translate the data into, for example, coordinates to work with the drawing machine, use them to create online apps, or to visualize them with [TouchDesigner](https://www.derivative.ca/).

## Planning

- DAY 1: initiation [TouchDesigner](https://www.derivative.ca/) (by Maarten Serpentier) (see the separate call &#39;TD.pdf&#39;)
- DAY 2: initiation OSINT with [Buscador](https://inteltechniques.com/buscador/) and with available scripts on the BBS github.
- DAY 3: Working out speed projects with the gathered information by Buscador and scripts. Data visualization through [AxiDraw](https://axidraw.com/) drawing machines, online applications and/or TouchDesigner.

## Syllabus

### TOUCHDESIGNER


### WEBSCRAPING
Web scraping is the collection of data via means other than a program that interacts with an API (or, via a human who uses a web browser). This is usually achieved by writing an automated program that retrieves data from a web server, collects this data (usually in the form of HTML and other files that compile web pages), and then &quot;parses&quot; that data to extract the necessary information from it.
In practice, web scraping includes a wide range of programming techniques and technologies, such as data analysis, natural language analysis and information security.
If you only have internet access via a browser, you miss out on a huge number of possibilities. Although browsers are useful for running JavaScript, displaying images and arranging objects in a more human-readable format (among other things) web scrapers are excellent for (fast) collecting and processing large amounts of data. Instead of viewing one page at a time through the narrow window of your monitor and browser, you can view databases that span thousands or even millions of pages in one session.
In addition, web scrapers can go to places that traditional search engines can not or do not want. A Google search for a specific topic will result in a lot of advertisements and popular hits on that topic. Google only shows what these websites say about their content pages and not the exact results that may be hidden deeper in the Net.


### OSINT

We use the Buscador distribution system to collect OSINT info. With OSINT or &quot;Open-Source Intelligence&quot; data is collected from publicly available sources. In the intelligence community, the term &#39;open&#39; refers to publicly available public sources (as opposed to secret or clandestine sources). With OSINT it is possible to pick data that you can not immediately find with a google search. An example is that you can download all Instagram photos or tweets from a certain user.


### BUSCADOR TOOLS discussed during the project week, from the menu:

1. **instalooter** , instagram scraping, works with some. Not with Zuckerberg&#39;s @zuck. Wonder why. Site: [http://instalooter.com/](http://instalooter.com/)
2. **Twitter Options** , twitter scraper, same here, no zuck
3. **EyeWitness** , grab screenshot plus site info.
4. **Pro Google Earth** , search for people and things on a global scale


### INSIDE CHROME INCOGNITO (still Buscador), icons on the right top corner...
0. **uBlock Origin** , what it says basically, can also be installed as Chrome plugin here: [https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)
1. **Prophet** , surf to social media sites and retrieve extra info about the subject, plugin: [https://chrome.google.com/webstore/detail/prophet/alikckkmddkoooodkchoheabgakpopmg](https://chrome.google.com/webstore/detail/prophet/alikckkmddkoooodkchoheabgakpopmg)
2. **Shodan** , get server and host details of visited site, also, shodan site: [shodan.io](https://www.shodan.io/), a search engine for IOT, refrigerators and toasters.
3. **ipinfo.io** , what it says, the site is here: [ipinfo.io](https://ipinfo.io/)


### WEBSCRAPING TOOLS/EXAMPLES BBS GITHUB
[https://github.com/theBlackBoxSociety](https://github.com/theBlackBoxSociety)

1. **UFOsighting** , data retrieved from over here [https://github.com/theBlackBoxSociety/awesome-public-datasets](https://github.com/theBlackBoxSociety/awesome-public-datasets) and then converted into json with this online tool: [http://beautifytools.com/html-to-json-converter.php](http://beautifytools.com/html-to-json-converter.php) p5.js is used, a JavaScript-like scripting language similar to Processing.

2. **GuardianAPI** , p5.js script to access Guardian headlines and create links to it.

3. **goggleImgScraper** , Python script/library to scrape Google for images

4. **pattern** , a web mining module for Python, with tools for scraping, natural language processing, machine learning, network analysis and visualization.


### DATAVISUALISATION
Some examples from the Generative Gestaltung book &amp; website
[http://www.generative-gestaltung.de/](http://www.generative-gestaltung.de/)

With PROCESSING

Code package [https://github.com/generative-design/Code-Package-Processing-3.x](https://github.com/generative-design/Code-Package-Processing-3.x)

+ library [https://github.com/generative-design/GenerativeDesignLibrary3](https://github.com/generative-design/GenerativeDesignLibrary3)

Or P5JS

Code package [https://github.com/generative-design/Code-Package-p5.js](https://github.com/generative-design/Code-Package-p5.js)

+ library https://github.com/generative-design/generative-design-library.js

Some helpful examples are _(P = basic principles M = complex methods)_

P.3.1.3 Text Image

Analyze a text file and visualize the number of times a character is used.

P.3.1.4 Text Diagram

Analyze a text file and visualize the number of times a word is used.

P.4.2.1 Collage from image collection

        This sketch assembles a collage from a folder of images after cropping, cutting and sorting.

M.5. Tree Diagrams

        Tree diagrams are graphic representations of hierarchically structured data.

M.6 Dynamic data structures

Read, analyze and visualize data from the internet (using the XML dataformat). Examples with the Wikipedia api.



### TECHNICAL

Please make sure you have all of these platforms up and running on your device before attending the project week. If you fail to do so anyway, no worries we'll help you along...

- [Virtualbox + VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads)

- Installing Buscador: [https://inteltechniques.com/buscador/](https://inteltechniques.com/buscador/)
note: after installing Buscador in a virtual machine: if keyboard is in qwerty, open up terminal inside Buscador and type: setxkbmap fr

- Installing Python 2 [Python 2.7.15](https://www.python.org/downloads/release/python-2715/)

- Installing Python 3 (latest version): [https://www.python.org/downloads/](https://www.python.org/downloads/)

You will need IDLE for version 2 and 3 (Python's Integrated Development and Learning Environment). When you open up the BBS python scripts there will probably be other dependencies that need to be installed. These will show up in the IDLE window (in red), telling you which ones are necessary for the software to run successfully.

- p5.js: [https://p5js.org/download/](https://p5js.org/download/) for these scripts it might be good to install a good code editor such as Atom: [https://atom.io/](https://atom.io/)To open the html files (containing the javascript files) use Firefox. In Chrome, you first need to fire up a local server, in terminal use this command line: python -m SimpleHTTPServer then surf to localhost:8000 in your Chrome.


## Essential Reading & Links to interesting people & projects
See [this](https://github.com/theBlackBoxSociety/EssentialReading) & [this](https://github.com/theBlackBoxSociety/interestingPeople) gists
