# Introduction

I'm merely a fan of automating security procedures in the field of information security. I hope that our shared interests will enable us to improve this programme and make it more useful for people who are worried about their privacy and security online.
So let's get right to it. A simple yet useful tool called "Hello Zero" was created to be a component of the organization's vulnerability and risk management programme. It has been created to collect details about all the hardware and applications that have been installed on your system in order to find zero-day system exploits. Every day, it automatically searches the dark web to look for zero-day vulnerabilities that might harm your system.


## Prerequisites

Required libraries:

- PyQt5
- Packaging
- PySimpleGUI
- Mechanize
- BeautifulSoup4
- Python-Levenshtein
- FuzzyWuzzy
- PySocks

The prerequisites can be effortlessly installed via `pip install -r requirements.txt` command.

It also requires TOR, MySQL (or any other databases), and Python 3.


## Getting Started
The only thing you need to do is run the app and set the E-mail address you would like to receive alerts in "Emails.txt," and **Hello Zero** will do the rest for you.


## How does it work

Eagle0Eye **automatically scans the dark web for you to monitor any zero-day exploits that could impact your system** after gathering all information about the software/hardware installed on your system and its matching version. When it discovers any flaws, it will send you an email with the appropriate information on what you should look out for to lower the risk of these exploits in your environment.

NOTE: Eagle0Eye determines the difference between sequences by using both string metrics and fuzzy string matching.

## Why do I need to use this tool?

Eagle0Eye has been created to **complement your vulnerability and risk management programmes**, as was previously described. We must be aware of the vulnerabilities trafficked on the dark web that damage our systems without any readily available updates, in addition to patch management guidelines. Therefore, this tool may be suitable for you if you are worried about zero-day attacks.
