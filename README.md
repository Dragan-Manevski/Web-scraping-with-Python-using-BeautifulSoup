**Web scraping**
- process of **extracting and parsing data from websites** in an **automated fashion**
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
- **steps**
	1. Import necessary external libraries
	2. Pass the URL into the .get() method to load an HTML document into response object
	3. Pass the HTML document into the .Beautifulsoup() method to parse through Python string (HTML text file) from the soup object
	4. Pass the HTML tags into the BS4 method to grab the required information from the soup object
