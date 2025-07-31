---
layout: page
title: SharpSCCM
---

{:refdef: style="text-align: center;"}
![license](https://img.shields.io/badge/license-GPL--3.0-02B36C) ![Project Type](https://img.shields.io/badge/type-Red%20Team-FF7E79) ![Slack](https://img.shields.io/badge/language-C%23-5465FF) ![forks](https://img.shields.io/github/forks/Mayyhem/SharpSCCM?color=0F0B38&style=social) ![stargazers](https://img.shields.io/github/stars/Mayyhem/SharpSCCM?color=5465FF&style=social)
{:refdef}

{:refdef: style="text-align: center;"}
![SharpSCCM](/assets/img/sharpsccm.png)
{:refdef}

SharpSCCM is an open-source C# post-exploitation tool designed to leverage Microsoft Configuration Manager (a.k.a. ConfigMgr, formerly SCCM) for lateral movement and credential gathering without requiring access to the SCCM administration console GUI. It was initially created to execute user hunting and lateral movement functions ported from PowerSCCM (by @harmj0y, @jaredcatkinson, @enigma0x3, and @mattifestation) from a C2 agent and contains additional functionality to abuse newly discovered attack primitives for recon, authentication coercion, credential gathering, and arbitrary remote code execution via application deployment or PowerShell on SCCM client devices and servers.

|Resource|Link|
| :--- | :--- |
|GitHub|<https://github.com/Mayyhem/SharpSCCM>|
