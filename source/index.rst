Threat landscape @home
====================================

The below writeups are based on reading the usual threat landscapes, picking up what is reuseful for defending people's devices, researching and adding what seems to be missing for @home contexts, updating passive defence strategies, and linking in some device hardening how-tos and hands-on exercises.

With that as foundation, we can develop the more unusual active defence strategies.

.. image:: _static/images/in-progress.png
  :alt: Forever in progress ...

----

Threats
----------------------------

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Background

   docs/backdrop/README.md
   docs/backdrop/adversaries.md
   docs/backdrop/marketplace.md
   docs/backdrop/c2.md
   docs/backdrop/maas.md
   docs/backdrop/raas.md
   docs/backdrop/iaas.md
   docs/backdrop/initial.md
   docs/backdrop/lol.md
   docs/backdrop/botnets.md
   docs/backdrop/youtoo.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Mitre Att&Ck

   docs/mitre/README.md
   docs/mitre/drive-by.md
   docs/mitre/supply-chain.md
   docs/mitre/phishing.md
   docs/mitre/c2.md
   docs/mitre/iocs.md

----

Prevent\|Detect\|Respond
---------------------------------

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Device independent

   docs/independent/README.md
   docs/independent/phishing.md
   docs/independent/drive-by.md
   docs/independent/mfa.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Workstation specific

   docs/workstation/README.md
   docs/workstation/ransomware.md

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Mobile specific

   docs/mobile/README.md
   docs/mobile/malware.md
   docs/mobile/smishing.md
   docs/mobile/vishing.md
   docs/mobile/swapping.md
   docs/mobile/otp-bots.md
   docs/mobile/squatting.md
   docs/mobile/ransomware.md
   docs/mobile/madware.md
   docs/mobile/spyware.md
   docs/mobile/tracking.md
   docs/mobile/stalkerware.md

----

DIY
-------------------------------

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Hardening endpoints

   docs/diy/README.md
   docs/diy/strategy.md
   Android hardening <https://android.tymyrddin.dev/>
   iOS hardening <https://ios.tymyrddin.dev/>
   Hardening Windows <https://windows.tymyrddin.dev/>
   Hardening GNU/Linux <https://linux.tymyrddin.dev/>
   Hardening macOS <https://macos.tymyrddin.dev/>
   Smarter mail servers <https://mailserver.tymyrddin.dev/>
   Active defence <https://honey.tymyrddin.dev/>

----

.. toctree::
   :maxdepth: 1
   :includehidden:
   :caption: Testlab

   Phishing analysis tools <https://testlab.tymyrddin.dev/docs/phishing/README>
   Mobile tools <https://testlab.tymyrddin.dev/docs/mobile/README>
   Reverse engineering tools <https://testlab.tymyrddin.dev/docs/dis/README>

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: TryHackMe rooms

   docs/thm/README.md
   docs/thm/cases.md
   docs/thm/greenholt.md
   Android malware analysis (Pithus and jadx) <https://dfir.tymyrddin.dev/docs/thm/android>
   iOS forensics (SQLiteDB) <https://dfir.tymyrddin.dev/docs/thm/ios>

.. toctree::
   :glob:
   :maxdepth: 1
   :includehidden:
   :caption: Root-me challenges

   APK anti-debug <https://reverse.tymyrddin.dev/docs/root-me/apk-anti-debug>
