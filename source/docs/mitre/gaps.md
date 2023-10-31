# Gaps in defensive capabilities

## Adversaries professionalising

In general, attackers are multiplying, diversifying their exploits, and making attacks more targeted. [Cybercrime organisations and nation-state offensive groups](../general/adversaries.md) operate much more like traditional companies, with responsibilities, deliverables, and objectives. They quickly adopt new technologies, and have deep pockets from past exploits or from nation-state sponsors, allowing experimenting with and incorporating new technologies like generative AI, which make their attacks more complex and much harder to detect.

## Drive-by downloads number one

There is a shift in Mitre Att&Ck techniques used by attackers. [Phishing for information](phishing.md) as favourited initial access technique has apparently been replaced by [Drive-by downloads](drive-by.md).

## Ransomware on the rise

Ransomware is on the rise and becoming more sophisticated too. These [Ransomware-as-a-Service (RaaS) operations](../general/ransomware.md) can infiltrate networks. Distribution seems to have become more concentrated with adversaries carrying out more targeted attacks using quickly adaptable and sophisticated playbooks.

## More LOL

Adversaries are embracing conventional and commercially available development tools to make attacks faster and harder to detect, more often using [“living off the land" (lol)](https://evasion.tymyrddin.dev/docs/land/readme): Exploits using built-in tools and programs for operating systems ([LOLBAS](https://lolbas-project.github.io), [GTFOBins](https://gtfobins.github.io/) and [loldrivers](https://www.loldrivers.io/)) can deceive threat detection and response systems.

## C&C takeover

Penetration testing tools such as Cobalt Strike and Brute Ratel are developed for red teaming and adversarial attack simulations like cracking passwords, launching spear phishing attacks, remotely controlling and monitoring attacks with a command and control (C&C) framework, and creating reports on the effectiveness of these simulated attacks. Some are even designed to avoid detection by antivirus solutions and endpoint detection and response (EDR). And are now used by adversaries for real attacks.

## Botnet activity increase

Most current malware families use botnets for command and control (C&C) communications. With the growth in malware families and variants, it is to be expected that [botnet activity](../general/botnets.md) increases as well.

## Resources

* [When Pentest Tools Go Brutal: Red-Teaming Tool Being Abused by Malicious Actors](https://unit42.paloaltonetworks.com/brute-ratel-c4-tool/)








