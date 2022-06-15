![Logo](https://raw.githubusercontent.com/StevenBlack/hosts/master/.github/logo.png)

# How Its Work

- You can use a modified HOSTS file to block ads and possibly unwanted programs. 
- This HOSTS File block the connection(s) that supplies Ads Related Datas. 
- The Hosts file is loaded into memory (cache) at startup, so there is no need to turn on, adjust or change any settings. 

# Uses
- Using a well designed HOSTS file can speed the loading of web pages by not having to wait for these ads, annoying banners, hit counters, etc. to load. - This also helps to protect your Privacy and Security by blocking sites that may track your viewing habits.

# How To Set Up The hosts File
## Android 
- Download The APP From [AdAway](https://github.com/AdAway/AdAway/releases) 
- Click The Latest Release
- From Assets Download The APK File
- You can either navigate to your Download folder or simply begin the install by clicking on the completed download in your mobile browser.
- Android will ask you to grant permission to install the app. Grant the permission and it should bounce you back to the installation screen. If not, navigate back to your Download folder after granting the permission to try again.

> AdAway is an open source ad blocker for Android using the hosts file.
> So It Is Safe

![](https://www.androidauthority.com/wp-content/uploads/2011/11/Install-Unknown-Apps.jpg.webp)

## Windows
-  navigate to `c:\Windows\System32\Drivers\etc\hosts`. Alternatively, you can copy/paste this file path into the address bar and then press Enter.
- Replace The hosts File 

# How can I contribute hosts records?

If you discover sketchy domains you feel should be included here, here are some ways to contribute them.

## Fork this repository, add your domains to file, and submit a pull request

Fork this hosts this repo and add your links to hosts file.

Then, submit a pull request.

## Option 3: create your own hosts list as a repo on GitHub

If you're able to curate your own collection of sketchy domains, then curate your own hosts list.  Then signal the existence of your repo as [a new issue](https://github.com/hegdepooja-poojahegde/ADBlockerHosts/issues) and we may include your new repo into the collection of sources we pull whenever we create new versions.

## What is a hosts file?

A hosts file, named `hosts` (with no file extension), is a plain-text file
used by all operating systems to map hostnames to IP addresses.

In most operating systems, the `hosts` file is preferential to `DNS`.
Therefore if a domain name is resolved by the `hosts` file, the request never
leaves your computer.

For example, to nullify requests to some doubleclick.net servers, adding these
lines to your hosts file will do it:

```text
# block doubleClick's servers
0.0.0.0 ad.ae.doubleclick.net
0.0.0.0 ad.ar.doubleclick.net
0.0.0.0 ad.at.doubleclick.net
0.0.0.0 ad.au.doubleclick.net
0.0.0.0 ad.be.doubleclick.net
# etc...
```

## We recommend using `0.0.0.0` instead of `127.0.0.1`

Traditionally most host files use `127.0.0.1`, the *loopback address*, to establish an IP connection to the local machine.

We prefer to use `0.0.0.0`, which is defined as a non-routable meta-address used to designate an invalid, unknown, or non-applicable target.

Using `0.0.0.0` is empirically faster, possibly because there's no wait for a timeout resolution. It also does not
interfere with a web server that may be running on the local PC.

## Why not use `0` instead of `0.0.0.0`?

We tried that.  Using `0` doesn't work universally.

## Location of your hosts file

To modify your current `hosts` file, look for it in the following places and modify it with a text editor.

* **macOS (until 10.14.x macOS Mojave), iOS, Android, Linux**: `/etc/hosts` file.
* **macOS Catalina:** `/private/etc/hosts` file.
* **Windows**: `%SystemRoot%\system32\drivers\etc\hosts` file.

## Updating hosts file on Windows


* **Windows XP**: Start → Run → `cmd`
* **Windows Vista, 7**: Start Button → type `cmd` → right-click Command Prompt → "Run as Administrator"
* **Windows 8**: Start → Swipe Up → All Apps → Windows System → right-click Command Prompt → "Run as Administrator"
* **Windows 10**: Start Button → type `cmd` → right-click Command Prompt → "Run as Administrator"

