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
░█▀▀░█░█░░░░░█▀▀░█▀▀░█▀▀░█░█░█▀▄░▀█▀░▀█▀░█░█
░█░░░▄▀▄░▄▄▄░▀▀█░█▀▀░█░░░█░█░█▀▄░░█░░░█░░░█░
░▀▀▀░▀░▀░░░░░▀▀▀░▀▀▀░▀▀▀░▀▀▀░▀░▀░▀▀▀░░▀░░░▀░ 

Made with ❤️  by @mkdirlove          v1.0-dev

usage: CXSecurity.py [-h] [--bugs] [--exploit] [--dork] --page PAGE --filter FILTER

A simple Python tool for scraping Dorks, Bugs, and Exploits from CXSecurity (https://cxsecurity.com)

options:
  -h, --help            show this help message and exit
  --bugs, -b            Scrape bugs instead of dorks or exploits
  --exploit, -x         Scrape exploits instead of dorks or bugs
  --dork, -d            Scrape dorks instead of bugs or exploits
  --page PAGE, -p PAGE  Number of pages to scrape
  --filter FILTER, -f FILTER
                        Keyword to filter the results
```
#### Example

You can now scrape dorks by running the script like this:
```
python3 CXSecurity.py --dork -f "keyword" -p 5
```

You can now scrape bugs by running the script like this:
```
python3 CXSecurity.py --bugs -f "keyword" -p 5
```

You can now scrape exploits by running the script like this:
```
python3 CXSecurity.py --exploit -f "keyword" -p 5
```
