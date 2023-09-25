# Web Scraping and Element Style Finder

This Python script allows you to scrape a website for specific HTML elements and their associated CSS styles. It uses the `requests` library to send a GET request to the website and `BeautifulSoup` for parsing the HTML content.

## How to Use

1. Make sure you have Python installed on your system.

2. Clone or download this repository to your local machine.

3. Open a terminal or command prompt and navigate to the directory where you saved the script.

4. Run the script by executing the following command:


5. Follow the on-screen prompts:

- Enter the URL of the website you want to scrape.
- Specify the HTML tags you want to select (e.g., div, span, h1).
- Specify the CSS style you want to find (e.g., color, font-size).

6. The script will then send a request to the specified URL, scrape the content, and display the selected elements with the specified style.

## Example

Here's an example of how to use the script:

Please enter the URL of the website:  https://www.newsinlevels.com/
Please enter the HTML tags you want to select (e.g., div, span, h1):  div
Please enter the CSS style you want to find (e.g., color, font-size):  title

1. Plankton harms the sea
2. One Year ago: Steel industry problems
3. Grammar for Your Level
4. World Petanque Championship
5. The world is in debt
6. Oldest oak trees in Europe
7. Nigeria crisis
8. Nora the polar bear
9. AI drones help farmers and the planet
10. Britain bans dangerous dogs
11. Police officer laughs after a woman dies
12. Marylin Monroe’s house

## Dependencies

- Python 3.x
- `requests` library
- `beautifulsoup4` library

You can install the required libraries using pip:

pip install requests beautifulsoup4

### 
Enjoy web scraping and finding element styles with ease!
