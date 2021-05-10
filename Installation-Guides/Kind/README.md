# `kind` Installation Guide
`kind` is a tool for running local Kubernetes clusters using Docker container “nodes”.

### Step1:
Open `Terminal` and type this cmd:

```bash
curl -Lo ./kind https://kind.sigs.k8s.io/dl/v0.10.0/kind-linux-amd64
```
and press `ENTER` key.

### Step2:
Then, type this cmd:

```bash
sudo chmod +x ./kind 
```
and press `ENTER` key.

### Step3:
Then, type this cmd:

```bash
sudo mv ./kind /usr/local/bin
```
### Step4:
Now, verify the installation by typing this cmd:

```bash
kind --version
```
