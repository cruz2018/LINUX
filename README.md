# LINUX
Linus Training
APT PACHAGE HANDLING UTILITY


the APT pachage handling utility, symple known as "apt-get," is a lightweith and extremely powerfull command-line tool for installing and removing software packages. Apt-get keeps track of everything installed along with the required dependecies. Dependencies are the addtional software packages required for proper functionality of other software.

Installing Application or Packages
Installing additional software is the most basic function of the apt-get command and is simple and straightforward. Tje systax below will provid an example of the necessary usage of the install subcommand:

apt-get install [package_name]
=======================================================================================================

Update
From time to time the resources, or repositories, need to be checked for updates to various application and packages installed on linux. It is recommended that updates are checked before installing any new packages, and is essential before performinig an upgrade to the operating system or software application or packages. The systax for performinig updates follows
apt-get update.
=======================================================================================================

Upgrade
No system is ever perfect, in fact every major operating system is in a constant state of improvement, enhencement, and patch management to offer new features or correct bug. The upgrade function will pull donw and install all new packged versions pf already installed software packges. The beauty of linux-based operating system is that they're open source, meaning that anyoje in the world can submit new code to the functionality of the system if the spo a bug or a need for improvement. This also allows for patches to be updated faster compared to the corporate giants like Microsoft. As stated earlier, it is vital to perform an update before running an upgrade. To upgrade linux use the command.
apt-get -upgrade
=======================================================================================================

Distribution Upgrade
The distribution upgrade function works very similarly to the upgrade function, however, thi function also seeks out sources for special marked packges and they dependencies as well new packges the distribution managers have designated to be included with the newest baseline. For example, when involking the distribution upgrade function, the entire version


