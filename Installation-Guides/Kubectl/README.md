# `kubectl` Installation Guide
The Kubernetes command-line tool.

### Step1:
Open `Terminal` and type this cmd:

```bash
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
```
then press `ENTER` key.

### Step2:
Then type this cmd:

```bash
sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
```
then press `ENTER` key.

### Step3:
Now, verify the installation by typing this cmd:

```bash
kubectl version --client
```
then press `ENTER` key.
