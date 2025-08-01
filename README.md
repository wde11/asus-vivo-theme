# Installation Guide

Hello this is a guide in installing Grub Theme onto your Grub bootloader.

<p align="center">
  <img src="preview.png" alt="Alt text for image" width="500">
</p>

### Prerequisites

* Install Git:
    ```sh
    sudo apt-get install git-all
    ```

### Installation

1.  Clone this repository to your local machine:
    ```sh
    git clone https://github.com/wde11/asus-vivo-theme.git
    ```

2.  Navigate into the cloned directory:
    ```sh
    cd asus-vivo-theme
    ```

3.  Make the installation script executable:
    ```sh
    chmod +x install.sh
    ```

4.  Run the installation script with `sudo`:
    ```sh
    sudo ./install.sh
    ```

5. ``` You've successfully installed your Grub theme onto your bootloader! Reboot your system to see the changes. ```

### Uninstall

> [!WARNING]
> Don't delete the cloned file when uninstalling the grub theme.

1.  Revert back to terminal:
    ```sh
    cd
    ```

2.  Make the installation script executable:
    ```sh
    chmod +x uninstall.sh
    ```

4.  Run the installation script with `sudo`:
    ```sh
    sudo ./uninstallinstall.sh
    ```

5. ``` You've successfully uninstalled your Grub theme from your bootloader! Reboot your system to see the changes. ```

If you want to configure the file, open your terminal ```sh sudo nano /etc/default/grub ``` and locate ``` #GRUB_THEME="/boot/grub/themes/theme_name/theme.txt" ```

> [!IMPORTANT]
> This theme, might be a work in progress. I may plan to update the design in the future.

@wde11
https://github.com/wde11
