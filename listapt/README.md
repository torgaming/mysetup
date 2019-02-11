"listapt" is the codename for this chapter where package managers are listed based on features that are required to be in various categories. They are fully subjective and may change at any moment. It's a list of package managers and their features in relation to Whonix and the required security necessary to keep users safe according to "Whonix standards" and mainly based on this section:
* https://www.whonix.org/wiki/Install_Software#Avoid_Third_Party_Package_Managers

Background: This interest of mine started after 0brand at https://forums.whonix.org/t/npm-python-pip-on-whonix-workstation-14/6576/2
linked to the avoid third party package managers link https://whonix.org/wiki/Install_Software#Avoid_Third_Party_Package_Managers where [3] and [4] are
* [3] https://web.archive.org/web/20170919173146/https://arstechnica.com/information-technology/2017/09/devs-unknowingly-use-malicious-modules-put-into-official-python-repository/
* [4] https://github.com/pypa/pip/issues/1035 and https://theupdateframework.github.io/

In the beginning the will probably not be very much information and since this is not really my area I'll probably have a lot of question marks spread out but this is what I have so far:

Package managers that I know at least some core/other members of the Whonix community approve of:
* APT doesn't lack the "security safeguards that are standard in Debian" and "The security concern with third party options is they do not verify the code comes from the author" [1a], [1b], [1c]
** APT source code repository: https://salsa.debian.org/apt-team/apt
** APT source code mirror: https://github.com/Debian/apt

Package managers that need further investigation:
* pip
** Main source code repository: https://github.com/pypa/pip/
** "Discourse channel": https://discuss.python.org/c/packaging
** "Dev mailing list": https://groups.google.com/forum/#!forum/pypa-dev
** "Dev IRC" and "User IRC": https://webchat.freenode.net/?channels=%23pypa-dev and https://webchat.freenode.net/?channels=%23pypa (here for informational purposes)
** Open problems: https://www.whonix.org/wiki/Install_Software#Avoid_Third_Party_Package_Managers and look at [3] and [4]
* node.js
** 

sources and references

* [1a] Assuming this page https://www.whonix.org/wiki/Install_Software#Avoid_Third_Party_Package_Managers and associated information is approved by adrelanos as there is no visible infobox on the top of the page where any other page maintainer is listed.
* [1b] 0brand's interest to inform me https://forums.whonix.org/t/npm-python-pip-on-whonix-workstation-14/6576/2
* [1c] HulaHoop's interest to help give clarity on the issue https://forums.whonix.org/t/npm-python-pip-on-whonix-workstation-14/6576/3
