<h1 align="center">
  <br>
  <a href="https://github.com/mkdirlove/CXSecurity"><img src="https://github.com/mkdirlove/CXSecurity/blob/main/logo.png" alt="CXSecurity"></a>
  <br>
  A simple Python tool for scraping Dorks, Bugs, and Exploits from CXSecurity (https://cxsecurity.com)
  <br>
</h1>

#### Installation

Copy-paste this into your terminal:

```sh
git clone https://github.com/mkdirlove/CXSecurity.git
```
```
cd CXSecurity
```
```
python3 -m pip install -r requirements.txt
```
```
python3 CXSecurity.py
```
or
```
python3 CXSecurity.py -h
```
#### Usage
```   
█░█░░░░░█▀▀░█▀▀░█▀▀░█░█░█▀▄░▀█▀░▀█▀░█░█
░█░░░▄▀▄░▄▄▄░▀▀█░█▀▀░█░░░█░█░█▀▄░░█░░░█░░░█░
░▀▀▀░▀░▀░░░░░▀▀▀░▀▀▀░▀▀▀░▀▀▀░▀░▀░▀▀▀░░▀░░░▀░ 

Made with ❤️  by @mkdirlove      [ v1.0-dev ]

usage: v3.py [-h] [--bugs] [--exploit] [--dork] --keyword KEYWORD [--pages PAGES] [--output OUTPUT]

A simple Python tool for scraping Dorks, Bugs, and Exploits from CXSecurity (https://cxsecurity.com)

options:
  -h, --help            show this help message and exit
  --bugs, -b            Scrape bugs instead of dorks or exploits
  --exploit, -x         Scrape exploits instead of dorks or bugs
  --dork, -d            Scrape dorks instead of bugs or exploits
  --keyword KEYWORD, -k KEYWORD
                        Filter results based on this keyword
  --pages PAGES, -p PAGES
                        Number of pages to scrape
  --output OUTPUT, -o OUTPUT
                        Output file to save the results
```
#### Example

You can now scrape dorks by running the script like this:
```
python3 CXSecurity.py --dork -k "sql injection" -p 5 -o dorks.txt
```

You can now scrape bugs by running the script like this:
```
python3 CXSecurity.py --bugs -k "microsoft" -p 5 -o bugs.txt
```

You can now scrape exploits by running the script like this:
```
python3 CXSecurity.py --exploit -k "linux" -p 5 -o exploits.txt
```
