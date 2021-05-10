# `node.js` and `npm` Installation Guide

### Step1:
To install nodejs and npm on ubuntu linux, first visit the official website to download the installer using: <a href='https://nodejs.org/en/'>Download Installer<a>

### Step2:
Click on **LTS** or **Current** based on your choice. I have chose `Current` release for this project.

### Step3:
After downloading the installer, open the folder in which the installer file is present. It will be a file with `tar.xz` extension.

### Step4:
Now open the `terminal` in that folder (Right click to open menu and click on terminal).

### Step5:
Type this cmd in the terminal:

```bash
sudo apt-get install xz-utils
```
and press `ENTER` key.

### Step6:
Then type this cmd in the terminal with changing the `NodeInstallerFileName` with the installer filename that you just downloaded:

```bash
tar xvfJ NodeInstallerFileName.tar.xz
```
and press `ENTER` key.

### Step7:
Verify the installation using the cmds:

```bash
node -v
```
and

```bash
npm -v
```
