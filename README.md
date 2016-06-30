# University Domains and Names Data List & API

Do you need a list of universites and their domain names? You found it! 


This package includes a JSON file that contains domains, names and countries of most of the universities of the world.
 - You can create a validation script that checks the email domain. 
 - You can automatically generate a user's country and university by looking at their emails.


# Using the Data Source

The whole data source is located in the `world_universities_and_domains.json` file. It is just a list of dictionaries in the following format:

	[
		...
		{
		    "alpha_two_code": "TR",
		    "country": "Turkey",
		    "domain": "sabanciuniv.edu.tr",
		    "name": "Sabanci University",
		    "web_page": "http://www.sabanciuniv.edu.tr/"
		},
		...
	]


NOTE: Some universities use a format like `[user]@[department].[domain].edu`, but this list only contains the `[domain]` portion. 
For example, an email address might be `[student]@cs.usc.edu`, and this list will contain 'usc.edu', the domain for the 
University of Southern California. Take this into consideration if using this list for email address validation.

# Hosted Python API

Please access the hosted python API via [university-domains-list-api](https://github.com/Hipo/university-domains-list-api)

# Contribution
Please contribute to this list! We need your support to keep this list up-to-date.
Do not hesitate to fix any wrong data. It is extremely easy. Just open a PR, or create an issue. 

# Contributors

 - Yiğit Güler
 - Tuna Vargı
 - Patrick Michelberger
 - Barricadenick
 - Rasim Demirbay
 - Ryan White
 - Bilal Arslan
 - anwilli5
 - Thomas Bauer
 - Emin Mastizada
 - Jai
 - Jimi Ford
 - Lars Schwegmann

### Created and maintained by [Hipo](http://www.hipolabs.com)
