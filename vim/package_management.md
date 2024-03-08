# Dependecies
If a package requires a shared resource such as a library, it is said to have a dependecies.

**High an low package manager**
- dpkg --> low package mamager

- apt-get, aptitude --> High level package manager

https://www.freecodecamp.org/news/sudo-apt-get-update-vs-upgrade-what-is-the-difference/
[![update vs upgrade](https://www.freecodecamp.org/news/sudo-apt-get-update-vs-upgrade-what-is-the-difference/)](https://www.freecodecamp.org/news/sudo-apt-get-update-vs-upgrade-what-is-the-difference/)

## Package search
- apt-get upadte and then apt-cache search <search_string>


## installing a package
- apt-get update and then apt-get install <package_name>

If package is downloaded from source other than repo, it can be installed using:
- dpkg --install <package_name>

# removing a package
- pat-get remove <package_name>

# updating a package
## package downloaded from repo
    apt-get update, apt-get upgrade

## package downloaded from non repo
    dpkg --install <package_name>

# list installed package
    dpkg --list

# determine if a package is installed
    dpkg --status <package_name>

# info about a package
    apt-cache show <package_name>