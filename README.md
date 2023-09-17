# AUTO-CREATE-IG-ACCOUNT
Instagram Automatic Account Creator Bot
This Python script automates the process of creating Instagram accounts by generating random usernames. It relies on the Selenium library, so make sure to have it installed before running the code. Please be aware that Instagram has implemented security measures to prevent bot usage, so use this script responsibly.

Note: You will need to specify the web driver you intend to use within the botAccountCreate.py file.

Usage
To use this bot, follow these steps:

Clone this repository to your local machine.

Install the required dependencies by running the following command:

bash
Copy code
pip install -r requirements.txt
Specify the web driver of your choice in the botAccountCreate.py file:

python
Copy code
# For Chrome
browser = webdriver.Chrome("your_chrome_driver_path_here")

# Alternatively, for Firefox
# browser = webdriver.Firefox("your_firefox_driver_path_here")
Run the script using:

bash
Copy code
python botAccountCreate.py
New Features
This project includes the following new features:

Fake Email Address: The bot can generate fake email addresses to use during account creation, enhancing anonymity.

Verification Code Retrieval: It can retrieve the verification code required during the Instagram account creation process, streamlining the registration process.

Please note that this project is an ongoing work, and updates may be made to improve its functionality and bypass Instagram's security measures.

Remember to use this script responsibly and in compliance with Instagram's terms of service and any applicable laws and regulations. Unauthorized or excessive use of automation bots can result in account suspension or legal consequences.
