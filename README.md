-------------------------------------------------------------------------------------------------------------------------------------------------------------------
# Web scraping with Python using BeautifulSoup4
-------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Web scraping:**
- process of **extracting and parsing data from websites** in an automated fashion
- **use Python and its libraries** to download / get:
	- images
	- information
- **rules:**
	- always try to **get permission** before scraping
	- **too many scraping attempts** or requests, the **IP address** could **get blocked**
	- some websites **automatically block scraping software**
- **limitations:**   
	- every **Web scraping script is unique**
	- slight **change / update to a website breaks Web scraping script**
- main **Front-end components of a website:**
	- **HTML** - used to display content / information on a webpage
	- **CSS** - used to design and style of a webpage (HTML)
	- **JavaScript** - used to define the interactive elements of a webpage
-  external **libraries:**
	- **requests** - used to **pull / retrieve data from an API using Python**
	- **lxml** - used to **process XML and HTML using Python**
	- **BeautifulSoup** - used to **pull data out of HTML and XML files using Python**
- **steps:**
	1. Pick a website and describe the objective
	2. Import necessary external libraries
	3. Use the requests library to download web pages
		- Inspect the website's HTML source and identify the right URLs to download
		- Pass the URL into the .get() method to load an HTML document into response object
		- Download and save web pages locally using the requests library
	4. Use Beautiful Soup to parse and extract information
		- Pass the HTML document into the .Beautifulsoup() method to parse through Python string (HTML text file) from the soup object and explore the structure of downloaded web pages
		- Pass the HTML tags into the right BS4 properties and methods to extract the required information from the soup object
		- Create functions to extract from the page into lists and dictionaries.
	5. Create CSV file(s) with the extracted information
		- Create functions for the end-to-end process of downloading, parsing, and saving CSVs
		- Execute the function with different inputs to create a dataset of CSV files
		- Verify the information in the CSV files by reading them back using Pandas
	6. Document and share the work


___________________________________________________________________________________________________________________________________________


**Web Scraping with Python using requests and BeautifulSoup**

**1. Import the Libraries**

_________

**I. Scrape data from National Weather Service website**

**1. Access and get HTML content from a website**

**2. Parse a web page**
- 2.1. Extract web **'head'** tag
- 2.2. Extract web **'body'** tag
- 2.3. Extract web **'title'** tag

_________

**II. Scrape data from World Population Clock website**

**1. Access and get HTML content from a website**

**2. Parse a web page**
- 2.1. Extract web **'h2'** tag
- 2.2. Extract web **'p'** tag
- 2.3. Extract web **'a'** tag
- 2.4. Extract web **'div'** tag
	- using **'class'** attribute
	- using **'id'** attribute

_________

**III. Scrape data from Data scraping Wikipedia website**

**1. Access and get HTML content from a website**

**2. Parse a web page**
- 2.1. Extract web **'img'** tag

_________

**IV. Scrape data from Books to Scrape website**

**1. Access and get HTML content from a website**

**2. Parse a web page**
- 2.1. Extract **elements across multiple web pages**

_________

**V. Scrape data from Worldometers website**

**1. Access and get HTML content from a website**

**2. Parse a web page**
- 2.1. Extract web **'table'** tag and **save data to .csv file**
