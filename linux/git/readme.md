
# Installing Git on Ubuntu

This guide will walk you through the steps to install Git on an Ubuntu-based Linux distribution.

## Prerequisites
- A system running Ubuntu (or any Ubuntu-based distro)
- User account with `sudo` privileges
- Internet connection

## Step-by-Step Guide

### 1. Update the package index
Before installing any package, it is recommended to update the local package index to ensure the latest available versions of packages are fetched.

```bash
sudo apt update
```

### 2. Install Git
Once the package index is updated, install Git using the following command:

```bash
sudo apt install git
```

### 3. Verify the installation
After the installation is complete, verify the installed Git version with the command:

```bash
git --version
```

You should see output similar to this (the version number may vary):

```
git version 2.25.1
```

### 4. Configure Git
Once Git is installed, it is important to configure it with your name and email address. These details will be attached to your Git commits.

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### 5. Optional: View Git Configuration
To check the current Git configuration, use the following command:

```bash
git config --list
```

## Additional Resources
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guide](https://guides.github.com/activities/hello-world/)

With these steps, Git should now be installed and ready to use on your Ubuntu system. Happy coding!