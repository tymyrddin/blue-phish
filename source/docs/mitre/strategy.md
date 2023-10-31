# A Prevent|Detect|Respond strategy

About a decade ago it was: Keep systems updated, patch, use strong passwords, install anti-malware, firewalls and proxies, etc.

Now it is: Keep systems updated, patch more, use stronger passwords, use a password vault, MFA, biometric authentication, Next-Gen firewalls, Next-Gen anti-malware, and oh, there's new proxies too, and more, and more overload, tool integrations, maintenance of tools, etc. And usually expensive!

## Defence strategies

Active defence employs limited offensive action and counterattacks with a defensive posture to deny a contested area or position to the enemy. It requires proactive, anticipatory, and reactionary actions against adversaries. The enemies are already inside the gates ... 

Passive defence is all about measures taken to reduce the probability of and to minimize the effects of damage caused by hostile action without the intention of taking the initiative. It typically uses traditional static defenses and then hopes for the best ...

Prevent|Detect|Respond: Prevention is ideal ofcourse, and it requires detection, and detection without response is of little value ...

## Strategy

* Prevent|Detect|Respond on [mobiles](../mobile/README) and [workstations](../workstation/README).
* For home and small organisational networks, Raspberry Pi can be bought (not expensive), the [PiRogue suite](https://testlab.tymyrddin.dev/docs/mobile/pts) installed on it, and then used to catch indicators of compromise (IoAs and IoCs) on all our devices, including mobiles. 
* We can do some mobile app vetting and malware analysis, and share results on Pithus. 
* If we run a server, we can [harden it](https://server.tymyrddin.dev/)
* And we can harden our [webservers](https://webserver.tymyrddin.dev/).
* If we run a mailserver, we can [make it smarter](https://mailserver.tymyrddin.dev/).
* With all of that covered, we can add some [active defence](https://honey.tymyrddin.dev/) and set up a [honeyclient](https://honey.tymyrddin.dev/docs/notes/honeyclients) and/or [honeyports](https://honey.tymyrddin.dev/docs/notes/honeyports). 
* ...
* Design and organise security operations training. Not for users, not for employees, not for activists, for people! Make it fun, with posters, simulations and hands-on hardening exercises for all likely endpoints.
