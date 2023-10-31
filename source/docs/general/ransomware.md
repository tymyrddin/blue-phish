# Ransomware-as-a-Service (RaaS) operations

Think of Ransomware-as-a-service (RaaS) and the larger Crime-as-a-Service (CaaS) market as a variation of the Software-as-a-Service (SaaS) business model. In this business model, developers offer negotiations, cryptocurrency transfers, leak site management, ransomware development, etc. to multiple affiliates. Affiliates receive the largest percentage of the ransom received in trade for the risk of getting identified and arrested. RaaS allows less experienced adversaries to carry out attacks. 

For workstations (Windows, macOS, *nix), a ransomware infection means that data on the device has been encrypted or the operating system is being blocked, and its owner receives a message to pay a ransom. [Mobile ransomware](../mobile/ransomware.md) variants can also encrypt, but most use other techniques.

Ransomware can find its way onto a device in many different ways. Phishing used to be the main point of entry attack. While these are still used, [drive-by download](drive-by.md) (has nothing to do with driving a car, but with visiting websites), VPN vulnerabilities and distribution over botnets are more likely used. 

While individuals, companies, and NGO's are all targets, the compromise of a small number of user accounts that have additional access or privileges, are especially valuable to [adversaries](adversaries.md). 

A ransomware attack can mean the loss of data, spending large sums of money, or both. 

***Use Deploy Disaster-Recovery-as-a-Service (DRaaS) to ensure quick recovery in case of an attack.***

## Detection

* The antivirus scanner or security app sounds an alarm (unless it was not installed or has been bypassed).
* File extensions change to an unfamiliar combination of letters.
* File names change.
* Increased CPU and disk activity.
* Suspicious network communication (with the gangsters). 
* Encrypted files.
* A window containing a ransom demand. A locker ransomware virus locks the entire screen, while crypto ransomware encrypts individual files.

## Removal

If you detect it before the ransom note is delivered, you may be able to stop it from spreading to other devices and files, and to remove it. Files already encrypted remain encrypted (of course you have a backup). 

* Disconnect from wireless and wired devices, external hard drives, storage media, and cloud accounts (prevent it from spreading).
* Scan with AV scanner of security app (identify threat). In the case of screen-locking ransomware, you can probably not get to the security software. Start the device in ***Safe Mode***, and you might get to it. 
* Check the [No More Ransom Project website](https://www.nomoreransom.org/) for solutions.
* Restore encrypted data from backup.

## Prevention

* Keep online backups of your data, and offline encrypted backups of critical data.
* Do not click on links in spam messages or on unknown websites.
* Do not give personal information.
* Do not open suspicious email attachments.
* Never use unknown USB sticks.
* Use VPN services on public Wi-Fi networks.

Because ransomware use is exploding, it is only a matter of time before dedicated anti-ransomware products appear. Paid services of course. Excuse my sarcasm.





