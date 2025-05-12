# Vagrant


# 🧪 Lab 0: Environment Setup and First Virtual Machines

## 🎯 Objective
Prepare your local development environment by installing essential tools and creating your first virtual machines. This lab ensures all participants have a consistent starting point for the rest of the training.

---

## ✅ Part 1: Install Required Software

Ensure the following tools are installed on your system. Use official websites or trusted package managers (apt, brew, choco, etc.) depending on your OS.


| Software               | Required | Notes                                   |
|------------------------|----------|-----------------------------------------|
| VirtualBox             | ✅ Yes   | https://www.virtualbox.org              |
| VMware Workstation/Player | ❌ Optional | https://www.vmware.com                 |
| Docker Engine          | ✅ Yes   | https://docs.docker.com/engine/install |
| Docker Desktop         | ❌ Optional | For GUI usage                           |
| Vagrant                | ✅ Yes   | https://www.vagrantup.com/downloads     |
| Visual Studio Code     | ✅ Yes   | https://code.visualstudio.com           |
| Google Chrome          | ✅ Yes   | https://www.google.com/chrome/          |
| Discord (software and account)      | ✅ Yes   | https://discord.com                     |
| Slack (software and account)        | ✅ Yes   | https://slack.com                       |

### 🔧 Verification
After installation, verify using terminal:

```bash
vagrant --version
vboxmanage --version
docker --version
code --version
```

---

### Install Vagrant


#### Install on Mac


#### Install on Linux/Ubuntu


#### Install on Windows



# 💻 Create Your First Virtual Machine

Download a base Linux ISO (e.g., Ubuntu 22.04) from the official site.

1. Open **VirtualBox**
2. Create a new VM (Ubuntu)
3. Attach the ISO to the optical drive
4. Install the OS
5. Boot into the installed OS


navigate to the root dirictory and Run `vagrant init` 

> **Note**: Versions may need to be updated if newer are unavailable—check [Vagrant Cloud](https://app.vagrantup.com) for each box.

## 🚀 Start the VMs

```bash
vagrant up
```

Check status:

```bash
vagrant status