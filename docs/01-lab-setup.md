# Chapter 1 - Lab Setup

## Objective

The objective of this chapter is to prepare the virtual environment required for the Wazuh Security Operations Center (SOC) lab. Ubuntu Server was selected because it provides a stable and widely supported Linux environment.

---

## Step 1 - Ubuntu Server First Login

After installing Ubuntu Server, the system booted successfully and the initial login screen was displayed. The administrator account created during installation was used to access the server.

### Screenshot

![Ubuntu Server First Login](../screenshots/1_ubuntu%20server%20first%20login.png)

*Figure 1: Ubuntu Server first login after installation.*

---

## Step 2 - Linux Basic Commands

Basic Linux commands were executed to verify that the operating system was functioning correctly and to become familiar with the command-line environment.

Commands used:

```bash
pwd
ls
cd
mkdir
```

### Screenshot

![Linux Basic Commands](../screenshots/2_linux basic commands.png)

*Figure 2: Verification of Linux basic commands.*

---

## Step 3 - Updating Ubuntu

Before installing Wazuh, the Ubuntu Server packages were updated to the latest available versions.

Commands used:

```bash
sudo apt update
sudo apt upgrade -y
```

### Screenshot

![System Update](../screenshots/3_system update.png)

*Figure 3: Ubuntu package update process.*

---

## Outcome

At the end of this chapter:

- Ubuntu Server was installed successfully.
- Basic Linux command-line operations were verified.
- The operating system was fully updated and ready for Wazuh installation.
