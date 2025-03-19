# PhishDetect, a URL & Email phishin Detection Tool

PhishDetect is a command-line phishing detection tool that analyzes URLs and email text to detect malicious links. It uses **regex-based URL analysis,** domain reputation checks, WHOIS lookup, TLD verification, Google Safe Browsing API, and more** to identify potential phishing attempts.

## Features:
✔️ **Extract URLs** from email text or input  
✔️ **Detect phishing keywords** in URLs  
✔️ **Check domain age** via WHOIS lookup  
✔️ **Verify HTTPS security**  
✔️ **Identify suspicious TLDs** (.xyz, .tk, etc.)  
✔️ **Detect URL shorteners** (bit.ly, tinyurl, etc.)  
✔️ **Google Safe Browsing API check**  
✔️ **Analyze WHOIS Email** to check domain registration details


## Set up:
** Make Sure that Python & pip are installed on your system
  You can check by:
      `python --version`

  If they are not installed, you can install them by:

  **Linux**:
    `sudo apt intall python3 python3-pip`
    `pip3 install requests python-whois`


  **macOs**:
    `brew install python3`
    `pip3 install requests python-whois`


  **Windows**:
    Download Python from [python.org](url) and install it.
      (Make sure to add the file in the System Path)


## Installation:
 ** You can install the tool simply by running this command in your terminal:

   **Linux & macOS:**
    `git clone [https://github.com/yourusername/PhishDetect.git](https://github.com/belalmostafaaa/Phishdetect.git)`
    `cd PhishDetect`
    `pip install -r requirements.txt`
    `chmod +x phishdetect.py`
    `python3 phishdetect.py <url> or python phishdetect.py <url> or ./phishdetect.py <url>`
