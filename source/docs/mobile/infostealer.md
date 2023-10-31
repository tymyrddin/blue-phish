# Infostealer-as-a-Service (IaaS)

Infostealer attacks are typically financially motivated. For a reasonable monthly fee, adversaries who do not know how to write their own InfoStealer can simply pay to use one written by an expert. It works the same way as popular subscription services. 

## Big business

Infostealer-as-a-Service (IaaS) isn the grander scheme Malware-as-a-Service (MaaS) and the Software-as-a-Service (SaaS) or Criminals-as-a-Service (CraaS) business model. We only had to wait for it. Anyone with a few hundred bucks worth of bitcoin can get started with a few clicks. 

Once a threat actor has purchased an InfoStealer from a dark web or Telegram marketplace, their next task is to spread the malware onto as many machines as possible: 

* Embedding the InfoStealer into a document (e.g. a Microsoft Word document or a Microsoft Excel spreadsheet) then sending the doc out as an attachment in cleverly worded [phishing emails](../general/phishing.md), [smishing](smishing.md) or [vishing](vishing.md), that entice people to open the file. 
* Creating a convincing site with a lookalike domain, the logo of a trusted brand, and a convincing design that tricks unsuspecting users into voluntarily downloading the InfoStealer, thinking that it is a legitimate app. 
* Adding the malicious code to a [squatted app](squatting.md), and then making that corrupted lookalike application available for download from popular app stores. 
* Paying for advertising on Google Ads and Facebook Ads to trick more people into downloading the malware. Using paid ads to distribute malware works wonders because it leverages the trust that people have in both the advertising platform and the brand that they are impersonating on the fake site. If a user sees an ad after making a query in a search engine, they implicitly assume that it is safe to click because they trust the search engine.

## What is stolen

Infostealers can extract a wide range of data from an infected machine, including:

* Credentials used for online banking, email accounts, social media sites, and FTP services.
* Credit card details.
* Emails.
* Hardware information.
* Operating system information.
* Cryptocurrency wallets.
* Screenshots.
* Specific file types (commonly images, documents, spreadsheets, etc).

The stolen data is analysed and any valuable information is collated and organised into a database, which can then be sold on the dark web or through private Telegram channels.

The increased sophistication and complexity is making it more difficult for defenders to detect and prevent infostealers, and requires way more robust operation security training, but try [mobile malware Detection, Response, and Prevention](malware.md). If not works, get help.

## Tongue, cheek

***Deploy Disaster-Recovery-as-a-Service (DRaaS) to ensure quick recovery in case of an attack.***
