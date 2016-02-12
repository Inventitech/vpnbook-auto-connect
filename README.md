# VPNBook Auto Connect Script

This is a minimalist shell script that automatically scrapes user credentials
from the free vpn service vpnbook.com and connects to it.

## Installation

Simply copy the `vpnb` shell script somewhere in the system's path.  If you
have administrative access you can install it with `sudo install vpnb.sh
/usr/local/bin/vpnb`.  You can also run `vpnb` in a directory and run it from
there.

## Use
You use _vpnb_ with the following sub-commands. It is handy to have a directory
with vpn profiles downloaded from vpnbook.com.

* `vpnb vpn-profile.ovpn`: Scrape vpnbook.com, and connect to vpn-profile.ovpn,
  using the scraped authentication data.

## Internals

* A file called `auth` is created, which contains the credentials to log-in to
  vpnbook.com

## Project status
This work is stable and feature-complet, patches welcome.
Priority is to increase the system's portability.

## Legal Disclose

Note that we are not in any way associated with vpnbook.com, nor do we advise
its use. There are rumours that it [might be a
honeypot](https://plus.google.com/117604887745850959716/posts/J8tkLw1Fgjv).