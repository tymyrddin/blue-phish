# Phishing

***Phishing*** (Email) is a way an adversary might use to contact you in an attempt to gather personal information about you, or worse.

Phishing attempts to trick people into clicking on fraudulent links in emails. The link typically takes the person to a seemingly legitimate site with a malware download, or even just a form that asks them to type in their usernames, passwords, credit card numbers, bank account details, and other private information.

## Detection

* Hover the cursor over the `From` address to confirm the email address and then cross-check the website the official email address and domain used.
* Take note of the spelling of the sender address and email subject line, which may contain small details.
* Look for inconsistencies in grammar and small spelling mistakes in content.
* Check links before you leap. Hover the cursor over the link, and the destination address displays in a tiny bar down the bottom of a browser. On mobile phones, hold down on the link, and a pop-up window with the link will appear.
* An urgent warning tries to frighten people into reacting without considering the consequences.
* "Clickbait" titles on social media, advertising or publications are attention-grabbing.
* Generic greetings are not the common practices of legitimate companies.
* Poor quality logos that are unclear or smaller than usual.

### Email header analysis 

Copy and paste the entire email header and run an analysis tool.

* [Messageheader](https://toolbox.googleapps.com/apps/messageheader/analyzeheader)
* [Message Header Analyzer](https://mha.azurewebsites.net/)
* [mailheader.org](https://mailheader.org/)

It is good to have multiple resources to refer to as each tool might reveal information that another tool may not reveal.

### Sender's IP address

* [IPinfo.io](https://ipinfo.io/)
* [URLScan.io](https://urlscan.io/)  provides a screenshot of the URL. This screenshot is provided, so you don't have to navigate to the URL in question explicitly.
* [Talos Reputation Center](https://talosintelligence.com/reputation)

#### URLs

* [URL Extractor](https://www.convertcsv.com/url-extractor.htm)
* [CyberChef Extract URLs recipe](https://gchq.github.io/CyberChef/)

Note the root domain for the extracted URLs and do an analysis on the root domain as well. Also check the reputation 
of the URLs and root domain.

## Mitigation

* Never open an attachment unless certain that the communication is from a genuine source.
* Run an online virus or malware scanner on files before downloading attachments.

### Attachments

If the email has an attachment: Obtain the attachment safely. Accomplishing this is easy in Thunderbird by using the 
`Save` button. Get its hash and check the file's reputation with the hash to see if it's a known malicious document.

* [Talos File Reputation](https://talosintelligence.com/talos_file_reputation)
* [VirusTotal](https://www.virustotal.com/gui/)
* [Reversing Labs file reputation](https://register.reversinglabs.com/file_reputation)
* [Norimaci – Simple And Lightweight Malware Analysis Sandbox For macOS](https://haxf4rall.com/2022/06/24/norimaci-simple-and-lightweight-malware-analysis-sandbox-for-macos-2/)

## Prevention

* Monitor personal and private accounts and look at the settings. Multifactor verification is a feature that secures email and work accounts.
* Set up at least two email addresses: a private address and a public address.
   * The private address should not be your first and last name, and be protected by never being used on publicly accessible online resources. Or masked. Proton vault and other services allow for this. Or use a graphics file. If it is discovered, change it.
   * The public address as a temporary address and needs to be changed frequently. Consider using a number of public addresses. That way you can perhaps trace which services may be selling addresses to spammers or have been compromised and its data sold on the black market.
* Only open email accounts with providers that include spam filtering.
* Do not respond to any spam, ever.
* Think before you click 'unsubscribe'.
* Web browsers include settings to restrict access to dangerous websites, and when one attempts to access a bad site, an alert message appears. Do not ignore these warnings and do not visit that website or access that file.
* Keep your browser updated, and install the NoScript extension.
