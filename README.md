<h1 align="center">Background Microphone Recorder with Termux</h1>
<p align="center">
    <img alt="Version" src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge&color=blue">
    <img alt="Stars" src="https://img.shields.io/github/stars/SaltyMold/Background-Microphone-Recorder-with-Termux?style=for-the-badge&color=magenta">
    <img alt="Forks" src="https://img.shields.io/github/forks/SaltyMold/Background-Microphone-Recorder-with-Termux?color=cyan&style=for-the-badge&color=purple">
    <img alt="License" src="https://img.shields.io/github/license/SaltyMold/Background-Microphone-Recorder-with-Termux?style=for-the-badge&color=blue">
    <br>
    <a href="https://github.com/SaltyMold"><img title="Developer" src="https://img.shields.io/badge/Developer-SaltyMold-red?style=flat-square"></a>
    <img alt="Maintained" src="https://img.shields.io/badge/Maintained-No-blue?style=flat-square">
    <img alt="Written In" src="https://img.shields.io/badge/Written%20In-Bash-yellow?style=flat-square">
</p>

_This script uses **Termux, Termux:API, and Termux:Widget** to create a background microphone recorder. It helps capture **evidence of harassment or violence**, record lectures, or take voice notes discreetly._

## Install the script

First you need to install [Termux](https://f-droid.org/fr/packages/com.termux/), [Termux:API](https://f-droid.org/fr/packages/com.termux.api/) and [Termux:Widget](https://f-droid.org/fr/packages/com.termux.widget/) from F-Droid.

Open Termux:API and Termux:Widget to active them.

Open Termux and execute :

```Bash
pkg install termux-api
pkg install wget

mkdir ~/.shortcuts && mkdir ~/.shortcuts/tasks && mkdir ~/.shortcuts/icons

cd ~/.shortcuts/tasks

wget https://raw.githubusercontent.com/SaltyMold/Background-Microphone-Recorder-with-Termux/main/Microphone

chmod +x Microphone

cd ~/.shortcuts/icons

wget https://raw.githubusercontent.com/SaltyMold/Background-Microphone-Recorder-with-Termux/main/Microphone.png
```

Now go on your desktop and add the Termux shortcut 1×1 widget :

![Screenshot_2025-03-01-21-26-43-467_com mi android globallauncher-edit](https://github.com/user-attachments/assets/c63bbd9f-7693-4b48-bf42-eec677977020)

