# Frequently used software on macOS


# Toolkits
## [Brew](https://brew.sh/)
The missing package manager for macOS.

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

## [GNU Command Line Tools](http://www.gnu.org/)
GNU is an operating system that is free software—that is, it respects users' freedom. The development of GNU made it possible to use a computer without software that would trample your freedom.


```
brew install coreutils
brew install binutils
brew install diffutils
brew install ed --with-default-names
brew install findutils --with-default-names
brew install gawk
brew install gnu-indent --with-default-names
brew install gnu-sed --with-default-names
brew install gnu-tar --with-default-names
brew install gnu-which --with-default-names
brew install gnutls
brew install grep --with-default-names
brew install gzip
brew install screen
brew install watch
brew install wdiff --with-gettext
brew install wget
brew install xz
```

Modify user PATH

```
echo 'PATH="/usr/local/opt/coreutils/libexec/gnubin:/usr/local/bin:/usr/local/sbin:$PATH"' >> ~/.bashrc 
echo 'export PATH' >> ~/.bashrc
```

## [fish](http://fish.sh/)
fish is a smart and user-friendly command line
shell for macOS, Linux, and the rest of the family. 

```
brew install fish
```


## [nmap](https://nmap.org/)
Nmap ("Network Mapper") is a free and open source (license) utility for network discovery and security auditing. 

```
brew install nmap
```


## [iTerm2](https://iterm2.com)
iTerm2 is a terminal emulator for macOS that does amazing things.

iTerm2 Color Schemes
https://github.com/mbadolato/iTerm2-Color-Schemes


> FirefoxDev


```
brew cask install iterm2
```

## [macdown](https://macdown.uranusjr.com/)
The open source Markdown editor for macOS.

```
brew cask install macdown
```

## [Sublime Text 3](https://www.sublimetext.com/)
A sophisticated text editor for code, markup and prose.

Download from the homepage.

## [Keka](http://www.kekaosx.com/en/)
Free Mac OS X file archiver with the main compression core p7zip.

```
brew cask install keka
```

## [GnuPG](https://www.gnupg.org/)
GnuPG is a complete and free implementation of the OpenPGP standard as defined by RFC4880 (also known as PGP). 

```
brew install gpg
```

## [fio](https://github.com/axboe/fio)
Fio was written by Jens Axboe <axboe@kernel.dk> to enable flexible testing of the Linux I/O subsystem and schedulers.

```
brew install fio
```

## [Cdrtools](http://cdrtools.sourceforge.net/private/cdrecord.html)
Cdrtools is a set of command line programs that allows to record CD/DVD/BluRay media. 

```
brew install cdrtools
```

## [qemu](https://wiki.qemu.org/Main_Page)
QEMU is a generic and open source machine emulator and virtualizer.  

```
brew install qemu
```

## [autojump](https://github.com/wting/autojump)
autojump is a faster way to navigate your filesystem. It works by maintaining a database of the directories you use the most from the command line.

```
brew install autojump
```


## [aria2](https://aria2.github.io/)
aria2 is a lightweight multi-protocol & multi-source command-line download utility. It supports HTTP/HTTPS, FTP, SFTP, BitTorrent and Metalink.

```
brew install aria2
```

## [pv](https://www.ivarch.com/programs/pv.shtml)
pv - Pipe Viewer - is a terminal-based tool for monitoring the progress of data through a pipeline. 

```
brew install pv
```

## [jq](https://stedolan.github.io/jq/)
jq is a lightweight and flexible command-line JSON processor.

```
brew install jq
```
## [autossh](http://macappstore.org/autossh/)
AutoSSH is a command that detects when SSH connections drop and automatically reconnects them.

```
brew install autossh
```

## [GitHub Desktop](https://desktop.github.com)
The new native Extend your GitHub workflow beyond your browser with GitHub Desktop, completely redesigned with Electron.
 
Download from the homepage.


## [Wireshark](https://www.wireshark.org/)
Wireshark is the world’s foremost and widely-used network protocol analyzer.

Download from the homepage.


# Office

## [Microsoft Office](https://www.microsoft.com/en-us/download/office.aspx)
Microsoft Office is an office suite of applications, servers, and services developed by Microsoft.

