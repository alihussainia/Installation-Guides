# `Docker` Installation Guide


### Step1:
Open `Terminal` and type this cmd:

```bash
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
```
and press `ENTER` key.

### Step2:
Then type this cmd:

```bash
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
```
and press `ENTER` key.

### Step3:
Then type this cmd:

```bash
sudo apt-get install docker-ce docker-ce-cli containerd.io
```
and press `ENTER` key.

### Step4:
Then type this cmd:

```bash
sudo groupadd docker
```
and press `ENTER` key.

### Step5:
Then type this cmd:

```bash
sudo usermod -aG docker $USER
```
and press `ENTER` key.

### Step6:
Then type this cmd:

```bash
sudo -i
```
and press `ENTER` key.

### Step7:
Then type this cmd:

```bash
newgrp docker
```
and press `ENTER` key.

### Step8:
Then type this cmd:

```bash
reboot
```
and press `ENTER` key.

**Note**: The last command will ***`reboot/restart`*** your machine. 
