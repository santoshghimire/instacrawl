Instructions for running the script:

1) Install dependencies: pip install -r requirements.txt
3) Install chromedriver: https://sites.google.com/a/chromium.org/chromedriver/downloads
3) Update instagram credentials on file data/login_data/login_details.json
4) Run script using command: scrapy crawl insta
5) Inputs:  a) hashtag (without the #)
			b) Start Date (dd/mm/yyyy)
			c) End Date (dd/mm/yyyy)
			d) Minimum Followers (+ve numbers only)
	To end the program when an input is prompted, enter Ctrs + Z
6) Extracted data is saved in location data/extracted_data/HASHTAG.json
7) It takes a lot of time. So, you need to be patient.