Download from Appstore.

## [Microsoft OneNote](https://www.onenote.com/)
OneNote is your digital notebook for capturing and organizing everything across your devices. 

Download from Appstore.



## [Microsoft Remote Desktop](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/clients/remote-desktop-mac)
Use the Microsoft Remote Desktop app to connect to a remote PC or virtual apps and desktops made available by your admin. 

Download from Appstore.


## [Chrome](https://www.google.com/chrome/browser/index.html)
Google Chrome is a fast, secure, and free web browser, built for the modern web.

Download from the homepage.

### Plugins
Tampermonkey

## [Firefox](https://www.mozilla.org/en-US/firefox/)
Mozilla Firefox (or simply Firefox) is a free and open-source web browser developed by the Mozilla Foundation and its subsidiary the Mozilla Corporation.

Download from the homepage.

### Plugins
Tampermonkey


## [VMware Fusion / Pro](https://www.vmware.com/products/fusion.html)
Fusion makes running Windows on a Mac easy to implement and use.

Download from the homepage.

## [YoudaoDict](http://cidian.youdao.com/index-mac.html)
As an English, Japanese, Korean, French free universal search word translation software, Youdao dictionary over the years dedicated to providing users with better translation services, for the Mac platform characteristics, we particularly launched a new version, more in line with the use of Mac user translation habits. 

Download from Appstore.

## [LuckNews](http://lucknewsapp.blogspot.com)
LuckNews is a fully featured, easy to use news reader for your Mac. 

Download from Appstore.


## [Kindle]()
The Kindle app gives users the ability to read eBooks on a beautiful, easy-to-use interface.

Download from Appstore.

## [VitalSource Bookshelf](https://bookshelf.vitalsource.com/)
Use VitalSource Bookshelf to download and access VitalSource eTextbooks on your Kindle.

Download from the homepage.


# developer
## [Python](https://python.org/)
Python is a widely used high-level programming language for general-purpose programming, created by Guido van Rossum and first released in 1991. An interpreted language, Python has a design philosophy that emphasizes code readability, and a syntax that allows programmers to express concepts in fewer lines of code than might be used in languages such as C++ or Java. It provides constructs that enable clear programming on both small and large scales.

```
brew install python3
```

## [Go](https://golang.org)
Go is an open source programming language that makes it easy to build simple, reliable, and efficient software.

```
brew install  golang
```
## [Ruby](https://www.ruby-lang.org/en/)
A dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write.

```
brew install  ruby
echo 'export PATH="/usr/local/opt/ruby/bin:$PATH"' >> ~/.zshrc
```

## [JDK](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
Oracle JDK is Oracle's supported Java SE version for customers and for developing, testing, prototyping or demonstrating your Java applications.

```
brew cask install java8
echo 'export JAVA_HOME="/Library/Java/JavaVirtualMachines/jdk1.8.0_162.jdk/Contents/Home"' >> ~/.zshrc

```

## [PyCharm](https://www.jetbrains.com/pycharm/)
PyCharm is an Integrated Development Environment (IDE) used in computer programming, specifically for the Python language. 

Download from the homepage.

# IM

## [Wechat](https://web.wechat.com)
WeChat, the free messaging & calling app available across all smartphones, is now available for your desktop.

Download from Appstore.

# Players

## [Splayer](http://www.splayer.org/)
A Modern Media Player with Smart Translation.

Download from Mac App Store or [github](https://github.com/chiflix/splayerx/releases)

## [NeteaseMusic](http://music.163.com/)
NetEase Music is a music and video streaming service developed and operated by NetEase, Inc.

Download from the homepage.


# Accessiblity


## [Spectacle](https://www.spectacleapp.com/)
Window control with simple and customizable keyboard shortcuts.

```
brew cask install spectacle
```

## [Mounty](http://enjoygineering.com/mounty/)
Mounty uses Apple's Notification Center to issue notification whenever a NTFS volume to re-mount is detected.

```
brew install mounty
```

## [cloc](https://github.com/AlDanial/cloc)
cloc counts blank lines, comment lines, and physical lines of source code in many programming languages.


```
brew install cloc
```


