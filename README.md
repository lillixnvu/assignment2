# Assignment 2: Shell Scripting
### Introduction
Welcome to my **Shell Scripts Repository**! Here, you'll find two projects that are created to make system setup and configuration easier.
1. **Configuration and Packages Installation Script**: Automates the installation of packages and configuration.
2. **New User Script**: Simplifies the setup process for adding new users.

### Prerequisites 
To get started, please ensure that you meet the following requirements:
- **Operating System**: Arch Linux with Bash
- **Repository Access**: The  [2420-as2-starting-files](https://gitlab.com/cit2420/2420-as2-starting-files) cloned locally.
- **Permissions**: Root access to execute the scripts.

### Project 1: Configuration and Packages Installation Script
This project is created to automate the setup of a new system by installing specified packages and managing configuration files. It reads the package list from the `packages` file and creates symbolic links to the configuration files in the cloned directory.

**Important**: In order to run this script, you MUST run it as the root user or with `sudo` privileges.


**Available Options**:
1. **Install Packages**: To install packages listed in the `packages`, please run the following command:
```bash
sudo ./main -p packages
```
*Optional*: You can modify the `packages` file and add additional packages, or keep it unchanged.

2. **Set Up Configurations**: To set up your configurations, please run:
```bash
sudo ./main -c config
```

---

### Project 2: New User Script
This project is created to help the user to set up new accounts without relying on existing user-creation tools, giving you full control over each step of the setup and allowing for customization.
