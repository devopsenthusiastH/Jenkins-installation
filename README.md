# Jenkins Installation Script for Ubuntu

This shell script automates the installation process of Jenkins on Ubuntu systems. It adds the Jenkins repository to your system's software sources list, imports the repository key, updates your package index, installs Jenkins, starts its service, and enables it to start on boot. Additionally, it displays the initial admin password needed to unlock Jenkins during the setup process.

## Usage

1. Download the `install_jenkins.sh` script or copy its content:

    ```bash
    wget https://raw.githubusercontent.com/your-username/your-repo/master/install_jenkins.sh
    ```

2. Make the script executable:

    ```bash
    chmod +x install_jenkins.sh
    ```

3. Run the script as sudo:

    ```bash
    sudo ./install_jenkins.sh
    ```

4. Follow the instructions displayed to complete the Jenkins setup.

## Requirements

- Ubuntu operating system
- Internet connection


## Disclaimer

Please note that this script is provided as-is and without any warranty. Use it at your own risk.
