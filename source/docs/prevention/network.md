# Patterns for NTA

Phishing is classified as [Technique ID 1598 (T1598)](https://attack.mitre.org/techniques/T1598/), and it contains 
three sub-techniques: Spearphishing Service, Spearphishing Attachment and Spearphishing Link.

The [NIST phishing incident response playbook](https://www.incidentresponse.org/workflows/download/Phishing.pdf) gives 
the context and purpose for which NTA patterns will be re-useful for in IDS/IPS.

## Packet capture

Narrow down a packet output using SMTP status codes: `smtp.response.code`

Message for status code 220: 

    <domain> Service ready

Blocked email: `553`, `mailbox name not allowed`

Status code typically preceding a SMTP DATA command: `354`

## Traffic analysis

Standard smtp port: `25`

Initial filter: `smtp`

## Resources

* [Wireshark: SMTP](https://www.wireshark.org/docs/dfref/s/smtp.html)
* [SMTP codes](https://www.mailersend.com/blog/smtp-codes)
* [Wireshark: IMF](https://www.wireshark.org/docs/dfref/i/imf.html)