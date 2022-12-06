# Email body analysis

The email body is where a malicious payload may be delivered to the recipient either as a link or an attachment.

## Files

If the email has an attachment: Obtain the attachment safely. Accomplishing this is easy in Thunderbird by using the 
`Save` button. Get its hash and check the file's reputation with the hash to see if it's a known malicious document.

* [Talos File Reputation](https://talosintelligence.com/talos_file_reputation)
* [VirusTotal](https://www.virustotal.com/gui/)
* [Reversing Labs file reputation](https://register.reversinglabs.com/file_reputation)
* [Norimaci – Simple And Lightweight Malware Analysis Sandbox For macOS](https://haxf4rall.com/2022/06/24/norimaci-simple-and-lightweight-malware-analysis-sandbox-for-macos-2/)

## URLs

* [URL Extractor](https://www.convertcsv.com/url-extractor.htm)
* [CyberChef Extract URLs recipe](https://gchq.github.io/CyberChef/)

Note the root domain for the extracted URLs and do an analysis on the root domain as well. Also check the reputation 
of the URLs and root domain.

