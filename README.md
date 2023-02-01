# End-to-End Flipkat-Product-Review-Scrapper

**It is an End-To-End project written in Python that takes product name as user input and extracts reviews of that product given by multiple users from flipkart using API's and presents it on the website along with saving it in a structured CSV format.** 

#### Here is a step-by-step description of how the This web scraping project works:

Import libraries: The first step is to import the required libraries, such as Flask API, BeautifulSoup, requests, and Pandas, etc. These libraries are used for extracting the data from the website, sending HTTP requests, and formatting the data into a structured format.

Send HTTP request: In this step, the code sends an HTTP request to the Flipkart website. The response from the website is stored in a variable.

Parse HTML content: The next step is to parse the HTML content of the response using the BeautifulSoup library. This library makes it easy to extract data from HTML by allowing the code to search for specific HTML tags, such as div, span, or p.

Extract data: In this step, the code uses the BeautifulSoup library to extract the data from the HTML content. For example, the code might extract the product name, price, and product description from a product listing on the Flipkart website.

Exception handling: To handle unexpected conditions or errors that may occur during the execution of a program. The purpose of exception handling is to prevent the program from crashing and to provide a mechanism for gracefully recovering from the exception.

Store data: Once the data has been extracted, it is stored in a Pandas DataFrame, which is a two-dimensional data structure that is well suited for storing data in a tabular format.

Save data:  The data is stored in a structured CSV format, using the Pandas library. 

Upload on Website: Using Basic HTML and CSS create a website that can take product name from user as input and return product reviews in a tabluar format.

Make it public: The final step is to upload the project on GitHub for others to evaluate and use if needed.


