# Strategising

About a decade ago it was: Keep systems updated, patch, use strong passwords, install anti-malware, firewalls and proxies, etc.

Now it is: Keep systems updated, patch more, use stronger passwords, use a password vault, MFA, biometric authentication, Next-Gen firewalls, Next-Gen anti-malware, and oh, there's new proxies too, and more, and more overload, tool integrations, maintenance of tools, etc. And usually expensive!

Understanding our current defensive capabilities and mapping them against [Mitre Att&Ck framework](../mitre/README.md) can be helpful for discovering where and how best to invest our time and energy. Then layer the same with potential threats to our devices and (home) networks. The gaps discovered are the areas that should be focused first.

* Prevent|Detect|Respond on [mobiles](../mobile/README) and [workstations](../workstation/README).
* For home and small organisational networks, Raspberry Pi can be bought (not expensive), the [PiRogue suite](https://testlab.tymyrddin.dev/docs/mobile/pts) installed on it, and then used to catch indicators of compromise (IoAs and IoCs) on all our devices, including mobiles. 
* We can do some mobile app vetting and malware analysis, and share results on Pithus. 
* If we run a server, we can [harden it](https://server.tymyrddin.dev/)
* And we can harden our [webservers](https://webserver.tymyrddin.dev/).
* If we run a mailserver, we can [make it smarter](https://mailserver.tymyrddin.dev/).
* And we can use some [active defence](https://honey.tymyrddin.dev/) and set up a [honeyclient](https://honey.tymyrddin.dev/docs/notes/honeyclients) and/or [honeyports](https://honey.tymyrddin.dev/docs/notes/honeyports). 
