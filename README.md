# runOpenvpn3

A bash script to install and start openvpn3 on debian/ubuntu distros.

## Installation steps:

- Open your terminal `CTRL + ALT + T`
- Clone the repository `git clone git@github.com:AhmedFr/runOpenvpn3.git`
- Go inside the repository folder `cd runOpenvpn3 `
- Give the script the appropriate rights `chmod +x runOpenvpn3`
- Run the script ! `./runOpenvpn3`

## First run

The first time you'll run the script it will ask you for your sudo password to be installed in your $PATH (/usr/local/bin).

## Usage

Usage:

    runOpenvpn3 <path to .ovpn file>

    runOpenvpn3 -install: installs openvpn3 on your machine
    runOpenvpn3 -disconnect: disconnects you from current session
