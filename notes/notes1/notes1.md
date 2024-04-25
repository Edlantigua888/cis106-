# Notes 1: Bash Shell

Commands cover in lecture:

## Echo
### Definition:
Display a line of text
### Usage
`echo` + `option` + `string`
### Examples:
* Display a line of text without the new line
  * `echo -n "hello world"`
* Display a line of text that includes a horizontal tab
  * `echo -e "\thello world"`
* Display 2 lines of text in a single echo command
  * `echo -e "Line 1\nLine2"`
* Display 2 lines of text in a single echo command, with the second line starting with a tab
  * `echo -e "Line 1\n\tLine 2"`
* Display 2 lines of text in a single echo command that starts with a tab
  * `echo -e "\tLine 1\tLine 2"`

<hr>

## date
### Definition
Print or set the system date and time
### Usage
`data` + `option`
### Examples
* Display current date
  * `date`
* Display current date in rfc 5322 format
  * `date -R`

<hr>

## free
### Definition
Display amount of free and used memory in the system
### usage
* `free` + `option`
### Examples
* Display memory utilization
* `free`
* Display memory utilization in human readable format
* `free -h`

<hr>

## uname
### Definition
Print system information
### Usage
`uname` + `option`
### Examples
* Print all information
  * `uname -a`
* Print kernel information
* `uname -s`
* Print node name
  * `uname -n`
  
  <hr>
  
## history
### Definition
Shows command line history
### Usage
`history + option`
## Examples
* Display session history
  * `history`
* Clear session history
  * `history -c`

<hr>

## man
## Definition
An interface to the system reference manuals
## Usage
`man` + `option` + `command`
## Examples
* Open the man page of echo command
`man echo`
* Open a specific man page
  * `man 5 passwd`
* Show all available man pages
  * `man -f passwd`

<hr> 

## apt
### Definition
A set of tools for managing debian packages
### Usage
`sudo'(if required) + `apt` + `apt action` + `package name`
### Examples
* Update and upgrade
  * `sudo apt update && sudo apt upgrde
* installa program
  * `sudo apt install firefox`
* Remove a program
* `sudo apt remove firefox`
* Search for a program
* `apt search "Web Browser"`
* List all installed programs
  * `apt list --installed`

<hr>

## Snap
### Definition
Snaps are app packages for desktop, cloud and IoT that are easy to install, cross platform and dependency
free
### Usage
`sudo` (if needed) + `snap` + `action` + `package name`
### Examples
* Find a snap
  * `snap search "video player"`
*Install a snap
  * `sudo snap install vlc`
* Remove a snap
  * `sudo snap remove vlc`
* Update snaps
  * `sudo snap refresh`

<hr>

## Flatpak
### Definition
Flatpak is a next generation technology for packaging, distributing, and managing software in Linux
### Usage
`sudo` (if needed) + `flatpak` + `action` + `package id`
### Examples
* Search for package
  * `flatpak search "video player"`
* Install package
  * `flatpak install org.videolan.VLC`
* Remove flatpak
  * `flatpak remove org.videolan.VLC`
* Update packages
  * `flatpak update`
