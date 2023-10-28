# Ransomware

Any ransomware tool development must be lucrative for the threat actor, which used to be far less likely in the case of locking a mobile device, as compared with locking all the Windows systems in an organisation. The bring-your-own-device (BYOD) trend has been growing for many years though.

With Android overwhelmingly the most common operating system for mobile devices, ransomwares targeting Android are on the rise. Publicly known ransomware threats to iOS are substantially less prevalent.

Mobile ransomware sneaks onto your device using social engineering tactics that trick you into downloading malicious content, such as fake apps from third party app stores, [app squatting](squatting.md), infected system or software updates, [phishing](../general/phishing), or [smishing](smishing.md).

Android ransomware often masquerades as a. Traditional ransomware encrypts the files on a device, and some, but not all, Android ransomware variants do encrypt. Different types of techniques can be used to deny a victim access to the device:

* Abusing functionalities, for example, `AndroidOS.MalLocker.B` takes advantage of a high-priority ***call notification*** and overrides the `onUserLeaveHint()` callback to pop up the ransom note. This callback runs when the user presses the ***Home** button or closes an app, thereby preventing dismissing the ransom note.
* Hijacking permissions works by abusing the permission `SYSTEM_ALERT_WINDOW`, which allows an application to overlay a window on top of all other phone apps. 
* Resetting device PIN to prevent access to the device, often used in combination with encrypting files. Examples of these are  DoubleLocker and CovidLock.

WannaLocker actually uses AES encryption to encrypt files, except files on paths including `DCIM`, `download`, `miad`, `android`, or `com` in their path name.

Both [iPhone](https://ios.tymyrddin.dev/docs/malware/ransomware) and [Android](https://android.tymyrddin.dev/docs/malware/ransomware) users have easy access to cheap, cloud-based backup tools (Apple iCloud and Google One), which makes it easy to wipe and restore devices, in the event of a ransomware attack, with minimal loss of data.

## Resources

* [CovidLock: Mobile Coronavirus Tracking App Coughs Up Ransomware](https://www.domaintools.com/resources/blog/covidlock-mobile-coronavirus-tracking-app-coughs-up-ransomware/), 2020
* [Sophisticated Android Ransomware Executes with the Home Button](https://threatpost.com/android-ransomware-home-button/160001/), 2020
* [WannaLocker - The WannaCry Copycat Targeting Android Users in China](https://www.tripwire.com/state-of-security/wannalocker-wannacry-copycat-targeting-android-users-china), 2017

