<h1 align="center">
  <img src="static/webscrape.jpg" alt="subshot" width="250px">
  <br>
</h1>

<h4 align="center">Scraping Sites (login/noLogin) in Python Guide</h4>

<p align="center">
  <a href="#Features">Features</a> •
  <a href="#Install">Install</a> •
  <a href="#Post-Installation">Post Installation</a> •
  <a href="#Usage">Usage</a> 
  
</p>


---

`webscrape-tutorial` is a basic tutorial to web scraping using python for beginners. It teaches how to scrape content off a site and also automating login to scrape content that requires login

In the examples, we will be scraping a demo site, https://quotes.toscrape.com/, to show functionality which can be replicated on live sites.

---

# Features

- Exports data as CSV for reviewing (headers can be adjusted)
- Automates login to scrape content behind login wall using selenium
- Uses Exceptions to handle errors

---

# Install

`webscrape-tutorial` requires multiple packages to be installed using PIP

```sh
pip install beautifulsoup4
```
```sh
pip install requests
```
```sh
pip install selenium
```

`webscrape-tutorial` also requires a Chrome Web Driver to be installed on your system

Chrome Driver Linux:

```sh
sudo apt update
sudo apt install chromium-chromedriver
```
ChromeDriver Mac

```sh
brew install chromedriver
```
ChromeDriver Windows

https://developer.chrome.com/docs/chromedriver/downloads

# Post-Installation

# Usage
