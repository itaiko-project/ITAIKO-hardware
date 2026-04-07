<p align="center">
    <img src="https://github.com/danstronics/ITAIKO/blob/master/banner.jpg" alt="ITAIKO Banner" width="500">
</p>

**ITAIKO** is an open-source, DIY drum controller for *Taiko no Tatsujin* and its simulators. 

Built for rhythm game enthusiasts who want to build an arcade-quality drum at home, or for those who want to update their older drum with a newer and better e-box, the **onigiri-con!**

This project is heavily inspired by, and builds upon the incredible groundwork laid by:
* [**ravinrabbid's DonCon2040**](https://github.com/ravinrabbid/DonCon2040) for the base firmware and console compatibility!
* [**kasashiki3's HIDtaiko**](https://github.com/kasasiki3/HIDtaiko) for the passive sensors cleanup cicuit!

---

## ✨ Features

* **Arcade-like accuracy:** The firmware has been modified with a simple but effective algorithm that provides near-perfect readings even on the cheapest sensors!
* **Low Latency:** The passive cleanup circuit only uses **two diodes** to improve the readablity of the sensors, and combined with the speed of the RP2040 provides super fast readings without any operational amplifiers and active electronics!
* [**Web Configurator:**](https://itaiko.com/) A web-usb based configurator that works on Chromium-based browsers and Firefox*, it supports auto updating, key remapping and includes a built-in drum tester inspired by [**the Zhong Taiko Controller Tester.**](https://tktest.taiko.ac/)
* **Multi-Platform Support:** It's compatible with PC, PS4**, Switch, Android, iOS and even PS3!
* **Fully Open Source:** From the drum, to the onigiri, you can easily 3D print, laser cut and build your own ITAIKO! **We provide the files for everything you'll ever need.**

>*On firefox you'll need to install a lightweight extension to enable WebUSB

>**On PS4 you'll need to provide your own Dualshock 4 Private keys to avoid the 8 minute timeout!
---

## 🎮 Compatibility

**ITAIKO** is designed to be plug-and-play across various platforms. Below is the current compatibility status:

| Platform | Status | Notes |
| :--- | :--- | :--- |
| **PC (Windows/Mac/Linux)** | 🟢 Native | Works instantly with osu!taiko, TJAPlayer3, Taiko Web, etc. Maps as a standard USB gamepad, keyboard or XInput device. |
| **Android / iOS** | 🟢 Native | Works via USB OTG adapter as a standard gamepad/keyboard! |
| **Nintendo Switch (Hori Switch mode)** | 🟢 Native | Spoofs the official HORI Taiko Drum controller. Plug into the dock and play. |
| **PlayStation 3** | ⚠️ Currently untested | Should work as a Dualshock 3. |
| **PlayStation 4 (Hori PS4 mode)** | 🟡 Requires Auth | To avoid restarting the e-box every 8 minutes, **you'll need to provide your own Dualshock 4 private keys** (You can drag-drop them in the web configurator!) |
| **PlayStation 5** | ⚠️ Currently untested | Should work on PS4 backward-compatible games. PS4 limitation still apply here. |



---

##  Hardware

To build your own ITAIKO, you will need a mix of 3D printed parts, basic electronics, and woodwork.

This section is a WIP and will change constantly untill we get the drum design finalized. 


> A full, detailed Bill of Materials (BOM) and assembly guide will be added soon.

---

## Getting Started

>WIP

---

## Credits & Acknowledgements

This project would not exist without the open-source rhythm gaming community. Massive thanks to:

**Kasashiki3**, which made non-amplified piezo readings  comparable to amplified boards!

**ravinrabbid** with his amazing firmware on which we built our upon.

**The Taiko home drumming community** for sharing precious data necessary for this project to come to life.

**Zhong and all the other drum makers** for making arcade accurate home drumming a reality.

---

## License


This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)**.

To view a copy of this license, visit [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/).
