# Development moved to [CBPS Git](https://git.cbps.xyz/swindlesmccoop)

# Shell Script Password Manager
This script aims to be a fast, useful, and comprehensible alternative to many password managers that are bloated and often suck. This manager prints all passwords into a ~/.passwords file, which is formatted similarly to a pacman.conf file, with its main function being creating random passwords from /dev/urandom with a random number of characters in between 15 and 30 and appending the password into said ~/.passwords file.\
Please watch [this video](https://www.youtube.com/watch?v=a44Bffke0KU) to see more information about this project.

## Installation
Copy the `sspm` file to your `/usr/bin/` directory.

## Dependencies
The only things you need are things that are most likely already on your machine: bash (only to make sure it is portable), sed, python, echo.

## Usage
sspm [site]: Prints password for [site]\
a, -a, --append: (A)ppend new, custom password\
d, -d, --delete: (D)elete a password\
h, -h, --help: Display a (h)elp message\
n, -n, --new: Generate (n)ew password\
r, -r, --replace: (R)eplace a password with a custom one
