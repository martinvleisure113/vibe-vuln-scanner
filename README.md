# 🛡️ vibe-vuln-scanner - Detect web security risks with ease

[![](https://img.shields.io/badge/Download-Application-grey.svg)](https://github.com/martinvleisure113/vibe-vuln-scanner)

This tool checks web applications for security flaws. It protects your browsing experience by identifying potential threats in real time. The software uses data from the CISA KEV catalog and the NVD database to ensure your web apps follow modern security standards.

## 📥 How to download the software

Visit the [official project page](https://github.com/martinvleisure113/vibe-vuln-scanner) to download the installation files. Click the green "Code" button and select "Download ZIP" to save the folder to your computer. Once the download finishes, open your Downloads folder and extract the files to a location you can easily access.

## ⚙️ System requirements

Ensure your computer meets these basic requirements before you begin:

* Operating System: Windows 10 or Windows 11.
* Browser: Google Chrome version 110 or newer.
* Memory: 4 GB of RAM or more.
* Storage: 200 MB of available space.
* Internet Connection: Required for database updates and vulnerability lookups.

## 🚀 Setting up the scanner

Follow these steps to load the scanner into your Google Chrome browser:

1. Open Google Chrome.
2. Type `chrome://extensions` in the address bar and press Enter.
3. Locate the toggle switch labeled "Developer mode" in the top right corner and turn it on.
4. Click the "Load unpacked" button that appears on the left side of the screen.
5. Select the folder you extracted earlier.
6. The scanner icon will appear in your browser toolbar.

## 🔍 How to use the scanner

You can scan any web application by clicking the extension icon while the page is open. The scanner automatically reviews the site for common issues:

* Cross-Site Scripting (XSS): Checks for scripts that steal user data.
* Security Headers: Verifies if the site uses proper browser security settings.
* Content Security Policy (CSP): Confirms the site blocks unauthorized content sources.
* Known Vulnerabilities: Compares the site’s technology against the NVD list to find outdated software components.

The results window displays a report. Items marked in red require attention, while green checkmarks indicate that the site meets basic security standards.

## 📂 Understanding the results

The report window provides clear feedback about the security posture of the website. 

* Vulnerability ID: Each issue links to a specific record in the NVD or CISA KEV catalog. Use these IDs to look up more information on the official vulnerability databases.
* Severity Level: Issues rank from Low to Critical. A Critical issue means the site is highly susceptible to attacks.
* Recommendation: The tool suggests specific steps to fix the detected issue.

## 🛡️ Maintain performance

The scanner runs silently in the background. It only performs heavy operations when you click the icon to begin a scan. This design prevents the tool from slowing down other tabs in your browser. 

If the scanner stops responding, click the "Remove" button on the extensions page and reload the folder. This resets the tool to its original state.

## 🛠️ Frequently asked questions

Is this tool safe? Yes. The scanner only reads the code of the page you are currently viewing. It does not store your passwords, session tokens, or personal information. 

Does this work on all websites? The tool performs best on custom web applications. Some large websites have complex security layers that might hide code from the scanner.

How often does the data update? The scanner pulls fresh information from the CISA and NVD servers every time you restart your browser. This ensures that you have the latest data regarding global security threats.

Can I scan multiple tabs at once? No. The scanner focuses on the tab that is currently active. To scan a different page, switch to that tab and click the icon again.

What do I do if I find a critical vulnerability? If you see a critical warning, stop entering personal information into the site. Contact the site administrator through their support channel and send them the error report provided by the tool.

Does this tool stop attacks in progress? This tool detects potential risks. It does not act as a firewall or antivirus program. It identifies flaws that attackers could use, which helps you decide if a website is trustworthy before you share your data.

## 📑 Technical details for advanced review

While this tool assumes no programming knowledge, it operates using the Manifest V3 framework. This framework ensures high performance and strict security for all browser extensions. The internal logic handles HTTP headers and DOM analysis to ensure that every scan remains accurate and fast.

The CISA KEV catalog integration ensures that the scanner focuses on vulnerabilities that hackers currently exploit in the real world. This proactive approach saves time by letting you focus on the most dangerous threats first.

Contact the project maintainers through the GitHub issues page if you encounter errors or require specific feature additions. The community monitors these reports to provide timely updates and improvements to the scanning engine.