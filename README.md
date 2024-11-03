<a id="readme-top"></a>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/galisiber/berux">
    <img src="https://s3.amazonaws.com/i.snag.gy/i4SYlC.jpg" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Berux</h3>

  <p align="center">
    Berux is a fast parameters/endpoints scrapper tool for SQLI, XSS, RCE, etc
    <br />
    <br />
    <a href="https://github.com/galisiber/berux/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/galisiber/berux/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-berux">About Berux</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <ul>
        <li><a href="#single-url">Single URL</a></li>
        <li><a href="#multi-url">Multi URL</a></li>
        <li><a href="#screenshots">Screenshots</a></li>
      </ul>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About Berux

<img src="https://s3.amazonaws.com/i.snag.gy/1y4cXv.jpg">

Berux is a high-performance endpoint and parameter scraper designed for security professionals and penetration testers. With its ability to swiftly extract potential entry points from web applications, Berux facilitates the discovery of vulnerabilities such as SQL Injection (SQLI), Cross-Site Scripting (XSS), Remote Code Execution (RCE), and Local File Inclusion (LFI). Leveraging advanced scraping techniques, Berux empowers users to efficiently analyze and assess the security posture of their web targets, making it an essential tool in any security toolkit.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Python Version](https://img.shields.io/badge/python-v3.9%2B-blue.svg)](https://www.python.org)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Follow these steps bellow to install Berux

### Prerequisites

Install required programs
* python3
  ```sh
  sudo apt-get install python3
  ```

### Installation

1. Clone the repo & enter directory
   ```sh
   git clone https://github.com/galisiber/berux/; cd berux;
   ```
2. Install required python libraries
   ```sh
   python3 -m pip install requests, bs4 --break-system-packages;
   ```
3. Copy to /bin/ and add execute permission
   ```sh
   sudo cp berux /bin/berux; sudo chmod +x /bin/berux;
   ```
4. Run berux
   ```sh
   berux -h
   ``` 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

### Single URL
```sh
berux -u target.com -o output.txt
```
### Multi URL
```sh
berux -l list.txt -o output.txt -t 10
```

### Screenshots
<img src='https://s3.amazonaws.com/i.snag.gy/cxqDiM.jpg'>
<img src='https://s3.amazonaws.com/i.snag.gy/60hM5l.jpg'>
<p align="right">(<a href="#readme-top">back to top</a>)</p>
