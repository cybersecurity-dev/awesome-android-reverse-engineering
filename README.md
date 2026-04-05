<div align="center">
    <p align="center">
        <a href="https://wikipedia.org/wiki/Android_(operating_system)">
          <img width="35%" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/Android.svg" />
        </a>
    </p>

# **`Awesome`** [Android]() Reverse Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)]()
[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefence"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

## 📖 Contents
- [APK File Viewer/Editor](#apk-file-viewereditor)
- [Datasets](#datasets)
- [Scientific Research](#scientific-research)
- [My Other Awesome Lists](#my-other-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)


## Analysing Steps

### 1. Test APK (zipfile) Integrity 

```bash
zip -T <file.apk>
```
```bash
zip -T -v <file.apk>
```
### 2. Check Signatures of APK

```bash
apksigner verify <file.apk>
```


## Tools

### Analysis Frameworks
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - Mobile Security Framework ([MobSF](https://opensecurity.in/)) is an automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.
- [MASTG](https://github.com/OWASP/mastg) - The OWASP Mobile Application Security Testing Guide (MASTG) is a comprehensive manual for mobile app security testing and reverse engineering. It describes technical processes for verifying the OWASP Mobile Security Weakness Enumeration (MASWE) weaknesses, which are in alignment with the OWASP MASVS.

### APK File Viewer/Editor
- [APK Explorer & Editor](https://github.com/apk-editor/APK-Explorer-Editor) - APK Explorer & Editor ([AEE](https://apk-editor.github.io/)), includes a set of open-source tools mainly designed to check out what's inside installed APK's, is strictly made with an aim to inspect an installed APK file.

### [Disassembler](https://en.wikipedia.org/wiki/Disassembler)

### [Decompiler](https://en.wikipedia.org/wiki/Decompiler)

### [Debugging](https://en.wikipedia.org/wiki/Debugger) Tools
- [Mitmproxy](https://github.com/mitmproxy/mitmproxy) - An interactive TLS-capable intercepting [HTTP proxy](https://www.mitmproxy.org/) for penetration testers and software developers. 

### [UNI](https://wikipedia.org/wiki/Uniform_Resource_Identifier) Tools
- [apkleaks](https://github.com/dwisiswant0/apkleaks) - Scanning APK file for URIs, endpoints & secrets.


##

### Datasets
You can access the datasets [here](https://github.com/cybersecurity-dev/awesome-malware-datasets?tab=readme-ov-file#android).

### Scientific Research
You can access the Scientific Research [here](https://github.com/cybersecurity-dev/awesome-static-android-malware-analysis-scientific-research).

### My Other Awesome Lists
You can access the my other awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-android-reverse-engineering/graphs/contributors)!

[🔼 Back to top](#awesome-android-reverse-engineering-)
