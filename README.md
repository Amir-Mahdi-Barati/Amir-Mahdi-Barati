<!-- =====================================================================
     AMIR MAHDI BARATI — GitHub Profile README
     Last updated : 2026 
     ===================================================================== -->

<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:0a2540,80:112240,100:0d1117&height=200&section=header&text=Amir%20Mahdi%20Barati&fontSize=50&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=Mechatronics%20Engineer%20%E2%80%A2%20Embedded%20Systems%20%E2%80%A2%20IoT%20%E2%80%A2%20Isfahan&descAlignY=60&descColor=8b949e&descSize=17"
    alt="header"
  />
</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&multiline=false&width=700&lines=Building+hardware+that+thinks+%F0%9F%A4%96;Firmware+%7C+Python+%7C+Linux+%7C+IoT;National+Khwarizmi+Exhibition+%F0%9F%8F%86+Presenter;CoffeeCodeBox+%E2%80%94+building+what+matters)](https://github.com/Amir-Mahdi-Barati)

</div>

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amir-mahdi-barati-210ab5375)
[![Instagram](https://img.shields.io/badge/@iam__the__amir-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/iam_the_amir)
[![Email](https://img.shields.io/badge/amir.nytrix%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:amir.nytrix@gmail.com)
[![Credly](https://img.shields.io/badge/Credly-FF6B00?style=flat-square&logo=credly&logoColor=white)](https://www.credly.com/users/amir-mahdi-barati)
[![CoffeeCodeBox](https://img.shields.io/badge/CoffeeCodeBox-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/CoffeeCodeBox)

</div>

<br/>

---

## `$ whoami`

```python
#!/usr/bin/env python3
"""
Profile boot sequence — Amir Mahdi Barati
"""

from dataclasses import dataclass, field
from typing import List

@dataclass
class AmirMahdiBarati:
    name:        str        = "Amir Mahdi Barati"
    role:        str        = "Mechatronics Engineer & Developer"
    location:    str        = "Isfahan, Iran"
    org:         str        = "CoffeeCodeBox"
    languages:   List[str]  = field(default_factory=lambda: [
                                 "Python", "C++", "Bash", "C#"
                             ])
    hardware:    List[str]  = field(default_factory=lambda: [
                                 "Arduino", "ESP32", "ESP8266", "Raspberry Pi"
                             ])
    domains:     List[str]  = field(default_factory=lambda: [
                                 "Embedded Systems", "IoT", "PCB Design",
                                 "Cybersecurity", "Linux"
                             ])
    achievement: str        = "🏆 National Khwarizmi Exhibition — presented live"
    currently:   List[str]  = field(default_factory=lambda: [
                                 "Exploring RTOS & bare-metal firmware",
                                 "Building tools under CoffeeCodeBox",
                                 "Deepening Linux internals & kernel scripting"
                             ])
    open_to:     str        = "Collaboration, open-source, and real-world builds 🚀"


if __name__ == "__main__":
    me = AmirMahdiBarati()
    print(f"[BOOT] {me.name} — {me.role}")
    print(f"[INFO] Based in {me.location} | Org: {me.org}")
    print(f"[STAT] {me.achievement}")
    for item in me.currently:
        print(f"[ >> ] {item}")
```

---

## ⚙️ Tech Stack

<div align="center">

| Layer | Tools |
|:---:|:---|
| **Firmware** | ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square&logo=espressif&logoColor=white) ![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white) |
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white) |
| **Web / Backend** | ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) |
| **OS / Infra** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white) |
| **Protocols** | ![I2C](https://img.shields.io/badge/I²C-555555?style=flat-square) ![SPI](https://img.shields.io/badge/SPI-555555?style=flat-square) ![UART](https://img.shields.io/badge/UART-555555?style=flat-square) ![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white) |

</div>

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌑 [Dark-Ray](https://github.com/Amir-Mahdi-Barati/Dark-Ray)
> RGB LED Controller — built & deployed hardware

Full OLED menu system with NeoPixel LED strip control. Dual input: push-buttons + rotary encoder. 10+ effects: rainbow, fire, ice, bounce, wave. Arduino Uno/Nano target. Shipped with User-Guide and wiring schematics.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![NeoPixel](https://img.shields.io/badge/NeoPixel-FF6F00?style=flat-square)
&nbsp;⭐ **3**

</td>
<td width="50%" valign="top">

### 👻 [GhostPhish v1.0](https://github.com/Amir-Mahdi-Barati/GhostPhish-v1.0)
> Phishing Simulation — cybersecurity education

Terminal CLI + Flask web server. Realistic login replicas: Instagram, Gmail, GitHub, LinkedIn. Timestamped credential logging to `/logs/`. Modular architecture for new template injection. Runs on localhost only.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Security](https://img.shields.io/badge/Security-red?style=flat-square)
&nbsp;⭐ **1** · 🍴 **1**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔐 [Crypto-Station](https://github.com/Amir-Mahdi-Barati/Crypto-Station)
> AES + Base64 — runs on an ESP32 chip

No cloud. No server. The ESP32 *is* the server. Browser connects directly to the microcontroller for AES encryption and Base64 encode/decode over Wi-Fi. Proof of concept for edge-native crypto tools.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-00B4D8?style=flat-square)

</td>
<td width="50%" valign="top">

### 👁️ [SysCreep](https://github.com/CoffeeCodeBox/SysCreep) `org: CoffeeCodeBox`
> *"Your system thinks it's alone. We know better."*

Silent, low-footprint system telemetry for security research and education. Monitors, logs, and surfaces system-level activity without detection footprint. Built under CoffeeCodeBox organization.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
&nbsp;⭐ **3**

</td>
</tr>
</table>
---

## 📜 Certifications

<div align="center">

| | Certification | Platform | Verify |
|:---:|:---|:---|:---:|
| 🎖️ | Foundational C# with Microsoft | freeCodeCamp × Microsoft | [Link](https://www.freecodecamp.org/certification/amirmahdibarati/foundational-c-sharp-with-microsoft) |
| 🎖️ | AI Programming I — MOOC | University of Helsinki | [Link](https://certificates.mooc.fi/validate/bpv2x51oeje) |
| 🏅 | All verified badges | Credly | [Profile](https://www.credly.com/users/amir-mahdi-barati) |

</div>

---

<div align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a2540,100:0d1117&height=100&section=footer&reversal=false"
    alt="footer"
  />
  <sub>
    <i>« Engineering is the art of turning ideas into reality »</i>
  </sub>
</div>
