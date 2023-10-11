# seattle-ops-102d10AssignmentsRead-Class-04

## Readings: Installing Ubuntu Linux
Below you will find some reading materials and videos that support today’s topic and the upcoming lecture.

Reading
The Complete Beginner’s Guide to Ubuntu

1. [1.What is Ubuntu?] Ubuntu is an desktop operating system that's based upon the open-source software development.
2. [2.Why would you choose to install the LTS version over regular Ubuntu releases?] The LTS stands for long-term support adn it last for 5 years versus the few months the other offers.
3. [3.What is the Ubuntu GNOME Shell?] The display screen for the desktop.
4. [4.How do I install software from the command line?] To install you will use the apt managing system.To install software from the command line in Ubuntu, you can use the APT package management system. APT (Advanced Package Tool) is a command-line tool for managing software packages in Debian-based Linux distributions, including Ubuntu. Here are the basic steps for installing software using the command line:

1. Open a Terminal:
   You can open a terminal by pressing `Ctrl + Alt + T` or by searching for "Terminal" in the application menu.

2. Update the Package List:
   Before installing software, it's a good idea to update the package list to ensure you have the latest information about available packages. Run the following command:

   ```bash
   sudo apt update
   ```

   You will need to enter your password to run commands with `sudo`.

3. Install Software:
   To install a software package, use the `apt install` command followed by the name of the package you want to install. For example, if you want to install the "htop" system monitoring tool, you would run:

   ```bash
   sudo apt install htop
   ```

   You'll be prompted to confirm the installation. Type 'y' and press Enter to proceed.

4. Remove Software (Optional):
   If you want to remove a package, you can use the `apt remove` or `apt purge` commands. For example:

   ```bash
   sudo apt remove htop
   ```

   The `apt remove` command will remove the package but leave its configuration files. The `apt purge` command will remove the package and its configuration files.

5. Search for Software:
   You can search for available packages using the `apt search` command. For example:

   ```bash
   apt search package_name
   ```

   Replace `package_name` with the name of the package you're looking for.

6. Upgrade Software:
   To upgrade all installed packages to their latest versions, use the following command:

   ```bash
   sudo apt upgrade
   ```

   This command updates all installed packages without installing new ones.

7. Cleaning Up:
   After installing, upgrading, or removing software, you can clean up unused package files to free up disk space with:

   ```bash
   sudo apt autoremove
   ```

   This will remove packages that were automatically installed as dependencies but are no longer needed.

Remember to use `sudo` when necessary to run commands with administrative privileges. Make sure you are connected to the internet because APT needs to download packages from Ubuntu's repositories.

The exact package name and availability may vary depending on the software you want to install, so it's a good idea to search for the package using the `apt search` command if you're not sure about the name.
Videos
The Story of Linux
