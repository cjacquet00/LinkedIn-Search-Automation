# LinkedIn Search Automation
This project utilizes Selenium WebDriver to automate a search for people on Linkedin using Google and click on the resulting LinkedIn profile link.

Prerequisites
Python installed on your system
Chrome browser installed
Chrome WebDriver installed and added to PATH

Setup
Clone this repository to your local machine.
Install the required Python packages using pip:

Copy code
pip install selenium
Download the Chrome WebDriver and ensure it is in your system PATH.
Run the script main.py.
Usage
Upon running the script, a Chrome browser window will open and navigate to Google.
The script will wait for the Google search input field to be visible and then search for "Linkedin Cameron Jacquet".
After the search results load, it will click on the LinkedIn profile link containing the name "Cameron Jacquet".
Finally, the browser window will close automatically after a short delay.

Customization
You can modify the search query by changing the text passed to input_element.send_keys() in the script.
Adjust the wait times (WebDriverWait) as needed based on your system's performance and internet speed.
Feel free to explore and modify the script according to your requirements!
