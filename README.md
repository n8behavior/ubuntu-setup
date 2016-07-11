Setup & Tweaks
==============

Dotfiles
--------
- cd $HOME && git init
- touch up prompt: PS1
- force_color_prompt

VIM
---
- Pathogen
- ctrl-p

Desktop
-------
- Auto-hide the laucher
- Enable workspaces
- Natural scrolling
- Disable mouse tap to click

Keyboard
--------

- `sed -i 's/XKBOPTIONS=""/XKBOPTIONS="ctrl:nocaps"/' /etc/default/keyboard`
- Ctrl+ARROW move to workspace
- Shift+Ctrl+ARROW move window to workspace

Yubikey
-------
- https://raw.githubusercontent.com/Yubico/libu2f-host/master/70-u2f.rules

Devices
-------
- Pair phone
- Hotspot

Original Packages
-----------------

```
Desired=Unknown/Install/Remove/Purge/Hold
| Status=Not/Inst/Conf-files/Unpacked/halF-conf/Half-inst/trig-aWait/Trig-pend
|/ Err?=(none)/Reinst-required (Status,Err: uppercase=bad)
||/ Name                                                  Version                                             Architecture Description
+++-=====================================================-===================================================-============-===============================================================================
ii  account-plugin-aim                                    3.8.6-0ubuntu9.2                                    amd64        Messaging account plugin for AIM
ii  account-plugin-facebook                               0.11+14.04.20140409.1-0ubuntu2                      all          GNOME Control Center account plugin for single signon - facebook
ii  account-plugin-flickr                                 0.11+14.04.20140409.1-0ubuntu2                      all          GNOME Control Center account plugin for single signon - flickr
ii  account-plugin-google                                 0.11+14.04.20140409.1-0ubuntu2                      all          GNOME Control Center account plugin for single signon
ii  account-plugin-jabber                                 3.8.6-0ubuntu9.2                                    amd64        Messaging account plugin for Jabber/XMPP
ii  account-plugin-salut                                  3.8.6-0ubuntu9.2                                    amd64        Messaging account plugin for Local XMPP (Salut)
ii  account-plugin-twitter                                0.11+14.04.20140409.1-0ubuntu2                      all          GNOME Control Center account plugin for single signon - twitter
ii  account-plugin-windows-live                           0.11+14.04.20140409.1-0ubuntu2                      all          GNOME Control Center account plugin for single signon - windows live
ii  account-plugin-yahoo                                  3.8.6-0ubuntu9.2                                    amd64        Messaging account plugin for Yahoo!
ii  accountsservice                                       0.6.35-0ubuntu7.2                                   amd64        query and manipulate user account information
ii  acl                                                   2.2.52-1                                            amd64        Access control list utilities
ii  acpi-support                                          0.142                                               amd64        scripts for handling many ACPI events
ii  acpid                                                 1:2.0.21-1ubuntu2                                   amd64        Advanced Configuration and Power Interface event daemon
ii  activity-log-manager                                  0.9.7-0ubuntu14.1                                   amd64        blacklist configuration user interface for Zeitgeist
ii  activity-log-manager-control-center                   0.9.7-0ubuntu14.1                                   all          blacklist configuration for Zeitgeist (transitional package)
ii  adduser                                               3.113+nmu3ubuntu3                                   all          add and remove users and groups
ii  adium-theme-ubuntu                                    0.3.4-0ubuntu1                                      all          Adium message style for Ubuntu
ii  aisleriot                                             1:3.10.2-1                                          amd64        GNOME solitaire card game collection
ii  alsa-base                                             1.0.25+dfsg-0ubuntu4                                all          ALSA driver configuration files
ii  alsa-utils                                            1.0.27.2-1ubuntu2                                   amd64        Utilities for configuring and using ALSA
ii  anacron                                               2.3-20ubuntu1                                       amd64        cron-like program that doesn't go by time
ii  apg                                                   2.2.3.dfsg.1-2ubuntu1                               amd64        Automated Password Generator - Standalone version
ii  app-install-data                                      14.04.1                                             all          Ubuntu applications (data files)
ii  app-install-data-partner                              13.04                                               all          Application Installer (data files for partner applications/repositories)
ii  apparmor                                              2.8.95~2430-0ubuntu5.3                              amd64        User-space parser utility for AppArmor
ii  appmenu-qt                                            0.2.7+14.04.20140305-0ubuntu1                       amd64        application menu for Qt
ii  appmenu-qt5                                           0.3.0+14.04.20140415-0ubuntu1                       amd64        application menu for Qt5
ii  apport                                                2.14.1-0ubuntu3.19                                  all          automatically generate crash reports for debugging
ii  apport-gtk                                            2.14.1-0ubuntu3.19                                  all          GTK+ frontend for the apport crash report system
ii  apport-symptoms                                       0.20                                                all          symptom scripts for apport
ii  apt                                                   1.0.1ubuntu2.11                                     amd64        commandline package manager
ii  apt-clone                                             0.3.1~ubuntu11.1                                    all          Script to create state bundles
ii  apt-transport-https                                   1.0.1ubuntu2.11                                     amd64        https download transport for APT
ii  apt-utils                                             1.0.1ubuntu2.11                                     amd64        package management related utility programs
ii  apt-xapian-index                                      0.45ubuntu4                                         all          maintenance and search tools for a Xapian index of Debian packages
ii  aptdaemon                                             1.1.1-1ubuntu5.2                                    all          transaction based package management service
ii  aptdaemon-data                                        1.1.1-1ubuntu5.2                                    all          data files for clients
ii  aptitude                                              0.6.8.2-1ubuntu4                                    amd64        terminal-based package manager
ii  aptitude-common                                       0.6.8.2-1ubuntu4                                    all          architecture indepedent files for the aptitude package manager
ii  apturl                                                0.5.2ubuntu4                                        amd64        install packages using the apt protocol - GTK+ frontend
ii  apturl-common                                         0.5.2ubuntu4                                        amd64        install packages using the apt protocol - common data
ii  archdetect-deb                                        1.95ubuntu2.1                                       amd64        Hardware architecture detector
ii  aspell                                                0.60.7~20110707-1ubuntu1                            amd64        GNU Aspell spell-checker
ii  aspell-en                                             7.1-0-1                                             all          English dictionary for GNU Aspell
ii  at-spi2-core                                          2.10.2.is.2.10.1-0ubuntu1                           amd64        Assistive Technology Service Provider Interface (dbus core)
ii  autoconf                                              2.69-6                                              all          automatic configure script builder
ii  autogen                                               1:5.18-2ubuntu2                                     amd64        automated text file generator
ii  automake                                              1:1.14.1-2ubuntu1                                   all          Tool for generating GNU Standards-compliant Makefiles
ii  autotools-dev                                         20130810.1                                          all          Update infrastructure for config.{guess,sub} files
ii  avahi-autoipd                                         0.6.31-4ubuntu1                                     amd64        Avahi IPv4LL network address configuration daemon
ii  avahi-daemon                                          0.6.31-4ubuntu1                                     amd64        Avahi mDNS/DNS-SD daemon
ii  avahi-utils                                           0.6.31-4ubuntu1                                     amd64        Avahi browsing, publishing and discovery utilities
ii  bamfdaemon                                            0.5.1+14.04.20140409-0ubuntu1                       amd64        Window matching library - daemon
ii  baobab                                                3.8.2-1ubuntu1                                      amd64        GNOME disk usage analyzer
ii  base-files                                            7.2ubuntu5.4                                        amd64        Debian base system miscellaneous files
ii  base-passwd                                           3.5.33                                              amd64        Debian base system master password and group files
ii  bash                                                  4.3-7ubuntu1.5                                      amd64        GNU Bourne Again SHell
ii  bash-completion                                       1:2.1-4ubuntu0.1                                    all          programmable completion for the bash shell
ii  bc                                                    1.06.95-8ubuntu1                                    amd64        GNU bc arbitrary precision calculator language
ii  bcmwl-kernel-source                                   6.30.223.248+bdcom-0ubuntu0.2                       amd64        Broadcom 802.11 Linux STA wireless driver source
ii  bind9-host                                            1:9.9.5.dfsg-3ubuntu0.7                             amd64        Version of 'host' bundled with BIND 9.X
ii  binfmt-support                                        2.1.4-1                                             amd64        Support for extra binary formats
ii  binutils                                              2.24-5ubuntu14                                      amd64        GNU assembler, linker and binary utilities
ii  binutils-mingw-w64-i686                               2.23.52.20130620-1ubuntu1+3build1                   amd64        Cross-binutils for Win32 (x86) using MinGW-w64
ii  binutils-mingw-w64-x86-64                             2.23.52.20130620-1ubuntu1+3build1                   amd64        Cross-binutils for Win64 (x64) using MinGW-w64
ii  bison                                                 2:3.0.2.dfsg-2                                      amd64        YACC-compatible parser generator
ii  bluez                                                 4.101-0ubuntu13.1                                   amd64        Bluetooth tools and daemons
ii  bluez-alsa:amd64                                      4.101-0ubuntu13.1                                   amd64        Bluetooth ALSA support
ii  bluez-cups                                            4.101-0ubuntu13.1                                   amd64        Bluetooth printer driver for CUPS
ii  branding-ubuntu                                       0.8                                                 all          Replacement artwork with Ubuntu branding
ii  brasero                                               3.10.0-0ubuntu1                                     amd64        CD/DVD burning application for GNOME
ii  brasero-cdrkit                                        3.10.0-0ubuntu1                                     amd64        cdrkit extensions for the Brasero burning application
ii  brasero-common                                        3.10.0-0ubuntu1                                     all          Common files for the Brasero CD burning application and library
ii  brltty                                                5.0-2ubuntu2                                        amd64        Access software for a blind person using a braille display
ii  bsdmainutils                                          9.0.5ubuntu1                                        amd64        collection of more utilities from FreeBSD
ii  bsdutils                                              1:2.20.1-5.1ubuntu20.7                              amd64        Basic utilities from 4.4BSD-Lite
ii  bt-dw1560-firmware                                    1.0                                                 all          Bluetooth firmware for DW1560
ii  btrfs-tools                                           3.12-1ubuntu0.1                                     amd64        Checksumming Copy on Write Filesystem utilities
ii  build-essential                                       11.6ubuntu6                                         amd64        Informational list of build-essential packages
ii  busybox-initramfs                                     1:1.21.0-1ubuntu1                                   amd64        Standalone shell setup for initramfs
ii  busybox-static                                        1:1.21.0-1ubuntu1                                   amd64        Standalone rescue shell with tons of builtin utilities
ii  bzip2                                                 1.0.6-5                                             amd64        high-quality block-sorting file compressor - utilities
ii  ca-certificates                                       20160104ubuntu0.14.04.1                             all          Common CA certificates
ii  ca-certificates-java                                  20130815ubuntu1                                     all          Common CA certificates (JKS keystore)
ii  camera-app                                            2.9.1+14.04.20140508-0ubuntu1                       amd64        Camera application
ii  canonical-oem-keyring                                 2009.07.23+build3                                   all          GnuPG keys of Canoncical OEM archives
ii  canonical-poke                                        0.4.1+94~ubuntu14.04.1                              all          send "I am alive" ping to Canonical
ii  casper                                                1.340.2                                             amd64        Run a "live" preinstalled system from read-only media
ii  casper-memdisk                                        3                                                   all          Run a "live" preinstalled system from read-only memory disk or Internet
ii  checkbox-gui                                          0.17.6-0ubuntu6                                     amd64        QML based interface for system testing based on Plainbox.
ii  checkbox-ng                                           0.3-2                                               all          PlainBox based test runner
ii  checkbox-ng-service                                   0.3-2                                               all          CheckBox D-Bus service
ii  cheese-common                                         3.10.2-0ubuntu2                                     all          Common files for the Cheese tool to take pictures and videos
ii  cifs-utils                                            2:6.0-1ubuntu2                                      amd64        Common Internet File System utilities
ii  cli-common                                            0.9                                                 all          common files between all CLI packages
ii  colord                                                1.0.6-1                                             amd64        system service to manage device colour profiles -- system daemon
ii  command-not-found                                     0.3ubuntu12                                         all          Suggest installation of packages in interactive bash sessions
ii  command-not-found-data                                0.3ubuntu12                                         amd64        Set of data files for command-not-found.
ii  compiz                                                1:0.9.11.3+14.04.20150313-0ubuntu1                  all          OpenGL window and compositing manager
ii  compiz-core                                           1:0.9.11.3+14.04.20150313-0ubuntu1                  amd64        OpenGL window and compositing manager
ii  compiz-gnome                                          1:0.9.11.3+14.04.20150313-0ubuntu1                  amd64        OpenGL window and compositing manager - GNOME window decorator
ii  compiz-plugins                                        1:0.9.11.3+14.04.20150313-0ubuntu1                  amd64        OpenGL window and compositing manager - plugins
ii  compiz-plugins-default                                1:0.9.11.3+14.04.20150313-0ubuntu1                  amd64        OpenGL window and compositing manager - default plugins
ii  console-setup                                         1.70ubuntu8                                         all          console font and keymap setup program
ii  coreutils                                             8.21-1ubuntu5.3                                     amd64        GNU core utilities
ii  cpio                                                  2.11+dfsg-1ubuntu1.2                                amd64        GNU cpio -- a program to manage archives of files
ii  cpp                                                   4:4.8.2-1ubuntu6                                    amd64        GNU C preprocessor (cpp)
ii  cpp-4.8                                               4.8.4-2ubuntu1~14.04.1                              amd64        GNU C preprocessor
ii  cracklib-runtime                                      2.9.1-1build1                                       amd64        runtime support for password checker library cracklib2
ii  crda                                                  1.1.2-1ubuntu2                                      amd64        wireless Central Regulatory Domain Agent
ii  cron                                                  3.0pl1-124ubuntu2                                   amd64        process scheduling daemon
ii  cryptsetup-bin                                        2:1.6.1-1ubuntu1                                    amd64        disk encryption support - command line tools
ii  cups                                                  1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - PPD/driver support, web interface
ii  cups-browsed                                          1.0.52-0ubuntu1.7                                   amd64        OpenPrinting CUPS Filters - cups-browsed
ii  cups-bsd                                              1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - BSD commands
ii  cups-client                                           1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - client programs (SysV)
ii  cups-common                                           1.7.2-0ubuntu1.7                                    all          Common UNIX Printing System(tm) - common files
ii  cups-core-drivers                                     1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - PPD-less printing
ii  cups-daemon                                           1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - daemon
ii  cups-filters                                          1.0.52-0ubuntu1.7                                   amd64        OpenPrinting CUPS Filters - Main Package
ii  cups-filters-core-drivers                             1.0.52-0ubuntu1.7                                   amd64        OpenPrinting CUPS Filters - PPD-less printing
ii  cups-pk-helper                                        0.2.5-0ubuntu1                                      amd64        PolicyKit helper to configure cups with fine-grained privileges
ii  cups-ppdc                                             1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - PPD manipulation utilities
ii  cups-server-common                                    1.7.2-0ubuntu1.7                                    all          Common UNIX Printing System(tm) - server common files
ii  dash                                                  0.5.7-4ubuntu1                                      amd64        POSIX-compliant shell
ii  dbus                                                  1.6.18-0ubuntu4.3                                   amd64        simple interprocess messaging system (daemon and utilities)
ii  dbus-x11                                              1.6.18-0ubuntu4.3                                   amd64        simple interprocess messaging system (X11 deps)
ii  dc                                                    1.06.95-8ubuntu1                                    amd64        GNU dc arbitrary precision reverse-polish calculator
ii  dconf-cli                                             0.20.0-1                                            amd64        simple configuration storage system - utilities
ii  dconf-gsettings-backend:amd64                         0.20.0-1                                            amd64        simple configuration storage system - GSettings back-end
ii  dconf-service                                         0.20.0-1                                            amd64        simple configuration storage system - D-Bus service
ii  debconf                                               1.5.51ubuntu2                                       all          Debian configuration management system
ii  debconf-i18n                                          1.5.51ubuntu2                                       all          full internationalization support for debconf
ii  debianutils                                           4.4                                                 amd64        Miscellaneous utilities specific to Debian
ii  deja-dup                                              30.0-0ubuntu4                                       amd64        Back up your files
ii  deja-dup-backend-gvfs                                 30.0-0ubuntu4                                       all          Remote server support for Déjà Dup
ii  dell-browser-defaults                                 0.01                                                all          Dell Browser Defaults
ii  dell-e-star                                           0.03                                                all          Dell Energy Star
rc  dell-eula                                             1.03                                                all          Dell End User License Agreement
ii  dell-my-linux                                         3.3                                                 all          Dell MyLinux program
ii  dell-recovery                                         1.33~somerville1                                    all          Dell Recovery Media Creation Package
rc  dell-recovery-bootloader                              1.32~somerville3                                    all          Bootloader images for Dell's factory process
ii  desktop-file-utils                                    0.22-1ubuntu1                                       amd64        Utilities for .desktop files
ii  dh-python                                             1.20140128-1ubuntu8.2                               all          Debian helper tools for packaging Python libraries and applications
ii  dialog                                                1.2-20130928-1                                      amd64        Displays user-friendly dialog boxes from shell scripts
ii  dictionaries-common                                   1.20.5                                              all          Common utilities for spelling dictionary tools
ii  diffstat                                              1.58-1                                              amd64        produces graph of changes introduced by a diff file
ii  diffutils                                             1:3.3-1                                             amd64        File comparison utilities
ii  dino-meta                                             6                                                   all          Meta package for Dell XPS 13 (2015)
ii  dkms                                                  2.2.0.3-1.1ubuntu5.14.04.5                          all          Dynamic Kernel Module Support Framework
ii  dmidecode                                             2.12-2                                              amd64        SMBIOS/DMI table decoder
ii  dmraid                                                1.0.0.rc16-4.2ubuntu3                               amd64        Device-Mapper Software RAID support tool
ii  dmsetup                                               2:1.02.77-6ubuntu2                                  amd64        Linux Kernel Device Mapper userspace library
ii  dmz-cursor-theme                                      0.4.4ubuntu1                                        all          Style neutral, scalable cursor theme
ii  dnsmasq-base                                          2.68-1ubuntu0.1                                     amd64        Small caching DNS proxy and DHCP/TFTP server
ii  dnsutils                                              1:9.9.5.dfsg-3ubuntu0.7                             amd64        Clients provided with BIND
ii  doc-base                                              0.10.5                                              all          utilities to manage online documentation
ii  dosfstools                                            3.0.26-1                                            amd64        utilities for making and checking MS-DOS FAT filesystems
ii  dpkg                                                  1.17.5ubuntu5.5                                     amd64        Debian package management system
ii  dpkg-dev                                              1.17.5ubuntu5.5                                     all          Debian package development tools
ii  dpkg-repack                                           1.37                                                all          puts an unpacked .deb file back together
ii  duplicity                                             0.6.23-1ubuntu4.1                                   amd64        encrypted bandwidth-efficient backup
ii  dvd+rw-tools                                          7.1-10build1                                        amd64        DVD+-RW/R tools
ii  e2fslibs:amd64                                        1.42.9-3ubuntu1.3                                   amd64        ext2/ext3/ext4 file system libraries
ii  e2fsprogs                                             1.42.9-3ubuntu1.3                                   amd64        ext2/ext3/ext4 file system utilities
ii  ecryptfs-utils                                        104-0ubuntu1.14.04.4                                amd64        ecryptfs cryptographic filesystem (utilities)
ii  ed                                                    1.9-2                                               amd64        classic UNIX line editor
ii  efibootmgr                                            0.5.4-7ubuntu1.2                                    amd64        Interact with the EFI Boot Manager
ii  eject                                                 2.1.5+deb1+cvs20081104-13.1                         amd64        ejects CDs and operates CD-Changers under Linux
ii  empathy                                               3.8.6-0ubuntu9.2                                    amd64        GNOME multi-protocol chat and call client
ii  empathy-common                                        3.8.6-0ubuntu9.2                                    all          GNOME multi-protocol chat and call client (common files)
ii  enchant                                               1.6.0-10ubuntu1                                     amd64        Wrapper for various spell checker engines (binary programs)
ii  eog                                                   3.10.2-0ubuntu5.1                                   amd64        Eye of GNOME graphics viewer program
ii  espeak-data:amd64                                     1.47.11-1ubuntu1                                    amd64        Multi-lingual software speech synthesizer: speech data files
ii  ethtool                                               1:3.13-1                                            amd64        display or change Ethernet device settings
ii  evince                                                3.10.3-0ubuntu10.2                                  amd64        Document (PostScript, PDF) viewer
ii  evince-common                                         3.10.3-0ubuntu10.2                                  all          Document (PostScript, PDF) viewer - common files
ii  evolution-data-server                                 3.10.4-0ubuntu1.5                                   amd64        evolution database backend server
ii  evolution-data-server-common                          3.10.4-0ubuntu1.5                                   all          architecture independent files for Evolution Data Server
ii  evolution-data-server-online-accounts                 3.10.4-0ubuntu1.5                                   amd64        evolution data server integration with Ubuntu Online Accounts
ii  example-content                                       48                                                  all          Ubuntu example content
ii  fakeroot                                              1.20-3ubuntu2                                       amd64        tool for simulating superuser privileges
ii  feh                                                   2.9.3-1                                             amd64        imlib2 based image viewer
ii  file                                                  1:5.14-2ubuntu3.3                                   amd64        Determines file type using "magic" numbers
ii  file-roller                                           3.10.2.1-0ubuntu4.1                                 amd64        archive manager for GNOME
ii  findutils                                             4.4.2-7                                             amd64        utilities for finding files--find, xargs
rc  firefox                                               29.0+build1-0ubuntu0.14.04.2                        amd64        Safe and easy web browser from Mozilla
rc  firstboot-video2                                      1.0kittyhawk6somerville2                            all          Plays a video at firstboot.
ii  flex                                                  2.5.35-10.1ubuntu2                                  amd64        A fast lexical analyzer generator.
ii  fluendo-eula                                          0.12kittyhawk1                                      all          Display the Fluendo codec EULA
ii  folks-common                                          0.9.5-1ubuntu5                                      all          library to aggregates people into metacontacts (common files)
ii  fontconfig                                            2.11.0-0ubuntu4.1                                   amd64        generic font configuration library - support binaries
ii  fontconfig-config                                     2.11.0-0ubuntu4.1                                   all          generic font configuration library - configuration
ii  fonts-dejavu-core                                     2.34-1ubuntu1                                       all          Vera font family derivate with additional characters
ii  fonts-dejavu-extra                                    2.34-1ubuntu1                                       all          Vera font family derivate with additional characters (extra variants)
ii  fonts-droid                                           1:4.3-3ubuntu1.2                                    all          handheld device font with extensive style and language support
ii  fonts-freefont-ttf                                    20120503-4                                          all          Freefont Serif, Sans and Mono Truetype fonts
ii  fonts-kacst                                           2.01+mry-10                                         all          KACST free TrueType Arabic fonts
ii  fonts-kacst-one                                       5.0+svn11846-7                                      all          TrueType font designed for Arabic language
ii  fonts-khmeros-core                                    5.0-7ubuntu1                                        all          KhmerOS Unicode fonts for the Khmer language of Cambodia
ii  fonts-lao                                             0.0.20060226-9                                      all          TrueType font for Lao language
ii  fonts-liberation                                      1.07.3-3                                            all          Fonts with the same metrics as Times, Arial and Courier
ii  fonts-lklug-sinhala                                   0.6-3                                               all          Unicode Sinhala font by Lanka Linux User Group
ii  fonts-nanum                                           20131007-1                                          all          Nanum Korean fonts
ii  fonts-opensymbol                                      2:102.6+LibO4.2.8-0ubuntu4                          all          OpenSymbol TrueType font
ii  fonts-sil-abyssinica                                  1.200-6                                             all          smart Unicode font for Ethiopian and Erythrean scripts (Amharic et al.)
ii  fonts-sil-padauk                                      2.80-2                                              all          smart Unicode font for languages in Myanmar
ii  fonts-takao-pgothic                                   003.02.01-9ubuntu2                                  all          Japanese TrueType font set, Takao P Gothic Fonts
ii  fonts-thai-tlwg                                       1:0.5.1-3                                           all          Thai fonts maintained by TLWG (meta package)
ii  fonts-tibetan-machine                                 1.901b-5                                            all          font for Tibetan, Dzongkha and Ladakhi (OpenType Unicode)
ii  fonts-tlwg-garuda                                     1:0.5.1-3                                           all          Thai Garuda font
ii  fonts-tlwg-kinnari                                    1:0.5.1-3                                           all          Thai Kinnari font
ii  fonts-tlwg-loma                                       1:0.5.1-3                                           all          Thai Loma font
ii  fonts-tlwg-mono                                       1:0.5.1-3                                           all          Thai TlwgMono font
ii  fonts-tlwg-norasi                                     1:0.5.1-3                                           all          Thai Norasi font
ii  fonts-tlwg-purisa                                     1:0.5.1-3                                           all          Thai Purisa font
ii  fonts-tlwg-sawasdee                                   1:0.5.1-3                                           all          Thai Sawasdee font
ii  fonts-tlwg-typewriter                                 1:0.5.1-3                                           all          Thai TlwgTypewriter font
ii  fonts-tlwg-typist                                     1:0.5.1-3                                           all          Thai TlwgTypist font
ii  fonts-tlwg-typo                                       1:0.5.1-3                                           all          Thai TlwgTypo font
ii  fonts-tlwg-umpush                                     1:0.5.1-3                                           all          Thai Umpush font
ii  fonts-tlwg-waree                                      1:0.5.1-3                                           all          Thai Waree font
ii  foomatic-db-compressed-ppds                           20140410-0ubuntu1                                   all          OpenPrinting printer support - Compressed PPDs derived from the database
ii  friendly-recovery                                     0.2.25                                              all          Make recovery more user-friendly
ii  friends                                               0.2.0+14.04.20140217.1-0ubuntu1                     amd64        Social integration with the desktop
ii  friends-dispatcher                                    0.2.0+14.04.20140217.1-0ubuntu1                     all          Social integration with the desktop
ii  friends-facebook                                      0.2.0+14.04.20140217.1-0ubuntu1                     all          Social integration with the desktop - Facebook
ii  friends-twitter                                       0.2.0+14.04.20140217.1-0ubuntu1                     all          Social integration with the desktop - Twitter
ii  ftp                                                   0.17-28                                             amd64        classical file transfer client
ii  fuse                                                  2.9.2-4ubuntu4.14.04.1                              amd64        Filesystem in Userspace
ii  g++                                                   4:4.8.2-1ubuntu6                                    amd64        GNU C++ compiler
ii  g++-4.8                                               4.8.4-2ubuntu1~14.04.1                              amd64        GNU C++ compiler
ii  g++-mingw-w64                                         4.8.2-10ubuntu2+12                                  all          GNU C++ compiler for MinGW-w64
ii  g++-mingw-w64-i686                                    4.8.2-10ubuntu2+12                                  amd64        GNU C++ compiler for MinGW-w64 targeting Win32
ii  g++-mingw-w64-x86-64                                  4.8.2-10ubuntu2+12                                  amd64        GNU C++ compiler for MinGW-w64 targeting Win64
ii  gallery-app                                           0.0.67+14.04.20140502-0ubuntu1                      amd64        Photo gallery for Ubuntu
ii  gcc                                                   4:4.8.2-1ubuntu6                                    amd64        GNU C compiler
ii  gcc-4.8                                               4.8.4-2ubuntu1~14.04.1                              amd64        GNU C compiler
ii  gcc-4.8-base:amd64                                    4.8.4-2ubuntu1~14.04.1                              amd64        GCC, the GNU Compiler Collection (base package)
ii  gcc-4.9-base:amd64                                    4.9.3-0ubuntu4                                      amd64        GCC, the GNU Compiler Collection (base package)
ii  gcc-mingw-w64                                         4.8.2-10ubuntu2+12                                  all          GNU C compiler for MinGW-w64
ii  gcc-mingw-w64-base                                    4.8.2-10ubuntu2+12                                  amd64        GNU Compiler Collection for MinGW-w64 (base package)
ii  gcc-mingw-w64-i686                                    4.8.2-10ubuntu2+12                                  amd64        GNU C compiler for MinGW-w64 targeting Win32
ii  gcc-mingw-w64-x86-64                                  4.8.2-10ubuntu2+12                                  amd64        GNU C compiler for MinGW-w64 targeting Win64
ii  gconf-service                                         3.2.6-0ubuntu2                                      amd64        GNOME configuration database system (D-Bus service)
ii  gconf-service-backend                                 3.2.6-0ubuntu2                                      amd64        GNOME configuration database system (D-Bus service)
ii  gconf2                                                3.2.6-0ubuntu2                                      amd64        GNOME configuration database system (support tools)
ii  gconf2-common                                         3.2.6-0ubuntu2                                      all          GNOME configuration database system (common files)
ii  gcr                                                   3.10.1-1                                            amd64        GNOME crypto services (daemon and tools)
ii  gdb                                                   7.7.1-0ubuntu5~14.04.2                              amd64        GNU Debugger
ii  gdisk                                                 0.8.8-1ubuntu0.1                                    amd64        GPT fdisk text-mode partitioning tool
ii  gedit                                                 3.10.4-0ubuntu4                                     amd64        official text editor of the GNOME desktop environment
ii  gedit-common                                          3.10.4-0ubuntu4                                     all          official text editor of the GNOME desktop environment (support files)
ii  genisoimage                                           9:1.1.11-2ubuntu3                                   amd64        Creates ISO-9660 CD-ROM filesystem images
ii  geoclue                                               0.12.99-3ubuntu1                                    amd64        Geographic information framework
ii  geoclue-ubuntu-geoip                                  1.0.2+14.04.20131125-0ubuntu2                       amd64        Provide positioning for GeoClue via Ubuntu GeoIP services
ii  geoip-database                                        20140313-1                                          all          IP lookup command line tools that use the GeoIP library (country database)
ii  gettext                                               0.18.3.1-1ubuntu3                                   amd64        GNU Internationalization utilities
ii  gettext-base                                          0.18.3.1-1ubuntu3                                   amd64        GNU Internationalization utilities for the base system
ii  gfortran-mingw-w64                                    4.8.2-10ubuntu2+12                                  all          GNU Fortran compiler for MinGW-w64
ii  gfortran-mingw-w64-i686                               4.8.2-10ubuntu2+12                                  amd64        GNU Fortran compiler for MinGW-w64 targeting Win32
ii  gfortran-mingw-w64-x86-64                             4.8.2-10ubuntu2+12                                  amd64        GNU Fortran compiler for MinGW-w64 targeting Win64
ii  ghostscript                                           9.10~dfsg-0ubuntu10.4                               amd64        interpreter for the PostScript language and for PDF
ii  ghostscript-x                                         9.10~dfsg-0ubuntu10.4                               amd64        interpreter for the PostScript language and for PDF - X11 support
ii  giblib1:amd64                                         1.2.4-9                                             amd64        wrapper library for imlib2, and other stuff
ii  gir1.2-accounts-1.0                                   1.15+14.04.20131126.2-0ubuntu3                      amd64        typelib file for libaccounts-glib0
ii  gir1.2-appindicator3-0.1                              12.10.1+13.10.20130920-0ubuntu4.1                   amd64        Typelib files for libappindicator3-1.
ii  gir1.2-atk-1.0                                        2.10.0-2ubuntu2                                     amd64        ATK accessibility toolkit (GObject introspection)
ii  gir1.2-atspi-2.0                                      2.10.2.is.2.10.1-0ubuntu1                           amd64        Assistive Technology Service Provider (GObject introspection)
ii  gir1.2-dbusmenu-glib-0.4                              12.10.3+14.04.20140612-0ubuntu1                     amd64        typelib file for libdbusmenu-glib4
ii  gir1.2-dee-1.0                                        1.2.7+14.04.20140324-0ubuntu1                       amd64        GObject introspection data for the Dee library
ii  gir1.2-ebook-1.2                                      3.10.4-0ubuntu1.5                                   amd64        GObject introspection for the EBook library
ii  gir1.2-ebookcontacts-1.2                              3.10.4-0ubuntu1.5                                   amd64        GObject introspection for the EBook Contacts library
ii  gir1.2-edataserver-1.2                                3.10.4-0ubuntu1.5                                   amd64        GObject introspection for the EDataServer library
ii  gir1.2-freedesktop                                    1.40.0-1ubuntu0.2                                   amd64        Introspection data for some FreeDesktop components
ii  gir1.2-gdata-0.0                                      0.14.1-1                                            amd64        GObject introspection data for the GData webservices library
ii  gir1.2-gdkpixbuf-2.0                                  2.30.7-0ubuntu1.2                                   amd64        GDK Pixbuf library - GObject-Introspection
ii  gir1.2-glib-2.0                                       1.40.0-1ubuntu0.2                                   amd64        Introspection data for GLib, GObject, Gio and GModule
ii  gir1.2-gmenu-3.0                                      3.10.1-0ubuntu2                                     amd64        GObject introspection data for the GNOME menu library
ii  gir1.2-gnomebluetooth-1.0                             3.8.2.1-0ubuntu4.2                                  amd64        Introspection data for GnomeBluetooth
ii  gir1.2-gnomekeyring-1.0                               3.8.0-2                                             amd64        GNOME keyring services library - introspection data
ii  gir1.2-goa-1.0                                        3.10.3-0ubuntu1                                     amd64        Introspection data for GNOME Online Accounts
ii  gir1.2-gst-plugins-base-1.0                           1.2.4-1~ubuntu2                                     amd64        Description: GObject introspection data for the GStreamer Plugins Base library
ii  gir1.2-gstreamer-1.0                                  1.2.4-0ubuntu1                                      amd64        Description: GObject introspection data for the GStreamer library
ii  gir1.2-gtk-3.0                                        3.10.8-0ubuntu1.6                                   amd64        GTK+ graphical user interface library -- gir bindings
ii  gir1.2-gtksource-3.0                                  3.10.2-0ubuntu1                                     amd64        gir files for the GTK+ syntax highlighting widget
ii  gir1.2-gudev-1.0                                      1:204-5ubuntu20.18                                  amd64        libgudev-1.0 introspection data
ii  gir1.2-ibus-1.0                                       1.5.5-1ubuntu3.2                                    amd64        Intelligent Input Bus - introspection data
ii  gir1.2-javascriptcoregtk-3.0                          2.4.8-1ubuntu1~ubuntu14.04.1                        amd64        JavaScript engine library from WebKitGTK+ - GObject introspection data
ii  gir1.2-json-1.0                                       0.16.2-1ubuntu1                                     amd64        GLib JSON manipulation library (introspection data)
ii  gir1.2-messagingmenu-1.0                              13.10.1+14.04.20140410-0ubuntu1                     amd64        Messaging Menu - gir bindings
ii  gir1.2-networkmanager-1.0                             0.9.8.8-0ubuntu7.2                                  amd64        GObject introspection data for NetworkManager
ii  gir1.2-notify-0.7                                     0.7.6-1ubuntu3                                      amd64        sends desktop notifications to a notification daemon (Introspection files)
ii  gir1.2-packagekitglib-1.0                             0.8.12-1ubuntu5                                     amd64        GObject introspection data for the PackageKit GLib library
ii  gir1.2-pango-1.0                                      1.36.3-1ubuntu1.1                                   amd64        Layout and rendering of internationalized text - gir bindings
ii  gir1.2-peas-1.0                                       1.8.1-2ubuntu2                                      amd64        Application plugin library (introspection files)
ii  gir1.2-rb-3.0                                         3.0.2-0ubuntu2                                      amd64        GObject introspection data for the rhythmbox music player
ii  gir1.2-secret-1                                       0.16-0ubuntu1                                       amd64        Secret store (GObject-Introspection)
ii  gir1.2-signon-1.0                                     1.10daily13.06.25-0ubuntu2                          amd64        GObject introspection data for the Signon library
ii  gir1.2-soup-2.4                                       2.44.2-1ubuntu2                                     amd64        GObject introspection data for the libsoup HTTP library
ii  gir1.2-timezonemap-1.0                                0.4.1                                               amd64        typelib interface for libtimezonemap
ii  gir1.2-totem-1.0                                      3.10.1-1ubuntu4                                     amd64        GObject introspection data for Totem media player
ii  gir1.2-totem-plparser-1.0                             3.10.2-0ubuntu1                                     amd64        GObject introspection data for the Totem Playlist Parser library
ii  gir1.2-udisks-2.0                                     2.1.3-1ubuntu0.1                                    amd64        GObject based library to access udisks2 - introspection data
ii  gir1.2-unity-5.0:amd64                                7.1.4+14.04.20140210-0ubuntu1                       amd64        GObject introspection data for the Unity library
ii  gir1.2-vte-2.90                                       1:0.34.9-1ubuntu2                                   amd64        GObject introspection data for the VTE library
ii  gir1.2-webkit-3.0                                     2.4.8-1ubuntu1~ubuntu14.04.1                        amd64        Web content engine library for GTK+ - GObject introspection data
ii  gir1.2-wnck-3.0                                       3.4.7-0ubuntu3.1                                    amd64        GObject introspection data for the WNCK library
ii  gir1.2-xkl-1.0                                        5.4-0ubuntu1                                        amd64        X Keyboard Extension high-level API - introspection data
ii  gkbd-capplet                                          3.6.0-0ubuntu2                                      amd64        GNOME Panel applet for libgnomekbd
ii  glib-networking:amd64                                 2.40.0-1ubuntu0.1                                   amd64        network-related giomodules for GLib
ii  glib-networking-common                                2.40.0-1ubuntu0.1                                   all          network-related giomodules for GLib - data files
ii  glib-networking-services                              2.40.0-1ubuntu0.1                                   amd64        network-related giomodules for GLib - D-Bus services
ii  gnat-mingw-w64                                        4.8.2-12ubuntu2+12.1                                all          GNU Ada compiler for MinGW-w64
ii  gnat-mingw-w64-base                                   4.8.2-12ubuntu2+12.1                                amd64        GNU Ada compiler for MinGW-w64 (base package)
ii  gnat-mingw-w64-i686                                   4.8.2-12ubuntu2+12.1                                amd64        GNU Ada compiler for MinGW-w64 targeting Win32
ii  gnat-mingw-w64-x86-64                                 4.8.2-12ubuntu2+12.1                                amd64        GNU Ada compiler for MinGW-w64 targeting Win64
ii  gnome-accessibility-themes                            3.10.0-1ubuntu2                                     all          Accessibility themes for the GNOME desktop
ii  gnome-bluetooth                                       3.8.2.1-0ubuntu4.2                                  amd64        GNOME Bluetooth tools
ii  gnome-calculator                                      1:3.10.3-0ubuntu0.1.1                               amd64        GNOME desktop calculator
ii  gnome-contacts                                        3.8.3-1ubuntu1                                      amd64        Contacts manager for GNOME
ii  gnome-control-center-shared-data                      1:3.6.3-0ubuntu56.1                                 all          configuration applets for GNOME - shared data
ii  gnome-desktop3-data                                   3.8.4-0ubuntu3.2                                    all          Common files for GNOME desktop apps
ii  gnome-disk-utility                                    3.10.0-1ubuntu3                                     amd64        manage and configure disk drives and media
ii  gnome-font-viewer                                     3.8.0-1build1                                       amd64        font viewer for GNOME
ii  gnome-icon-theme                                      3.10.0-0ubuntu2                                     all          GNOME Desktop icon theme (small subset)
ii  gnome-icon-theme-symbolic                             3.10.1-1ubuntu1                                     all          GNOME desktop icon theme (symbolic icons)
ii  gnome-keyring                                         3.10.1-1ubuntu4.2                                   amd64        GNOME keyring services (daemon and tools)
ii  gnome-mahjongg                                        1:3.10.2-0ubuntu1                                   amd64        classic Eastern tile game for GNOME
ii  gnome-menus                                           3.10.1-0ubuntu2                                     amd64        GNOME implementation of the freedesktop menu specification
ii  gnome-mines                                           1:3.10.1-0ubuntu1                                   amd64        popular minesweeper puzzle game for GNOME
ii  gnome-orca                                            3.10.3-0ubuntu1                                     all          Scriptable screen reader
ii  gnome-power-manager                                   3.8.2-1ubuntu2                                      amd64        power management tool for the GNOME desktop
ii  gnome-screensaver                                     3.6.1-0ubuntu13                                     amd64        GNOME screen saver and locker
ii  gnome-screenshot                                      3.10.1-0ubuntu1                                     amd64        screenshot application for GNOME
ii  gnome-session-bin                                     3.9.90-0ubuntu12.1                                  amd64        GNOME Session Manager - Minimal runtime
ii  gnome-session-canberra                                0.30-0ubuntu3                                       amd64        GNOME session log in and log out sound events
ii  gnome-session-common                                  3.9.90-0ubuntu12.1                                  all          GNOME Session Manager - common files
ii  gnome-settings-daemon-schemas                         3.8.6.1-0ubuntu11.2                                 all          gnome-settings-daemon schemas
ii  gnome-sudoku                                          1:3.10.2-0ubuntu3.1                                 all          Sudoku puzzle game for GNOME
ii  gnome-system-log                                      3.8.1-1svn1                                         amd64        system log viewer for GNOME
ii  gnome-system-monitor                                  3.8.2.1-2ubuntu1                                    amd64        Process viewer and system resource monitor for GNOME
ii  gnome-terminal                                        3.6.2-0ubuntu1                                      amd64        GNOME terminal emulator application
ii  gnome-terminal-data                                   3.6.2-0ubuntu1                                      all          Data files for the GNOME terminal emulator
ii  gnome-user-guide                                      3.8.2-1                                             all          GNOME user's guide
ii  gnome-user-share                                      3.0.4-0ubuntu1                                      amd64        User level public file sharing via WebDAV or ObexFTP
ii  gnome-video-effects                                   0.4.1-0ubuntu1                                      all          GNOME Video Effects
ii  gnomine                                               1:3.10.1-0ubuntu1                                   all          popular minesweeper puzzle game for GNOME (transitional package)
ii  gnupg                                                 1.4.16-1ubuntu2.3                                   amd64        GNU privacy guard - a free PGP replacement
ii  google-chrome-stable                                  48.0.2564.116-1                                     amd64        The web browser from Google
ii  gpgv                                                  1.4.16-1ubuntu2.3                                   amd64        GNU privacy guard - signature verification tool
ii  grep                                                  2.16-1                                              amd64        GNU grep, egrep and fgrep
ii  groff-base                                            1.22.2-5                                            amd64        GNU troff text-formatting system (base system components)
ii  growisofs                                             7.1-10build1                                        amd64        DVD+-RW/R recorder
ii  grub-common                                           2.02~beta2-9ubuntu1.7                               amd64        GRand Unified Bootloader (common files)
ii  grub-efi-amd64                                        2.02~beta2-9ubuntu1.7                               amd64        GRand Unified Bootloader, version 2 (EFI-AMD64 version)
ii  grub-efi-amd64-bin                                    2.02~beta2-9ubuntu1.7                               amd64        GRand Unified Bootloader, version 2 (EFI-AMD64 binaries)
ii  grub-efi-amd64-signed                                 1.34.8+2.02~beta2-9ubuntu1.7                        amd64        GRand Unified Bootloader, version 2 (EFI-AMD64 version, signed)
ii  grub2-common                                          2.02~beta2-9ubuntu1.7                               amd64        GRand Unified Bootloader (common files for version 2)
ii  gsettings-desktop-schemas                             3.10.1-0ubuntu1                                     all          GSettings deskop-wide schemas
ii  gsettings-ubuntu-schemas                              0.0.1+14.04.20140401-0ubuntu1                       all          GSettings deskop-wide schemas for Ubuntu
ii  gsfonts                                               1:8.11+urwcyr1.0.7~pre44-4.2ubuntu1                 all          Fonts for the Ghostscript interpreter(s)
ii  gstreamer0.10-alsa:amd64                              0.10.36-1.1ubuntu2                                  amd64        GStreamer plugin for ALSA
ii  gstreamer0.10-fluendo-mp3:amd64                       0.10.23.debian-3                                    amd64        Fluendo mp3 decoder GStreamer 0.10 plugin
ii  gstreamer0.10-nice:amd64                              0.1.4-1                                             amd64        ICE library (GStreamer 0.10 plugin)
ii  gstreamer0.10-plugins-base:amd64                      0.10.36-1.1ubuntu2                                  amd64        GStreamer plugins from the "base" set
ii  gstreamer0.10-plugins-base-apps                       0.10.36-1.1ubuntu2                                  amd64        GStreamer helper programs from the "base" set
ii  gstreamer0.10-plugins-good:amd64                      0.10.31-3+nmu1ubuntu5                               amd64        GStreamer plugins from the "good" set
ii  gstreamer0.10-pulseaudio:amd64                        0.10.31-3+nmu1ubuntu5                               amd64        GStreamer plugin for PulseAudio
ii  gstreamer0.10-tools                                   0.10.36-1.2ubuntu3                                  amd64        Tools for use with GStreamer
ii  gstreamer0.10-x:amd64                                 0.10.36-1.1ubuntu2                                  amd64        GStreamer plugins for X11 and Pango
ii  gstreamer1.0-alsa:amd64                               1.2.4-1~ubuntu2                                     amd64        GStreamer plugin for ALSA
ii  gstreamer1.0-clutter                                  2.0.8-1build1                                       amd64        Clutter PLugin for GStreamer 1.0
ii  gstreamer1.0-fluendo-mp3:amd64                        0.10.23.debian-3                                    amd64        Fluendo mp3 decoder GStreamer 1.0 plugin
ii  gstreamer1.0-nice:amd64                               0.1.4-1                                             amd64        ICE library (GStreamer plugin)
ii  gstreamer1.0-plugins-base:amd64                       1.2.4-1~ubuntu2                                     amd64        GStreamer plugins from the "base" set
ii  gstreamer1.0-plugins-base-apps                        1.2.4-1~ubuntu2                                     amd64        GStreamer helper programs from the "base" set
ii  gstreamer1.0-plugins-good:amd64                       1.2.4-1~ubuntu1                                     amd64        GStreamer plugins from the "good" set
ii  gstreamer1.0-pulseaudio:amd64                         1.2.4-1~ubuntu1                                     amd64        GStreamer plugin for PulseAudio
ii  gstreamer1.0-tools                                    1.2.4-0ubuntu1                                      amd64        Tools for use with GStreamer
ii  gstreamer1.0-x:amd64                                  1.2.4-1~ubuntu2                                     amd64        GStreamer plugins for X11 and Pango
ii  gtk2-engines-murrine:amd64                            0.98.2-0ubuntu2                                     amd64        cairo-based gtk+-2.0 theme engine
ii  gtk3-engines-unico:amd64                              1.0.3+14.04.20140109-0ubuntu1                       amd64        Unico Gtk+ 3 theme engine
ii  gucharmap                                             1:3.10.1-0ubuntu2                                   amd64        Unicode character picker and font browser
ii  guile-2.0-libs                                        2.0.9+1-1ubuntu1                                    amd64        Core Guile libraries
ii  gvfs:amd64                                            1.20.3-0ubuntu1.2                                   amd64        userspace virtual filesystem - GIO module
ii  gvfs-backends                                         1.20.3-0ubuntu1.2                                   amd64        userspace virtual filesystem - backends
ii  gvfs-bin                                              1.20.3-0ubuntu1.2                                   amd64        userspace virtual filesystem - binaries
ii  gvfs-common                                           1.20.3-0ubuntu1.2                                   all          userspace virtual filesystem - common data files
ii  gvfs-daemons                                          1.20.3-0ubuntu1.2                                   amd64        userspace virtual filesystem - servers
ii  gvfs-fuse                                             1.20.3-0ubuntu1.2                                   amd64        userspace virtual filesystem - fuse server
ii  gvfs-libs:amd64                                       1.20.3-0ubuntu1.2                                   amd64        userspace virtual filesystem - private libraries
ii  gwakeonlan                                            0.5.1-1                                             all          wakes up your machines using Wake on LAN
ii  gzip                                                  1.6-3ubuntu1                                        amd64        GNU compression utilities
ii  hardening-includes                                    2.5ubuntu2.1                                        all          Makefile for enabling compiler flags for security hardening
ii  hdapsd                                                1:20090401-2                                        amd64        HDAPS daemon for IBM/Lenovo ThinkPads and Apple iBooks/PowerBooks
ii  hdparm                                                9.43-1ubuntu3                                       amd64        tune hard disk parameters for high performance
ii  heirloom-mailx                                        12.5-2+deb7u1build0.14.04.1                         amd64        feature-rich BSD mail(1)
ii  hicolor-icon-theme                                    0.13-1                                              all          default fallback theme for FreeDesktop.org icon themes
ii  hostname                                              3.15ubuntu1                                         amd64        utility to set/show the host name or domain name
ii  hplip                                                 3.14.3-0ubuntu3.4                                   amd64        HP Linux Printing and Imaging System (HPLIP)
ii  hplip-data                                            3.14.3-0ubuntu3.4                                   all          HP Linux Printing and Imaging - data files
ii  hud                                                   14.04+14.04.20140604-0ubuntu1                       amd64        Backend for the Unity HUD
ii  humanity-icon-theme                                   0.6.5                                               all          Humanity Icon theme
ii  hunspell-en-us                                        20070829-4ubuntu3                                   all          English_american dictionary for hunspell
ii  hwdata                                                0.249-1                                             all          hardware identification / configuration data
ii  hyphen-en-us                                          2.8.6-3ubuntu2                                      all          US English hyphenation patterns for LibreOffice/OpenOffice.org
ii  i915-3.19-3.13-dkms                                   3.19.1-6                                            all          Intel i915 video drivers from the mainline kernel,
ii  ibus                                                  1.5.5-1ubuntu3.2                                    amd64        Intelligent Input Bus - core
ii  ibus-gtk:amd64                                        1.5.5-1ubuntu3.2                                    amd64        Intelligent Input Bus - GTK+2 support
ii  ibus-gtk3:amd64                                       1.5.5-1ubuntu3.2                                    amd64        Intelligent Input Bus - GTK+3 support
ii  ibus-pinyin                                           1.5.0-1ubuntu1                                      amd64        Pinyin engine for IBus
ii  ibus-table                                            1.5.0.is.1.5.0.20130419-2                           all          table engine for IBus
ii  icedtea-6-jre-cacao:amd64                             6b38-1.13.10-0ubuntu0.14.04.1                       amd64        Alternative JVM for OpenJDK, using Cacao
ii  icedtea-6-jre-jamvm:amd64                             6b38-1.13.10-0ubuntu0.14.04.1                       amd64        Alternative JVM for OpenJDK, using JamVM
ii  icedtea-6-plugin:amd64                                1.5.3-0ubuntu0.14.04.1                              amd64        web browser plugin based on OpenJDK and IcedTea to execute Java applets
ii  icedtea-netx:amd64                                    1.5.3-0ubuntu0.14.04.1                              amd64        NetX - implementation of the Java Network Launching Protocol (JNLP)
ii  icedtea-netx-common                                   1.5.3-0ubuntu0.14.04.1                              all          NetX - implementation of the Java Network Launching Protocol (JNLP)
ii  ifupdown                                              0.7.47.2ubuntu4.3                                   amd64        high level tools to configure network interfaces
ii  im-config                                             0.24-1ubuntu4.2                                     all          Input method configuration framework
ii  indicator-application                                 12.10.1+14.04.20140407-0ubuntu1                     amd64        Application Indicators
ii  indicator-appmenu                                     13.01.0+14.04.20140404-0ubuntu1                     amd64        Indicator for application menus.
ii  indicator-bluetooth                                   0.0.6+14.04.20140207-0ubuntu2                       amd64        System bluetooth indicator.
ii  indicator-datetime                                    13.10.0+14.04.20140415.3-0ubuntu1                   amd64        Simple clock
ii  indicator-keyboard                                    0.0.0+14.04.20140410.1-0ubuntu1                     amd64        Keyboard indicator
ii  indicator-messages                                    13.10.1+14.04.20140410-0ubuntu1                     amd64        indicator that collects messages that need a response
ii  indicator-power                                       12.10.6+14.04.20140411-0ubuntu1                     amd64        Indicator showing power state.
ii  indicator-printers                                    0.1.7+14.04.20140527-0ubuntu1                       amd64        indicator showing active print jobs
ii  indicator-session                                     12.10.5+14.04.20151021.1-0ubuntu1                   amd64        indicator showing session management, status and user switching
ii  indicator-sound                                       12.10.2+14.04.20140401-0ubuntu1                     amd64        System sound indicator.
ii  info                                                  5.2.0.dfsg.1-2                                      amd64        Standalone GNU Info documentation browser
ii  init-system-helpers                                   1.14                                                all          helper tools for all init systems
ii  initramfs-tools                                       0.103ubuntu4.2                                      all          tools for generating an initramfs
ii  initramfs-tools-bin                                   0.103ubuntu4.2                                      amd64        binaries used by initramfs-tools
ii  initscripts                                           2.88dsf-41ubuntu6.3                                 amd64        scripts for initializing and shutting down the system
ii  inputattach                                           1:1.4.7-1                                           amd64        utility to connect serial-attached peripherals to the input subsystem
ii  insserv                                               1.14.0-5ubuntu2                                     amd64        boot sequence organizer using LSB init.d script dependency information
ii  install-info                                          5.2.0.dfsg.1-2                                      amd64        Manage installed documentation in info format
ii  intel-gpu-tools                                       1.3-0ubuntu2.1                                      amd64        tools for debugging the Intel graphics driver
ii  intltool                                              0.50.2-2                                            all          Utility scripts for internationalizing XML
ii  intltool-debian                                       0.35.0+20060710.1                                   all          Help i18n of RFC822 compliant config files
ii  iproute                                               1:3.12.0-2ubuntu1                                   all          transitional dummy package for iproute2
ii  iproute2                                              3.12.0-2ubuntu1                                     amd64        networking and traffic control tools
ii  iptables                                              1.4.21-1ubuntu1                                     amd64        administration tools for packet filtering and NAT
ii  iputils-arping                                        3:20121221-4ubuntu1.1                               amd64        Tool to send ICMP echo requests to an ARP address
ii  iputils-ping                                          3:20121221-4ubuntu1.1                               amd64        Tools to test the reachability of network hosts
ii  iputils-tracepath                                     3:20121221-4ubuntu1.1                               amd64        Tools to trace the network path to a remote host
ii  irqbalance                                            1.0.6-2ubuntu0.14.04.4                              amd64        Daemon to balance interrupts for SMP systems
ii  isc-dhcp-client                                       4.2.4-7ubuntu12.4                                   amd64        ISC DHCP client
ii  isc-dhcp-common                                       4.2.4-7ubuntu12.4                                   amd64        common files used by all the isc-dhcp* packages
ii  iso-codes                                             3.52-1                                              all          ISO language, territory, currency, script codes and their translations
ii  iw                                                    3.4-1                                               amd64        tool for configuring Linux wireless devices
ii  java-common                                           0.51                                                all          Base of all Java packages
ii  javascript-common                                     11                                                  all          Base support for JavaScript library packages
ii  kbd                                                   1.15.5-1ubuntu1                                     amd64        Linux console font and keytable utilities
ii  kerneloops-daemon                                     0.12+git20090217-3ubuntu8                           amd64        kernel oops tracker
ii  keyboard-configuration                                1.70ubuntu8                                         all          system-wide keyboard preferences
ii  keyutils                                              1.5.6-1                                             amd64        Linux Key Management Utilities
ii  kittyhawk-meta                                        1.6kittyhawk9                                       all          Meta package for the OEM mainstreams image.
ii  klibc-utils                                           2.0.3-0ubuntu1                                      amd64        small utilities built with klibc for early boot
ii  kmod                                                  15-0ubuntu6                                         amd64        tools for managing Linux kernel modules
ii  kpartx                                                0.4.9-3ubuntu7.9                                    amd64        create device mappings for partitions
ii  kpartx-boot                                           0.4.9-3ubuntu7.9                                    all          Provides kpartx during boot
ii  krb5-locales                                          1.12+dfsg-2ubuntu5.2                                all          Internationalization support for MIT Kerberos
ii  landscape-client-ui-install                           14.12-0ubuntu0.14.04                                amd64        The Landscape administration system client - UI installer
ii  language-pack-en                                      1:14.04+20150219                                    all          translation updates for language English
ii  language-pack-en-base                                 1:14.04+20150219                                    all          translations for language English
ii  language-pack-gnome-en                                1:14.04+20150219                                    all          GNOME translation updates for language English
ii  language-pack-gnome-en-base                           1:14.04+20150219                                    all          GNOME translations for language English
ii  language-selector-common                              0.129.3                                             all          Language selector for Ubuntu
ii  language-selector-gnome                               0.129.3                                             all          Language selector for Ubuntu
ii  laptop-detect                                         0.13.7ubuntu2                                       amd64        attempt to detect a laptop
ii  less                                                  458-2                                               amd64        pager program similar to more
ii  lib32gcc1                                             1:4.9.3-0ubuntu4                                    amd64        GCC support library (32 bit Version)
ii  lib32z1                                               1:1.2.8.dfsg-1ubuntu1                               amd64        compression library - 32 bit runtime
ii  libaa1:amd64                                          1.4p5-41                                            amd64        ASCII art library
ii  libaccount-plugin-1.0-0                               0.1.7~+14.04.20140211.2-0ubuntu4                    amd64        libaccount-plugin for Unity Control Center
ii  libaccount-plugin-generic-oauth                       0.11+14.04.20140409.1-0ubuntu2                      amd64        GNOME Control Center account plugin for single signon - generic OAuth
ii  libaccount-plugin-google                              0.11+14.04.20140409.1-0ubuntu2                      amd64        GNOME Control Center account plugin for single signon - Google Auth
ii  libaccounts-glib0:amd64                               1.15+14.04.20131126.2-0ubuntu3                      amd64        library for single signon
ii  libaccounts-qt5-1                                     1.11+14.04.20140410.1-0ubuntu1                      amd64        QT library for single sign on
ii  libaccountsservice0:amd64                             0.6.35-0ubuntu7.2                                   amd64        query and manipulate user account information - shared libraries
ii  libacl1:amd64                                         2.2.52-1                                            amd64        Access control list shared library
ii  libalgorithm-diff-perl                                1.19.02-3                                           all          module to find differences between files
ii  libalgorithm-diff-xs-perl                             0.04-2build4                                        amd64        module to find differences between files (XS accelerated)
ii  libalgorithm-merge-perl                               0.08-2                                              all          Perl module for three-way merge of textual data
ii  libandroid-properties1                                0.1.0+git20131207+e452e83-0ubuntu12                 amd64        Library to provide access to get, set and list Android properties
ii  libapparmor-perl                                      2.8.95~2430-0ubuntu5.3                              amd64        AppArmor library Perl bindings
ii  libapparmor1:amd64                                    2.8.95~2430-0ubuntu5.3                              amd64        changehat AppArmor library
ii  libappindicator1                                      12.10.1+13.10.20130920-0ubuntu4.1                   amd64        Application Indicators
ii  libappindicator3-1                                    12.10.1+13.10.20130920-0ubuntu4.1                   amd64        Application Indicators
ii  libapt-inst1.5:amd64                                  1.0.1ubuntu2.11                                     amd64        deb package format runtime library
ii  libapt-pkg-perl                                       0.1.29build1                                        amd64        Perl interface to libapt-pkg
ii  libapt-pkg4.12:amd64                                  1.0.1ubuntu2.11                                     amd64        package management runtime library
ii  libarchive-extract-perl                               0.70-1                                              all          generic archive extracting module
ii  libarchive-zip-perl                                   1.30-7                                              all          Perl module for manipulation of ZIP archives
ii  libarchive13:amd64                                    3.1.2-7ubuntu2.1                                    amd64        Multi-format archive and compression library (shared library)
ii  libart-2.0-2:amd64                                    2.3.21-2                                            amd64        Library of functions for 2D graphics - runtime files
ii  libasan0:amd64                                        4.8.4-2ubuntu1~14.04.1                              amd64        AddressSanitizer -- a fast memory error detector
ii  libasn1-8-heimdal:amd64                               1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - ASN.1 library
ii  libasound2:amd64                                      1.0.27.2-3ubuntu7                                   amd64        shared library for ALSA applications
ii  libasound2-data                                       1.0.27.2-3ubuntu7                                   all          Configuration files and profiles for ALSA drivers
ii  libasound2-plugins:amd64                              1.0.27-2ubuntu2                                     amd64        ALSA library additional plugins
ii  libaspell15                                           0.60.7~20110707-1ubuntu1                            amd64        GNU Aspell spell-checker runtime library
ii  libasprintf-dev:amd64                                 0.18.3.1-1ubuntu3                                   amd64        GNU Internationalization library development files
ii  libasprintf0c2:amd64                                  0.18.3.1-1ubuntu3                                   amd64        GNU library to use fprintf and friends in C++
ii  libassuan0:amd64                                      2.1.1-1ubuntu1                                      amd64        IPC library for the GnuPG components
ii  libasyncns0:amd64                                     0.8-4ubuntu2                                        amd64        Asynchronous name service query library
ii  libatasmart4:amd64                                    0.19-3                                              amd64        ATA S.M.A.R.T. reading and parsing library
ii  libatk-adaptor:amd64                                  2.10.2-2ubuntu1                                     amd64        AT-SPI 2 toolkit bridge
ii  libatk-bridge2.0-0:amd64                              2.10.2-2ubuntu1                                     amd64        AT-SPI 2 toolkit bridge - shared library
ii  libatk-wrapper-java                                   0.30.4-4                                            all          ATK implementation for Java using JNI
ii  libatk-wrapper-java-jni:amd64                         0.30.4-4                                            amd64        ATK implementation for Java using JNI (JNI bindings)
ii  libatk1.0-0:amd64                                     2.10.0-2ubuntu2                                     amd64        ATK accessibility toolkit
ii  libatk1.0-data                                        2.10.0-2ubuntu2                                     all          Common files for the ATK accessibility toolkit
ii  libatkmm-1.6-1:amd64                                  2.22.7-2ubuntu1                                     amd64        C++ wrappers for ATK accessibility toolkit (shared libraries)
ii  libatomic1:amd64                                      4.8.4-2ubuntu1~14.04.1                              amd64        support library providing __atomic built-in functions
ii  libatspi2.0-0:amd64                                   2.10.2.is.2.10.1-0ubuntu1                           amd64        Assistive Technology Service Provider Interface - shared library
ii  libattr1:amd64                                        1:2.4.47-1ubuntu1                                   amd64        Extended attribute shared library
ii  libaudio2:amd64                                       1.9.4-1                                             amd64        Network Audio System - shared libraries
ii  libaudit-common                                       1:2.3.2-2ubuntu1                                    all          Dynamic library for security auditing - common files
ii  libaudit1:amd64                                       1:2.3.2-2ubuntu1                                    amd64        Dynamic library for security auditing
ii  libauthen-sasl-perl                                   2.1500-1                                            all          Authen::SASL - SASL Authentication framework
ii  libautodie-perl                                       2.23-1                                              all          Perl pragma to make certain failures fatal
ii  libavahi-client3:amd64                                0.6.31-4ubuntu1                                     amd64        Avahi client library
ii  libavahi-common-data:amd64                            0.6.31-4ubuntu1                                     amd64        Avahi common data files
ii  libavahi-common3:amd64                                0.6.31-4ubuntu1                                     amd64        Avahi common library
ii  libavahi-core7:amd64                                  0.6.31-4ubuntu1                                     amd64        Avahi's embeddable mDNS/DNS-SD library
ii  libavahi-glib1:amd64                                  0.6.31-4ubuntu1                                     amd64        Avahi GLib integration library
ii  libavahi-gobject0:amd64                               0.6.31-4ubuntu1                                     amd64        Avahi GObject library
ii  libavc1394-0:amd64                                    0.5.4-2                                             amd64        control IEEE 1394 audio/video devices
ii  libbamf3-2:amd64                                      0.5.1+14.04.20140409-0ubuntu1                       amd64        Window matching library - shared library
ii  libbind9-90                                           1:9.9.5.dfsg-3ubuntu0.7                             amd64        BIND9 Shared Library used by BIND
ii  libbison-dev:amd64                                    2:3.0.2.dfsg-2                                      amd64        YACC-compatible parser generator - development library
ii  libblkid1:amd64                                       2.20.1-5.1ubuntu20.7                                amd64        block device id library
ii  libbluetooth3:amd64                                   4.101-0ubuntu13.1                                   amd64        Library to use the BlueZ Linux Bluetooth stack
ii  libboost-date-time1.54.0:amd64                        1.54.0-4ubuntu3.1                                   amd64        set of date-time libraries based on generic programming concepts
ii  libboost-iostreams1.54.0:amd64                        1.54.0-4ubuntu3.1                                   amd64        Boost.Iostreams Library
ii  libboost-system1.54.0:amd64                           1.54.0-4ubuntu3.1                                   amd64        Operating system (e.g. diagnostics support) library
ii  libbrasero-media3-1                                   3.10.0-0ubuntu1                                     amd64        CD/DVD burning library for GNOME - runtime
ii  libbrlapi0.6:amd64                                    5.0-2ubuntu2                                        amd64        braille display access via BRLTTY - shared library
ii  libbsd0:amd64                                         0.6.0-2ubuntu1                                      amd64        utility functions from BSD systems - shared library
ii  libburn4                                              1.3.4-0ubuntu1                                      amd64        library to provide CD/DVD writing functions
ii  libbz2-1.0:amd64                                      1.0.6-5                                             amd64        high-quality block-sorting file compressor library - runtime
ii  libc-bin                                              2.19-0ubuntu6.7                                     amd64        Embedded GNU C Library: Binaries
ii  libc-dev-bin                                          2.19-0ubuntu6.7                                     amd64        Embedded GNU C Library: Development binaries
ii  libc6:amd64                                           2.19-0ubuntu6.7                                     amd64        Embedded GNU C Library: Shared libraries
ii  libc6-dbg:amd64                                       2.19-0ubuntu6.7                                     amd64        Embedded GNU C Library: detached debugging symbols
ii  libc6-dev:amd64                                       2.19-0ubuntu6.7                                     amd64        Embedded GNU C Library: Development Libraries and Header Files
ii  libc6-i386                                            2.19-0ubuntu6.7                                     amd64        Embedded GNU C Library: 32-bit shared libraries for AMD64
ii  libcaca0:amd64                                        0.99.beta18-1ubuntu5                                amd64        colour ASCII art library
ii  libcairo-gobject2:amd64                               1.13.0~20140204-0ubuntu1.1                          amd64        The Cairo 2D vector graphics library (GObject library)
ii  libcairo-perl                                         1.104-1                                             amd64        Perl interface to the Cairo graphics library
ii  libcairo2:amd64                                       1.13.0~20140204-0ubuntu1.1                          amd64        The Cairo 2D vector graphics library
ii  libcairomm-1.0-1:amd64                                1.10.0-1ubuntu3                                     amd64        C++ wrappers for Cairo (shared libraries)
ii  libcamel-1.2-45                                       3.10.4-0ubuntu1.5                                   amd64        Evolution MIME message handling library
ii  libcanberra-gtk-module:amd64                          0.30-0ubuntu3                                       amd64        translates GTK+ widgets signals to event sounds
ii  libcanberra-gtk0:amd64                                0.30-0ubuntu3                                       amd64        GTK+ helper for playing widget event sounds with libcanberra
ii  libcanberra-gtk3-0:amd64                              0.30-0ubuntu3                                       amd64        GTK+ 3.0 helper for playing widget event sounds with libcanberra
ii  libcanberra-gtk3-module:amd64                         0.30-0ubuntu3                                       amd64        translates GTK3 widgets signals to event sounds
ii  libcanberra-pulse:amd64                               0.30-0ubuntu3                                       amd64        PulseAudio backend for libcanberra
ii  libcanberra0:amd64                                    0.30-0ubuntu3                                       amd64        simple abstract interface for playing event sounds
ii  libcap-ng0                                            0.7.3-1ubuntu2                                      amd64        An alternate POSIX capabilities library
ii  libcap2:amd64                                         1:2.24-0ubuntu2                                     amd64        support for getting/setting POSIX.1e capabilities
ii  libcap2-bin                                           1:2.24-0ubuntu2                                     amd64        basic utility programs for using capabilities
ii  libcdio-cdda1                                         0.83-4.1ubuntu1                                     amd64        library to read and control digital audio CDs
ii  libcdio-paranoia1                                     0.83-4.1ubuntu1                                     amd64        library to read digital audio CDs with error correction
ii  libcdio13                                             0.83-4.1ubuntu1                                     amd64        library to read and control CD-ROM
ii  libcdparanoia0:amd64                                  3.10.2+debian-11                                    amd64        audio extraction tool for sampling CDs (library)
ii  libcdr-0.0-0                                          0.0.15-1ubuntu1                                     amd64        library for reading and converting Corel DRAW files
ii  libcgmanager0:amd64                                   0.24-0ubuntu7.5                                     amd64        Central cgroup manager daemon (client library)
ii  libcheese-gtk23:amd64                                 3.10.2-0ubuntu2                                     amd64        tool to take pictures and videos from your webcam - widgets
ii  libcheese7:amd64                                      3.10.2-0ubuntu2                                     amd64        tool to take pictures and videos from your webcam - base library
ii  libclass-accessor-perl                                0.34-1                                              all          Perl module that automatically generates accessors
ii  libclick-0.4-0:amd64                                  0.4.21.1ubuntu0.2                                   amd64        run-time Click package management library
ii  libclone-perl                                         0.36-1                                              amd64        module for recursively copying Perl datatypes
ii  libcloog-isl4:amd64                                   0.18.2-1                                            amd64        Chunky Loop Generator (runtime library)
ii  libclucene-contribs1:amd64                            2.3.3.4-4build1                                     amd64        language specific text analyzers (runtime)
ii  libclucene-core1:amd64                                2.3.3.4-4build1                                     amd64        core library for full-featured text search engine (runtime)
ii  libclutter-1.0-0:amd64                                1.16.4-0ubuntu2                                     amd64        Open GL based interactive canvas library
ii  libclutter-1.0-common                                 1.16.4-0ubuntu2                                     all          Open GL based interactive canvas library (common files)
ii  libclutter-gst-2.0-0:amd64                            2.0.8-1build1                                       amd64        Open GL based interactive canvas library GStreamer elements
ii  libclutter-gtk-1.0-0:amd64                            1.4.4-3ubuntu2.2                                    amd64        Open GL based interactive canvas library GTK+ widget
ii  libcmis-0.4-4                                         0.4.1-3ubuntu4                                      amd64        CMIS protocol client library
ii  libcogl-common                                        1.16.2-1                                            all          Object oriented GL/GLES Abstraction/Utility Layer (common files)
ii  libcogl-pango15:amd64                                 1.16.2-1                                            amd64        Object oriented GL/GLES Abstraction/Utility Layer
ii  libcogl15:amd64                                       1.16.2-1                                            amd64        Object oriented GL/GLES Abstraction/Utility Layer
ii  libcolamd2.8.0:amd64                                  1:4.2.1-3ubuntu1                                    amd64        column approximate minimum degree ordering library for sparse matrices
ii  libcolord1:amd64                                      1.0.6-1                                             amd64        system service to manage device colour profiles -- runtime
ii  libcolorhug1:amd64                                    1.0.6-1                                             amd64        library to access the ColorHug colourimeter -- runtime
ii  libcolumbus1:amd64                                    1.1.0+14.04.20140325.3-0ubuntu1                     amd64        error tolerant matching engine - shared library
ii  libcolumbus1-common                                   1.1.0+14.04.20140325.3-0ubuntu1                     all          error tolerant matching engine - common files
ii  libcomerr2:amd64                                      1.42.9-3ubuntu1.3                                   amd64        common error description library
ii  libcompizconfig0                                      1:0.9.11.3+14.04.20150313-0ubuntu1                  amd64        Settings library for plugins - OpenCompositing Project
ii  libcontent-hub0:amd64                                 0.0+14.04.20140415-0ubuntu1                         amd64        content sharing/picking library
ii  libcrack2:amd64                                       2.9.1-1build1                                       amd64        pro-active password checker library
ii  libcroco3:amd64                                       0.6.8-2ubuntu1                                      amd64        Cascading Style Sheet (CSS) parsing and manipulation toolkit
ii  libcrypt-passwdmd5-perl                               1.3-10                                              all          interoperable MD5-based crypt() for perl
ii  libcryptsetup4                                        2:1.6.1-1ubuntu1                                    amd64        disk encryption support - shared library
ii  libcups2:amd64                                        1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - Core library
ii  libcupscgi1:amd64                                     1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - CGI library
ii  libcupsfilters1:amd64                                 1.0.52-0ubuntu1.7                                   amd64        OpenPrinting CUPS Filters - Shared library
ii  libcupsimage2:amd64                                   1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - Raster image library
ii  libcupsmime1:amd64                                    1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - MIME library
ii  libcupsppdc1:amd64                                    1.7.2-0ubuntu1.7                                    amd64        Common UNIX Printing System(tm) - PPD manipulation library
ii  libcurl3:amd64                                        7.35.0-1ubuntu2.6                                   amd64        easy-to-use client-side URL transfer library (OpenSSL flavour)
ii  libcurl3-gnutls:amd64                                 7.35.0-1ubuntu2.6                                   amd64        easy-to-use client-side URL transfer library (GnuTLS flavour)
ii  libcwidget3                                           0.5.16-3.5ubuntu1                                   amd64        high-level terminal interface library for C++ (runtime files)
ii  libdaemon0                                            0.14-2ubuntu1                                       amd64        lightweight C library for daemons - runtime library
ii  libdatrie1:amd64                                      0.2.8-1                                             amd64        Double-array trie library
ii  libdb5.3:amd64                                        5.3.28-3ubuntu3                                     amd64        Berkeley v5.3 Database Libraries [runtime]
ii  libdbus-1-3:amd64                                     1.6.18-0ubuntu4.3                                   amd64        simple interprocess messaging system (library)
ii  libdbus-glib-1-2:amd64                                0.100.2-1                                           amd64        simple interprocess messaging system (GLib-based shared library)
ii  libdbusmenu-glib4:amd64                               12.10.3+14.04.20140612-0ubuntu1                     amd64        library for passing menus over DBus
ii  libdbusmenu-gtk3-4:amd64                              12.10.3+14.04.20140612-0ubuntu1                     amd64        library for passing menus over DBus - GTK+ version
ii  libdbusmenu-gtk4:amd64                                12.10.3+14.04.20140612-0ubuntu1                     amd64        library for passing menus over DBus - GTK+ version
ii  libdbusmenu-qt2:amd64                                 0.9.3+14.04.20140314-0ubuntu1                       amd64        Qt implementation of the DBusMenu protocol
ii  libdbusmenu-qt5:amd64                                 0.9.3+14.04.20140314-0ubuntu1                       amd64        Qt5 implementation of the DBusMenu protocol
ii  libdconf1:amd64                                       0.20.0-1                                            amd64        simple configuration storage system - runtime library
ii  libdebconfclient0:amd64                               0.187ubuntu1                                        amd64        Debian Configuration Management System (C-implementation library)
ii  libdebian-installer4:amd64                            0.88ubuntu5.2                                       amd64        Library of common debian-installer functions
ii  libdecoration0                                        1:0.9.11.3+14.04.20150313-0ubuntu1                  amd64        Compiz window decoration library
ii  libdee-1.0-4:amd64                                    1.2.7+14.04.20140324-0ubuntu1                       amd64        model to synchronize multiple instances over DBus - shared lib
ii  libdee-qt5-3:amd64                                    3.3+14.04.20140317-0ubuntu1                         amd64        Qt5 binding for Dee - shared library
ii  libdevmapper-event1.02.1:amd64                        2:1.02.77-6ubuntu2                                  amd64        Linux Kernel Device Mapper event support library
ii  libdevmapper1.02.1:amd64                              2:1.02.77-6ubuntu2                                  amd64        Linux Kernel Device Mapper userspace library
ii  libdigest-hmac-perl                                   1.03+dfsg-1                                         all          module for creating standard message integrity checks
ii  libdjvulibre-text                                     3.5.25.4-3                                          all          Linguistic support files for libdjvulibre
ii  libdjvulibre21:amd64                                  3.5.25.4-3                                          amd64        Runtime support for the DjVu image format
ii  libdmapsharing-3.0-2                                  2.9.24-0ubuntu1                                     amd64        DMAP client and server library - runtime
ii  libdmraid1.0.0.rc16                                   1.0.0.rc16-4.2ubuntu3                               amd64        Device-Mapper Software RAID support tool - shared library
ii  libdns100                                             1:9.9.5.dfsg-3ubuntu0.7                             amd64        DNS Shared Library used by BIND
ii  libdotconf0:amd64                                     1.3-0ubuntu2                                        amd64        Configuration file parser library - runtime files
ii  libdpkg-perl                                          1.17.5ubuntu5.5                                     all          Dpkg perl modules
ii  libdrm-intel1:amd64                                   2.4.64-1~ubuntu14.04.1                              amd64        Userspace interface to intel-specific kernel DRM services -- runtime
ii  libdrm-nouveau2:amd64                                 2.4.64-1~ubuntu14.04.1                              amd64        Userspace interface to nouveau-specific kernel DRM services -- runtime
ii  libdrm-radeon1:amd64                                  2.4.64-1~ubuntu14.04.1                              amd64        Userspace interface to radeon-specific kernel DRM services -- runtime
ii  libdrm2:amd64                                         2.4.64-1~ubuntu14.04.1                              amd64        Userspace interface to kernel DRM services -- runtime
ii  libdv4:amd64                                          1.0.0-6                                             amd64        software library for DV format digital video (runtime lib)
ii  libebackend-1.2-7                                     3.10.4-0ubuntu1.5                                   amd64        Utility library for evolution data servers
ii  libebook-1.2-14                                       3.10.4-0ubuntu1.5                                   amd64        Client library for evolution address books
ii  libebook-contacts-1.2-0                               3.10.4-0ubuntu1.5                                   amd64        Client library for evolution contacts books
ii  libecal-1.2-16                                        3.10.4-0ubuntu1.5                                   amd64        Client library for evolution calendars
ii  libecryptfs0                                          104-0ubuntu1.14.04.4                                amd64        ecryptfs cryptographic filesystem (library)
ii  libedata-book-1.2-20                                  3.10.4-0ubuntu1.5                                   amd64        Backend library for evolution address books
ii  libedata-cal-1.2-23                                   3.10.4-0ubuntu1.5                                   amd64        Backend library for evolution calendars
ii  libedataserver-1.2-18                                 3.10.4-0ubuntu1.5                                   amd64        Utility library for evolution data servers
ii  libedit2:amd64                                        3.1-20130712-2                                      amd64        BSD editline and history libraries
ii  libegl1-mesa:amd64                                    10.1.3-0ubuntu0.6                                   amd64        free implementation of the EGL API -- runtime
ii  libegl1-mesa-drivers:amd64                            10.1.3-0ubuntu0.6                                   amd64        free implementation of the EGL API -- hardware drivers
ii  libelf1:amd64                                         0.158-0ubuntu5.2                                    amd64        library to read and write ELF files
ii  libelfg0:amd64                                        0.8.13-5                                            amd64        an ELF object file access library
ii  libemail-valid-perl                                   1.192-1                                             all          Perl module for checking the validity of Internet email addresses
ii  libenchant1c2a:amd64                                  1.6.0-10ubuntu1                                     amd64        Wrapper library for various spell checker engines (runtime libs)
ii  libencode-locale-perl                                 1.03-1                                              all          utility to determine the locale encoding
ii  libept1.4.12:amd64                                    1.0.12                                              amd64        High-level library for managing Debian package information
ii  libespeak1:amd64                                      1.47.11-1ubuntu1                                    amd64        Multi-lingual software speech synthesizer: shared library
ii  libestr0                                              0.1.9-0ubuntu2                                      amd64        Helper functions for handling strings (lib)
ii  libevdocument3-4                                      3.10.3-0ubuntu10.2                                  amd64        Document (PostScript, PDF) rendering library
ii  libevent-2.0-5:amd64                                  2.0.21-stable-1ubuntu1.14.04.1                      amd64        Asynchronous event notification library
ii  libevview3-3                                          3.10.3-0ubuntu10.2                                  amd64        Document (PostScript, PDF) rendering library - Gtk+ widgets
ii  libexempi3:amd64                                      2.2.1-1ubuntu1                                      amd64        library to parse XMP metadata (Library)
ii  libexif12:amd64                                       0.6.21-1ubuntu1                                     amd64        library to parse EXIF files
ii  libexiv2-12                                           0.23-1ubuntu2                                       amd64        EXIF/IPTC metadata manipulation library
ii  libexpat1:amd64                                       2.1.0-4ubuntu1.1                                    amd64        XML parsing C library - runtime library
ii  libexttextcat-2.0-0                                   3.4.3-1ubuntu1                                      amd64        Language detection library
ii  libexttextcat-data                                    3.4.3-1ubuntu1                                      all          Language detection library - data files
ii  libfakeroot:amd64                                     1.20-3ubuntu2                                       amd64        tool for simulating superuser privileges - shared libraries
ii  libfarstream-0.1-0:amd64                              0.1.2-1ubuntu3                                      amd64        Audio/Video communications framework: core library
ii  libfarstream-0.2-2:amd64                              0.2.3-1ubuntu2                                      amd64        Audio/Video communications framework: core library
ii  libffi6:amd64                                         3.1~rc1+r3.0.13-12ubuntu0.1                         amd64        Foreign Function Interface library runtime
ii  libfftw3-single3:amd64                                3.3.3-7ubuntu3                                      amd64        Library for computing Fast Fourier Transforms - Single precision
ii  libfile-basedir-perl                                  0.03-1fakesync1                                     all          Perl module to use the freedesktop basedir specification
ii  libfile-copy-recursive-perl                           0.38-1                                              all          Perl extension for recursively copying files and directories
ii  libfile-desktopentry-perl                             0.07-1                                              all          Perl module to handle freedesktop .desktop files
ii  libfile-fcntllock-perl                                0.14-2build1                                        amd64        Perl module for file locking with fcntl(2)
ii  libfile-listing-perl                                  6.04-1                                              all          module to parse directory listings
ii  libfile-mimeinfo-perl                                 0.22-1                                              all          Perl module to determine file types
ii  libfl-dev:amd64                                       2.5.35-10.1ubuntu2                                  amd64        static library for flex (a fast lexical analyzer generator).
ii  libflac8:amd64                                        1.3.0-2ubuntu0.14.04.1                              amd64        Free Lossless Audio Codec - runtime C library
ii  libfolks-eds25:amd64                                  0.9.5-1ubuntu5                                      amd64        Evolution-data-server backend for libfolks
ii  libfolks-telepathy25:amd64                            0.9.5-1ubuntu5                                      amd64        Telepathy backend for libfolks
ii  libfolks25:amd64                                      0.9.5-1ubuntu5                                      amd64        library to aggregates people into metacontacts
ii  libfont-afm-perl                                      1.20-1                                              all          Font::AFM - Interface to Adobe Font Metrics files
ii  libfontconfig1:amd64                                  2.11.0-0ubuntu4.1                                   amd64        generic font configuration library - runtime
ii  libfontembed1:amd64                                   1.0.52-0ubuntu1.7                                   amd64        OpenPrinting CUPS Filters - Font Embed Shared library
ii  libfontenc1:amd64                                     1:1.1.2-1                                           amd64        X11 font encoding library
ii  libframe6:amd64                                       2.5.0daily13.06.05-0ubuntu1                         amd64        Touch Frame Library
ii  libfreerdp-plugins-standard:amd64                     1.0.2-2ubuntu1                                      amd64        RDP client for Windows Terminal Services (plugins)
ii  libfreerdp1:amd64                                     1.0.2-2ubuntu1                                      amd64        RDP client for Windows Terminal Services (library)
ii  libfreetype6:amd64                                    2.5.2-1ubuntu2.5                                    amd64        FreeType 2 font engine, shared library files
ii  libfribidi0:amd64                                     0.19.6-1                                            amd64        Free Implementation of the Unicode BiDi algorithm
ii  libfriends0:amd64                                     0.1.2+14.04.20131108.1-0ubuntu1                     amd64        Provides an API for accessing social networks
ii  libfs6:amd64                                          2:1.0.5-1                                           amd64        X11 Font Services library
ii  libfuse2:amd64                                        2.9.2-4ubuntu4.14.04.1                              amd64        Filesystem in Userspace (library)
ii  libgail-3-0:amd64                                     3.10.8-0ubuntu1.6                                   amd64        GNOME Accessibility Implementation Library -- shared libraries
ii  libgail-common:amd64                                  2.24.23-0ubuntu1.4                                  amd64        GNOME Accessibility Implementation Library -- common modules
ii  libgail18:amd64                                       2.24.23-0ubuntu1.4                                  amd64        GNOME Accessibility Implementation Library -- shared libraries
ii  libgbm1:amd64                                         10.1.3-0ubuntu0.6                                   amd64        generic buffer management API -- runtime
ii  libgc1c2:amd64                                        1:7.2d-5ubuntu2                                     amd64        conservative garbage collector for C and C++
ii  libgcc-4.8-dev:amd64                                  4.8.4-2ubuntu1~14.04.1                              amd64        GCC support library (development files)
ii  libgcc1:amd64                                         1:4.9.3-0ubuntu4                                    amd64        GCC support library
ii  libgck-1-0:amd64                                      3.10.1-1                                            amd64        Glib wrapper library for PKCS#11 - runtime
ii  libgconf-2-4:amd64                                    3.2.6-0ubuntu2                                      amd64        GNOME configuration database system (shared libraries)
ii  libgconf2.0-cil                                       2.24.2-3                                            all          CLI binding for GConf 2.24
ii  libgcr-3-common                                       3.10.1-1                                            all          Library for Crypto UI related tasks - common files
ii  libgcr-base-3-1:amd64                                 3.10.1-1                                            amd64        Library for Crypto related tasks
ii  libgcr-ui-3-1:amd64                                   3.10.1-1                                            amd64        Library for Crypto UI related tasks
ii  libgcrypt11:amd64                                     1.5.3-2ubuntu4.3                                    amd64        LGPL Crypto library - runtime library
ii  libgd3:amd64                                          2.1.0-3                                             amd64        GD Graphics Library
ii  libgdata-common                                       0.14.1-1                                            all          Library for accessing GData webservices - common data files
ii  libgdata13                                            0.14.1-1                                            amd64        Library for accessing GData webservices - shared libraries
ii  libgdbm3:amd64                                        1.8.3-12build1                                      amd64        GNU dbm database routines (runtime version)
ii  libgdiplus                                            2.11+git20131008.9732566-5ubuntu1                   amd64        interface library for System.Drawing of Mono
ii  libgdk-pixbuf2.0-0:amd64                              2.30.7-0ubuntu1.2                                   amd64        GDK Pixbuf library
ii  libgdk-pixbuf2.0-common                               2.30.7-0ubuntu1.2                                   all          GDK Pixbuf library - data files
ii  libgee-0.8-2:amd64                                    0.10.5-1ubuntu1                                     amd64        GObject based collection library
ii  libgee2:amd64                                         0.6.8-1ubuntu1                                      amd64        GObject based collection library
ii  libgeis1:amd64                                        2.2.16+14.04.20140303-0ubuntu1                      amd64        Gesture engine interface support
ii  libgeoclue0:amd64                                     0.12.99-3ubuntu1                                    amd64        C API for GeoClue
ii  libgeoip1:amd64                                       1.6.0-1                                             amd64        non-DNS IP-to-country resolver library
ii  libgettextpo-dev:amd64                                0.18.3.1-1ubuntu3                                   amd64        GNU Internationalization library development files
ii  libgettextpo0:amd64                                   0.18.3.1-1ubuntu3                                   amd64        GNU Internationalization library
ii  libgexiv2-2:amd64                                     0.10.0-1ubuntu2                                     amd64        GObject-based wrapper around the Exiv2 library
ii  libgif4:amd64                                         4.1.6-11                                            amd64        library for GIF images (library)
ii  libgirepository-1.0-1                                 1.40.0-1ubuntu0.2                                   amd64        Library for handling GObject introspection data (runtime library)
ii  libgl1-mesa-dri:amd64                                 10.1.3-0ubuntu0.6                                   amd64        free implementation of the OpenGL API -- DRI modules
ii  libgl1-mesa-glx:amd64                                 10.1.3-0ubuntu0.6                                   amd64        free implementation of the OpenGL API -- GLX runtime
ii  libglade2-0:amd64                                     1:2.6.4-2                                           amd64        library to load .glade files at runtime
ii  libglade2.0-cil                                       2.12.10-5                                           amd64        CLI binding for the Glade libraries 2.6
ii  libglamor0:amd64                                      0.6.0-0ubuntu4                                      amd64        shared graphics acceleration library based on OpenGL
ii  libglapi-mesa:amd64                                   10.1.3-0ubuntu0.6                                   amd64        free implementation of the GL API -- shared library
ii  libgles2-mesa:amd64                                   10.1.3-0ubuntu0.6                                   amd64        free implementation of the OpenGL|ES 2.x API -- runtime
ii  libglew1.10:amd64                                     1.10.0-3                                            amd64        OpenGL Extension Wrangler - runtime environment
ii  libglewmx1.10:amd64                                   1.10.0-3                                            amd64        OpenGL Extension Wrangler (Multiple Rendering Contexts)
ii  libglib-perl                                          3:1.304-1                                           amd64        interface to the GLib and GObject libraries
ii  libglib2.0-0:amd64                                    2.40.2-0ubuntu1                                     amd64        GLib library of C routines
ii  libglib2.0-bin                                        2.40.2-0ubuntu1                                     amd64        Programs for the GLib library
ii  libglib2.0-cil                                        2.12.10-5                                           amd64        CLI binding for the GLib utility library 2.12
ii  libglib2.0-data                                       2.40.2-0ubuntu1                                     all          Common files for GLib library
ii  libglibmm-2.4-1c2a:amd64                              2.39.93-0ubuntu1                                    amd64        C++ wrapper for the GLib toolkit (shared libraries)
ii  libglu1-mesa:amd64                                    9.0.0-2                                             amd64        Mesa OpenGL utility library (GLU)
ii  libgmime-2.6-0:amd64                                  2.6.20-0ubuntu1                                     amd64        MIME message parser and creator library - runtime
ii  libgmp10:amd64                                        2:5.1.3+dfsg-1ubuntu1                               amd64        Multiprecision arithmetic library
ii  libgnome-bluetooth11                                  3.8.2.1-0ubuntu4.2                                  amd64        GNOME Bluetooth tools - support library
ii  libgnome-control-center1                              1:3.6.3-0ubuntu56.1                                 amd64        utilities to configure the GNOME desktop
ii  libgnome-desktop-3-7                                  3.8.4-0ubuntu3.2                                    amd64        Utility library for loading .desktop files - runtime files
ii  libgnome-keyring-common                               3.8.0-2                                             all          GNOME keyring services library - data files
ii  libgnome-keyring0:amd64                               3.8.0-2                                             amd64        GNOME keyring services library
ii  libgnome-menu-3-0                                     3.10.1-0ubuntu2                                     amd64        GNOME implementation of the freedesktop menu specification
ii  libgnomekbd-common                                    3.6.0-0ubuntu2                                      all          GNOME library to manage keyboard configuration - common files
ii  libgnomekbd8                                          3.6.0-0ubuntu2                                      amd64        GNOME library to manage keyboard configuration - shared library
ii  libgnutls-openssl27:amd64                             2.12.23-12ubuntu2.5                                 amd64        GNU TLS library - OpenSSL wrapper
ii  libgnutls26:amd64                                     2.12.23-12ubuntu2.5                                 amd64        GNU TLS library - runtime library
ii  libgoa-1.0-0b:amd64                                   3.10.3-0ubuntu1                                     amd64        library for GNOME Online Accounts
ii  libgoa-1.0-common                                     3.10.3-0ubuntu1                                     all          library for GNOME Online Accounts - common files
ii  libgomp1:amd64                                        4.8.4-2ubuntu1~14.04.1                              amd64        GCC OpenMP (GOMP) support library
ii  libgpg-error0:amd64                                   1.12-0.2ubuntu1                                     amd64        library for common error values and messages in GnuPG components
ii  libgpgme11:amd64                                      1.4.3-0.1ubuntu5.1                                  amd64        GPGME - GnuPG Made Easy (library)
ii  libgphoto2-6:amd64                                    2.5.3.1-1ubuntu2.2                                  amd64        gphoto2 digital camera library
ii  libgphoto2-l10n                                       2.5.3.1-1ubuntu2.2                                  all          gphoto2 digital camera library - localized messages
ii  libgphoto2-port10:amd64                               2.5.3.1-1ubuntu2.2                                  amd64        gphoto2 digital camera port library
ii  libgpm2:amd64                                         1.20.4-6.1                                          amd64        General Purpose Mouse - shared library
ii  libgpod-common                                        0.8.3-4ubuntu3                                      amd64        common files for libgpod
ii  libgpod4:amd64                                        0.8.3-4ubuntu3                                      amd64        library to read and write songs and artwork to an iPod
ii  libgrail6                                             3.1.0daily13.06.05-0ubuntu1                         amd64        Gesture Recognition And Instantiation Library
ii  libgraphite2-3:amd64                                  1.2.4-1ubuntu1.1                                    amd64        Font rendering engine for Complex Scripts -- library
ii  libgrip0                                              0.3.7+14.04.20140303-0ubuntu1                       amd64        multitouch gestures for GTK+ apps
ii  libgs9                                                9.10~dfsg-0ubuntu10.4                               amd64        interpreter for the PostScript language and for PDF - Library
ii  libgs9-common                                         9.10~dfsg-0ubuntu10.4                               all          interpreter for the PostScript language and for PDF - common files
ii  libgsettings-qt1:amd64                                0.1+14.04.20140408-0ubuntu1                         amd64        Library to access GSettings from Qt
ii  libgssapi-krb5-2:amd64                                1.12+dfsg-2ubuntu5.2                                amd64        MIT Kerberos runtime libraries - krb5 GSS-API Mechanism
ii  libgssapi3-heimdal:amd64                              1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - GSSAPI support library
ii  libgssdp-1.0-3                                        0.14.7-1ubuntu1                                     amd64        GObject-based library for SSDP
ii  libgstreamer-plugins-base0.10-0:amd64                 0.10.36-1.1ubuntu2                                  amd64        GStreamer libraries from the "base" set
ii  libgstreamer-plugins-base1.0-0:amd64                  1.2.4-1~ubuntu2                                     amd64        GStreamer libraries from the "base" set
ii  libgstreamer-plugins-good1.0-0:amd64                  1.2.4-1~ubuntu1                                     amd64        GStreamer development files for libraries from the "good" set
ii  libgstreamer0.10-0:amd64                              0.10.36-1.2ubuntu3                                  amd64        Core GStreamer libraries and elements
ii  libgstreamer1.0-0:amd64                               1.2.4-0ubuntu1                                      amd64        Core GStreamer libraries and elements
ii  libgtk-3-0:amd64                                      3.10.8-0ubuntu1.6                                   amd64        GTK+ graphical user interface library
ii  libgtk-3-bin                                          3.10.8-0ubuntu1.6                                   amd64        programs for the GTK+ graphical user interface library
ii  libgtk-3-common                                       3.10.8-0ubuntu1.6                                   all          common files for the GTK+ graphical user interface library
ii  libgtk2-perl                                          2:1.249-2                                           amd64        Perl interface to the 2.x series of the Gimp Toolkit library
ii  libgtk2.0-0:amd64                                     2.24.23-0ubuntu1.4                                  amd64        GTK+ graphical user interface library
ii  libgtk2.0-bin                                         2.24.23-0ubuntu1.4                                  amd64        programs for the GTK+ graphical user interface library
ii  libgtk2.0-cil                                         2.12.10-5                                           amd64        CLI binding for the GTK+ toolkit 2.12
ii  libgtk2.0-common                                      2.24.23-0ubuntu1.4                                  all          common files for the GTK+ graphical user interface library
ii  libgtkmm-3.0-1:amd64                                  3.10.1-0ubuntu2                                     amd64        C++ wrappers for GTK+ (shared libraries)
ii  libgtksourceview-3.0-1:amd64                          3.10.2-0ubuntu1                                     amd64        shared libraries for the GTK+ syntax highlighting widget
ii  libgtksourceview-3.0-common                           3.10.2-0ubuntu1                                     all          common files for the GTK+ syntax highlighting widget
ii  libgtop2-7                                            2.28.5-2                                            amd64        gtop system monitoring library (shared)
ii  libgtop2-common                                       2.28.5-2                                            all          gtop system monitoring library (common)
ii  libgucharmap-2-90-7                                   1:3.10.1-0ubuntu2                                   amd64        Unicode browser widget library (shared library)
ii  libgudev-1.0-0:amd64                                  1:204-5ubuntu20.18                                  amd64        GObject-based wrapper library for libudev
ii  libgupnp-1.0-4                                        0.20.10-1ubuntu1                                    amd64        GObject-based library for UPnP
ii  libgupnp-igd-1.0-4:amd64                              0.2.2-1                                             amd64        library to handle UPnP IGD port mapping
ii  libgusb2:amd64                                        0.1.6-5                                             amd64        GLib wrapper around libusb1
ii  libgutenprint2                                        5.2.10~pre2-0ubuntu2                                amd64        runtime for the Gutenprint printer driver library
ii  libgweather-3-6                                       3.10.2-0ubuntu2                                     amd64        GWeather shared library
ii  libgweather-common                                    3.10.2-0ubuntu2                                     all          GWeather common files
ii  libgxps2:amd64                                        0.2.2-2ubuntu2                                      amd64        handling and rendering XPS documents (library)
ii  libharfbuzz-icu0:amd64                                0.9.27-1ubuntu1                                     amd64        OpenType text shaping engine ICU backend
ii  libharfbuzz0b:amd64                                   0.9.27-1ubuntu1                                     amd64        OpenType text shaping engine (shared library)
ii  libhcrypto4-heimdal:amd64                             1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - crypto library
ii  libheimbase1-heimdal:amd64                            1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - Base library
ii  libheimntlm0-heimdal:amd64                            1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - NTLM support library
ii  libhpmud0                                             3.14.3-0ubuntu3.4                                   amd64        HP Multi-Point Transport Driver (hpmud) run-time libraries
ii  libhtml-form-perl                                     6.03-1                                              all          module that represents an HTML form element
ii  libhtml-format-perl                                   2.11-1                                              all          module for transforming HTML into various formats
ii  libhtml-parser-perl                                   3.71-1build1                                        amd64        collection of modules that parse HTML text documents
ii  libhtml-tagset-perl                                   3.20-2                                              all          Data tables pertaining to HTML
ii  libhtml-tree-perl                                     5.03-1                                              all          Perl module to represent and create HTML syntax trees
ii  libhttp-cookies-perl                                  6.00-2                                              all          HTTP cookie jars
ii  libhttp-daemon-perl                                   6.01-1                                              all          simple http server class
ii  libhttp-date-perl                                     6.02-1                                              all          module of date conversion routines
ii  libhttp-message-perl                                  6.06-1                                              all          perl interface to HTTP style messages
ii  libhttp-negotiate-perl                                6.00-2                                              all          implementation of content negotiation
ii  libhud2:amd64                                         14.04+14.04.20140604-0ubuntu1                       amd64        library for exporting items to the Unity HUD
ii  libhunspell-1.3-0:amd64                               1.3.2-6ubuntu2.1                                    amd64        spell checker and morphological analyzer (shared library)
ii  libhx509-5-heimdal:amd64                              1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - X509 support library
ii  libhyphen0                                            2.8.6-3ubuntu2                                      amd64        ALTLinux hyphenation library - shared library
ii  libibus-1.0-5:amd64                                   1.5.5-1ubuntu3.2                                    amd64        Intelligent Input Bus - shared library
ii  libical1                                              1.0-0ubuntu1                                        amd64        iCalendar library implementation in C (runtime)
ii  libice6:amd64                                         2:1.0.8-2                                           amd64        X11 Inter-Client Exchange library
ii  libicu52:amd64                                        52.1-3ubuntu0.4                                     amd64        International Components for Unicode
ii  libid3tag0                                            0.15.1b-10ubuntu1                                   amd64        ID3 tag reading library from the MAD project
ii  libidn11:amd64                                        1.28-1ubuntu2                                       amd64        GNU Libidn library, implementation of IETF IDN specifications
ii  libido3-0.1-0:amd64                                   13.10.0+14.04.20151021-0ubuntu1                     amd64        Shared library providing extra gtk menu items for display in
ii  libiec61883-0:amd64                                   1.2.0-0.1ubuntu3                                    amd64        an partial implementation of IEC 61883
ii  libieee1284-3:amd64                                   0.2.11-12                                           amd64        cross-platform library for parallel port access
ii  libijs-0.35                                           0.35-8build1                                        amd64        IJS raster image transport protocol: shared library
ii  libimlib2                                             1.4.6-2                                             amd64        image loading, rendering, saving library
ii  libimobiledevice4:amd64                               1.1.5+git20140313.bafe6a9e-0ubuntu1                 amd64        Library for communicating with the iPhone and iPod Touch
ii  libindicator3-7                                       12.10.2+14.04.20141007.1-0ubuntu1                   amd64        panel indicator applet - shared library
ii  libindicator7                                         12.10.2+14.04.20141007.1-0ubuntu1                   amd64        panel indicator applet - shared library
ii  libio-html-perl                                       1.00-1                                              all          open an HTML file with automatic charset detection
ii  libio-pty-perl                                        1:1.08-1build4                                      amd64        Perl module for pseudo tty IO
ii  libio-socket-inet6-perl                               2.71-1                                              all          object interface for AF_INET6 domain sockets
ii  libio-socket-ssl-perl                                 1.965-1ubuntu1                                      all          Perl module implementing object oriented interface to SSL sockets
ii  libio-string-perl                                     1.08-3                                              all          Emulate IO::File interface for in-core strings
ii  libipc-run-perl                                       0.92-1                                              all          Perl module for running processes
ii  libipc-system-simple-perl                             1.25-2                                              all          Perl module to run commands simply, with detailed diagnostics
ii  libisc95                                              1:9.9.5.dfsg-3ubuntu0.7                             amd64        ISC Shared Library used by BIND
ii  libisccc90                                            1:9.9.5.dfsg-3ubuntu0.7                             amd64        Command Channel Library used by BIND
ii  libisccfg90                                           1:9.9.5.dfsg-3ubuntu0.7                             amd64        Config File Handling Library used by BIND
ii  libisl10:amd64                                        0.12.2-1                                            amd64        manipulating sets and relations of integer points bounded by linear constraints
ii  libisofs6                                             1.3.4-0ubuntu1                                      amd64        library to create ISO9660 images
ii  libitm1:amd64                                         4.8.4-2ubuntu1~14.04.1                              amd64        GNU Transactional Memory Library
ii  libiw30:amd64                                         30~pre9-8ubuntu1                                    amd64        Wireless tools - library
ii  libjack-jackd2-0:amd64                                1.9.9.5+20130622git7de15e7a-1ubuntu1                amd64        JACK Audio Connection Kit (libraries)
ii  libjasper1:amd64                                      1.900.1-14ubuntu3.2                                 amd64        JasPer JPEG-2000 runtime library
ii  libjavascriptcoregtk-3.0-0:amd64                      2.4.8-1ubuntu1~ubuntu14.04.1                        amd64        JavaScript engine library from WebKitGTK+
ii  libjbig0:amd64                                        2.0-2ubuntu4.1                                      amd64        JBIGkit libraries
ii  libjbig2dec0                                          0.11+20120125-1ubuntu1                              amd64        JBIG2 decoder library - shared libraries
ii  libjpeg-turbo8:amd64                                  1.3.0-0ubuntu2                                      amd64        IJG JPEG compliant runtime library.
ii  libjpeg8:amd64                                        8c-2ubuntu8                                         amd64        Independent JPEG Group's JPEG runtime library (dependency package)
ii  libjs-jquery                                          1.7.2+dfsg-2ubuntu1                                 all          JavaScript library for dynamic web applications
ii  libjs-jquery-ui                                       1.10.1+dfsg-1                                       all          JavaScript UI library for dynamic web applications
ii  libjson-c2:amd64                                      0.11-3ubuntu1.2                                     amd64        JSON manipulation library - shared library
ii  libjson-glib-1.0-0:amd64                              0.16.2-1ubuntu1                                     amd64        GLib JSON manipulation library
ii  libjson-glib-1.0-common                               0.16.2-1ubuntu1                                     all          GLib JSON manipulation library (common files)
ii  libjson0:amd64                                        0.11-3ubuntu1.2                                     amd64        JSON manipulation library (transitional package)
ii  libjte1                                               1.19-2                                              amd64        Jigdo Template Export - runtime library
ii  libk5crypto3:amd64                                    1.12+dfsg-2ubuntu5.2                                amd64        MIT Kerberos runtime libraries - Crypto Library
ii  libkeyutils1:amd64                                    1.5.6-1                                             amd64        Linux Key Management Utilities (library)
ii  libklibc                                              2.0.3-0ubuntu1                                      amd64        minimal libc subset for use with initramfs
ii  libkmod2:amd64                                        15-0ubuntu6                                         amd64        libkmod shared library
ii  libkpathsea6                                          2013.20130729.30972-2build3                         amd64        TeX Live: path search library for TeX (runtime part)
ii  libkrb5-26-heimdal:amd64                              1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - libraries
ii  libkrb5-3:amd64                                       1.12+dfsg-2ubuntu5.2                                amd64        MIT Kerberos runtime libraries
ii  libkrb5support0:amd64                                 1.12+dfsg-2ubuntu5.2                                amd64        MIT Kerberos runtime libraries - Support library
ii  liblangtag-common                                     0.5.1-2                                             all          library to access tags for identifying languages -- data
ii  liblangtag1                                           0.5.1-2                                             amd64        library to access tags for identifying languages
ii  liblcms2-2:amd64                                      2.5-0ubuntu4                                        amd64        Little CMS 2 color management library
ii  libldap-2.4-2:amd64                                   2.4.31-1+nmu2ubuntu8.2                              amd64        OpenLDAP libraries
ii  libldb1:amd64                                         1:1.1.16-1ubuntu0.1                                 amd64        LDAP-like embedded database - shared library
ii  liblightdm-gobject-1-0                                1.10.6-0ubuntu1                                     amd64        LightDM GObject client library
ii  liblircclient0                                        0.9.0-0ubuntu5                                      amd64        infra-red remote control support - client library
ii  liblist-moreutils-perl                                0.33-1build3                                        amd64        Perl module with additional list functions not found in List::Util
ii  libllvm3.4:amd64                                      1:3.4-1ubuntu3                                      amd64        Modular compiler and toolchain technologies, runtime library
ii  liblocale-gettext-perl                                1.05-7build3                                        amd64        module using libc functions for internationalization in Perl
ii  liblockfile-bin                                       1.09-6ubuntu1                                       amd64        support binaries for and cli utilities based on liblockfile
ii  liblockfile1:amd64                                    1.09-6ubuntu1                                       amd64        NFS-safe locking library
ii  liblog-message-simple-perl                            0.10-1                                              all          simplified interface to Log::Message
ii  liblouis-data                                         2.5.3-2ubuntu1                                      all          Braille translation library - data
ii  liblouis2:amd64                                       2.5.3-2ubuntu1                                      amd64        Braille translation library - shared libs
ii  libltdl-dev:amd64                                     2.4.2-1.7ubuntu1                                    amd64        A system independent dlopen wrapper for GNU libtool
ii  libltdl7:amd64                                        2.4.2-1.7ubuntu1                                    amd64        A system independent dlopen wrapper for GNU libtool
ii  liblttng-ust-ctl2:amd64                               2.4.0-4ubuntu1                                      amd64        LTTng 2.0 Userspace Tracer (trace control library)
ii  liblttng-ust0:amd64                                   2.4.0-4ubuntu1                                      amd64        LTTng 2.0 Userspace Tracer (tracing libraries)
ii  liblua5.2-0:amd64                                     5.2.3-1                                             amd64        Shared library for the Lua interpreter version 5.2
ii  liblwp-mediatypes-perl                                6.02-1                                              all          module to guess media type for a file or a URL
ii  liblwp-protocol-https-perl                            6.04-2ubuntu0.1                                     all          HTTPS driver for LWP::UserAgent
ii  liblwres90                                            1:9.9.5.dfsg-3ubuntu0.7                             amd64        Lightweight Resolver Library used by BIND
ii  liblzma5:amd64                                        5.1.1alpha+20120614-2ubuntu2                        amd64        XZ-format compression library
ii  liblzo2-2:amd64                                       2.06-1.2ubuntu1.1                                   amd64        data compression library
ii  libmagic1:amd64                                       1:5.14-2ubuntu3.3                                   amd64        File type determination library using "magic" numbers
ii  libmailtools-perl                                     2.12-1                                              all          Manipulate email in perl programs
ii  libmbim-glib0:amd64                                   1.6.0-2ubuntu0.1                                    amd64        Support library to use the MBIM protocol
ii  libmeanwhile1                                         1.0.2-4.1ubuntu1                                    amd64        open implementation of the Lotus Sametime Community Client protocol
ii  libmediainfo0:amd64                                   0.7.67-2ubuntu1                                     amd64        library for reading metadata from media files -- shared library
ii  libmessaging-menu0                                    13.10.1+14.04.20140410-0ubuntu1                     amd64        Messaging Menu - shared library
ii  libmetacity-private0a                                 1:2.34.13-0ubuntu4.1                                amd64        library for the Metacity window manager
ii  libmhash2:amd64                                       0.9.9.9-4                                           amd64        Library for cryptographic hashing and message authentication
ii  libminiupnpc8                                         1.6-3ubuntu2.14.04.2                                amd64        UPnP IGD client lightweight library
ii  libmission-control-plugins0                           1:5.16.1-1ubuntu3                                   amd64        management daemon for Telepathy (library for plugins)
ii  libmm-glib0:amd64                                     1.0.0-2ubuntu1.1                                    amd64        D-Bus service for managing modems - shared libraries
ii  libmms0:amd64                                         0.6.2-3ubuntu2                                      amd64        MMS stream protocol library - shared library
ii  libmnl0:amd64                                         1.0.3-3ubuntu1                                      amd64        minimalistic Netlink communication library
ii  libmodule-pluggable-perl                              5.1-1                                               all          module for giving  modules the ability to have plugins
ii  libmono-cairo4.0-cil                                  3.2.8+dfsg-4ubuntu1.1                               all          Mono Cairo library (for CLI 4.0)
ii  libmono-corlib4.0-cil                                 3.2.8+dfsg-4ubuntu1.1                               all          Mono core library (for CLI 4.0)
ii  libmono-corlib4.5-cil                                 3.2.8+dfsg-4ubuntu1.1                               all          Mono core library (for CLI 4.5)
ii  libmono-i18n-west4.0-cil                              3.2.8+dfsg-4ubuntu1.1                               all          Mono I18N.West library (for CLI 4.0)
ii  libmono-i18n4.0-cil                                   3.2.8+dfsg-4ubuntu1.1                               all          Mono I18N base library (for CLI 4.0)
ii  libmono-security4.0-cil                               3.2.8+dfsg-4ubuntu1.1                               all          Mono Security library (for CLI 4.0)
ii  libmono-system-configuration4.0-cil                   3.2.8+dfsg-4ubuntu1.1                               all          Mono System.Configuration library (for CLI 4.0)
ii  libmono-system-drawing4.0-cil                         3.2.8+dfsg-4ubuntu1.1                               all          Mono System.Drawing library (for CLI 4.0)
ii  libmono-system-security4.0-cil                        3.2.8+dfsg-4ubuntu1.1                               all          Mono System.Security library (for CLI 4.0)
ii  libmono-system-xml4.0-cil                             3.2.8+dfsg-4ubuntu1.1                               all          Mono System.Xml library (for CLI 4.0)
ii  libmono-system4.0-cil                                 3.2.8+dfsg-4ubuntu1.1                               all          Mono System libraries (for CLI 4.0)
ii  libmount1:amd64                                       2.20.1-5.1ubuntu20.7                                amd64        block device id library
ii  libmpc3:amd64                                         1.0.1-1ubuntu1                                      amd64        multiple precision complex floating-point library
ii  libmpdec2:amd64                                       2.4.0-6                                             amd64        library for decimal floating point arithmetic (runtime library)
ii  libmpfr4:amd64                                        3.1.2-1                                             amd64        multiple precision floating-point computation
ii  libmspub-0.0-0                                        0.0.6-1ubuntu2                                      amd64        library for parsing the mspub file structure
ii  libmtdev1:amd64                                       1.1.4-1ubuntu1                                      amd64        Multitouch Protocol Translation Library - shared library
ii  libmtp-common                                         1.1.6-20-g1b9f164-1ubuntu2.1                        all          Media Transfer Protocol (MTP) common files
ii  libmtp-runtime                                        1.1.6-20-g1b9f164-1ubuntu2.1                        amd64        Media Transfer Protocol (MTP) runtime tools
ii  libmtp9:amd64                                         1.1.6-20-g1b9f164-1ubuntu2.1                        amd64        Media Transfer Protocol (MTP) library
ii  libmythes-1.2-0                                       2:1.2.2-1ubuntu2                                    amd64        simple thesaurus library
ii  libnatpmp1                                            20110808-3ubuntu2                                   amd64        portable and fully compliant implementation of NAT-PMP
ii  libnautilus-extension1a                               1:3.10.1-0ubuntu9.11                                amd64        libraries for nautilus components - runtime version
ii  libncurses5:amd64                                     5.9+20140118-1ubuntu1                               amd64        shared libraries for terminal handling
ii  libncursesw5:amd64                                    5.9+20140118-1ubuntu1                               amd64        shared libraries for terminal handling (wide character support)
ii  libneon27-gnutls                                      0.30.0-1ubuntu1                                     amd64        HTTP and WebDAV client library (GnuTLS enabled)
ii  libnet-dns-perl                                       0.68-1.2build1                                      amd64        Perform DNS queries from a Perl script
ii  libnet-domain-tld-perl                                1.70-1                                              all          list of currently available Top-level Domains (TLDs)
ii  libnet-http-perl                                      6.06-1                                              all          module providing low-level HTTP connection client
ii  libnet-ip-perl                                        1.26-1                                              all          Perl extension for manipulating IPv4/IPv6 addresses
ii  libnet-libidn-perl                                    0.12.ds-1build4                                     amd64        Perl bindings for GNU Libidn
ii  libnet-smtp-ssl-perl                                  1.01-3                                              all          Perl module providing SSL support to Net::SMTP
ii  libnet-ssleay-perl                                    1.58-1                                              amd64        Perl module for Secure Sockets Layer (SSL)
ii  libnetfilter-conntrack3:amd64                         1.0.4-1                                             amd64        Netfilter netlink-conntrack library
ii  libnettle4:amd64                                      2.7.1-1ubuntu0.1                                    amd64        low level cryptographic library (symmetric and one-way cryptos)
ii  libnewt0.52:amd64                                     0.52.15-2ubuntu5                                    amd64        Not Erik's Windowing Toolkit - text mode windowing with slang
ii  libnfnetlink0:amd64                                   1.0.1-2                                             amd64        Netfilter netlink library
ii  libnice10:amd64                                       0.1.4-1                                             amd64        ICE library (shared library)
ii  libnih-dbus1:amd64                                    1.0.3-4ubuntu25                                     amd64        NIH D-Bus Bindings Library
ii  libnih1:amd64                                         1.0.3-4ubuntu25                                     amd64        NIH Utility Library
ii  libnl-3-200:amd64                                     3.2.21-1                                            amd64        library for dealing with netlink sockets
ii  libnl-genl-3-200:amd64                                3.2.21-1                                            amd64        library for dealing with netlink sockets - generic netlink
ii  libnl-route-3-200:amd64                               3.2.21-1                                            amd64        library for dealing with netlink sockets - route interface
ii  libnm-glib-vpn1                                       0.9.8.8-0ubuntu7.2                                  amd64        network management framework (GLib VPN shared library)
ii  libnm-glib4                                           0.9.8.8-0ubuntu7.2                                  amd64        network management framework (GLib shared library)
ii  libnm-gtk-common                                      0.9.8.8-0ubuntu4.4                                  all          network management framework (common files for wifi and mobile)
ii  libnm-gtk0                                            0.9.8.8-0ubuntu4.4                                  amd64        network management framework (GNOME dialogs for wifi and mobile)
ii  libnm-util2                                           0.9.8.8-0ubuntu7.2                                  amd64        network management framework (shared library)
ii  libnotify-bin                                         0.7.6-1ubuntu3                                      amd64        sends desktop notifications to a notification daemon (Utilities)
ii  libnotify4:amd64                                      0.7.6-1ubuntu3                                      amd64        sends desktop notifications to a notification daemon
ii  libnspr4:amd64                                        2:4.10.10-0ubuntu0.14.04.1                          amd64        NetScape Portable Runtime Library
ii  libnss-mdns:amd64                                     0.10-6                                              amd64        NSS module for Multicast DNS name resolution
ii  libnss3:amd64                                         2:3.21-0ubuntu0.14.04.1                             amd64        Network Security Service libraries
ii  libnss3-1d:amd64                                      2:3.21-0ubuntu0.14.04.1                             amd64        Network Security Service libraries - transitional package
ii  libnss3-nssdb                                         2:3.21-0ubuntu0.14.04.1                             all          Network Security Security libraries - shared databases
ii  libntdb1:amd64                                        1.0-2ubuntu1                                        amd64        New Trivial Database - shared library
ii  libnuma1:amd64                                        2.0.9~rc5-1ubuntu3.14.04.1                          amd64        Libraries for controlling NUMA policy
ii  libnux-4.0-0                                          4.0.6+14.04.20141107-0ubuntu1                       amd64        Visual rendering toolkit for real-time applications - shared lib
ii  libnux-4.0-common                                     4.0.6+14.04.20141107-0ubuntu1                       amd64        Visual rendering toolkit for real-time applications - common files
ii  liboauth0:amd64                                       1.0.1-1                                             amd64        C library for implementing OAuth 1.0
ii  libogg0:amd64                                         1.3.1-1ubuntu1                                      amd64        Ogg bitstream library
ii  liboil0.3:amd64                                       0.3.17-2ubuntu4                                     amd64        Library of Optimized Inner Loops
ii  libopencc1:amd64                                      0.4.3-2build1                                       amd64        simplified-traditional chinese conversion library - runtime
ii  libopenobex1                                          1.5-2.1                                             amd64        OBEX protocol library
ii  libopenvg1-mesa:amd64                                 10.1.3-0ubuntu0.6                                   amd64        free implementation of the OpenVG API -- runtime
ii  libopts25:amd64                                       1:5.18-2ubuntu2                                     amd64        automated option processing library based on autogen
ii  libopts25-dev                                         1:5.18-2ubuntu2                                     amd64        automated option processing library based on autogen
ii  liborc-0.4-0:amd64                                    1:0.4.18-1ubuntu1                                   amd64        Library of Optimized Inner Loops Runtime Compiler
ii  liborcus-0.6-0                                        0.5.1-7                                             amd64        library for processing spreadsheet documents
ii  liboxideqt-qmlplugin:amd64                            1.12.7-0ubuntu0.14.04.1                             amd64        Web browser engine library for Qt (QML plugin)
ii  liboxideqtcore0:amd64                                 1.12.7-0ubuntu0.14.04.1                             amd64        Web browser engine library for Qt (core library and components)
ii  liboxideqtquick0:amd64                                1.12.7-0ubuntu0.14.04.1                             amd64        Web browser engine library for Qt (QtQuick library)
ii  libp11-kit-gnome-keyring:amd64                        3.10.1-1ubuntu4.2                                   amd64        GNOME keyring module for the PKCS#11 module loading library
ii  libp11-kit0:amd64                                     0.20.2-2ubuntu2                                     amd64        Library for loading and coordinating access to PKCS#11 modules - runtime
ii  libpackagekit-glib2-16:amd64                          0.8.12-1ubuntu5                                     amd64        Library for accessing PackageKit using GLib
ii  libpam-cap:amd64                                      1:2.24-0ubuntu2                                     amd64        PAM module for implementing capabilities
ii  libpam-gnome-keyring:amd64                            3.10.1-1ubuntu4.2                                   amd64        PAM module to unlock the GNOME keyring upon login
ii  libpam-modules:amd64                                  1.1.8-1ubuntu2                                      amd64        Pluggable Authentication Modules for PAM
ii  libpam-modules-bin                                    1.1.8-1ubuntu2                                      amd64        Pluggable Authentication Modules for PAM - helper binaries
ii  libpam-runtime                                        1.1.8-1ubuntu2                                      all          Runtime support for the PAM library
ii  libpam-systemd:amd64                                  204-5ubuntu20.18                                    amd64        system and service manager - PAM module
ii  libpam0g:amd64                                        1.1.8-1ubuntu2                                      amd64        Pluggable Authentication Modules library
ii  libpango-1.0-0:amd64                                  1.36.3-1ubuntu1.1                                   amd64        Layout and rendering of internationalized text
ii  libpango-perl                                         1.224-2                                             amd64        Perl module to layout and render international text
ii  libpango1.0-0:amd64                                   1.36.3-1ubuntu1.1                                   amd64        Layout and rendering of internationalized text
ii  libpangocairo-1.0-0:amd64                             1.36.3-1ubuntu1.1                                   amd64        Layout and rendering of internationalized text
ii  libpangoft2-1.0-0:amd64                               1.36.3-1ubuntu1.1                                   amd64        Layout and rendering of internationalized text
ii  libpangomm-1.4-1:amd64                                2.34.0-1ubuntu1                                     amd64        C++ Wrapper for pango (shared libraries)
ii  libpangox-1.0-0:amd64                                 0.0.2-4ubuntu1                                      amd64        pango library X backend
ii  libpangoxft-1.0-0:amd64                               1.36.3-1ubuntu1.1                                   amd64        Layout and rendering of internationalized text
ii  libpaper-utils                                        1.1.24+nmu2ubuntu3                                  amd64        library for handling paper characteristics (utilities)
ii  libpaper1:amd64                                       1.1.24+nmu2ubuntu3                                  amd64        library for handling paper characteristics
ii  libparse-debianchangelog-perl                         1.2.0-1ubuntu1                                      all          parse Debian changelogs and output them in other formats
ii  libparted0debian1:amd64                               2.3-19ubuntu1.14.04.1                               amd64        disk partition manipulator - shared library
ii  libpcap0.8:amd64                                      1.5.3-2                                             amd64        system interface for user-level packet capture
ii  libpci3:amd64                                         1:3.2.1-1ubuntu5.1                                  amd64        Linux PCI Utilities (shared library)
ii  libpciaccess0:amd64                                   0.13.2-1                                            amd64        Generic PCI access library for X
ii  libpcre3:amd64                                        1:8.31-2ubuntu2.1                                   amd64        Perl 5 Compatible Regular Expression Library - runtime files
ii  libpcsclite1:amd64                                    1.8.10-1ubuntu1                                     amd64        Middleware to access a smart card using PC/SC (library)
ii  libpeas-1.0-0                                         1.8.1-2ubuntu2                                      amd64        Application plugin library
ii  libpeas-common                                        1.8.1-2ubuntu2                                      all          Application plugin library (common files)
ii  libperl5.18                                           5.18.2-2ubuntu1                                     amd64        shared Perl library
ii  libperlio-gzip-perl                                   0.18-1build3                                        amd64        module providing a PerlIO layer to gzip/gunzip
ii  libpipeline1:amd64                                    1.3.0-1                                             amd64        pipeline manipulation library
ii  libpixman-1-0:amd64                                   0.30.2-2ubuntu1                                     amd64        pixel-manipulation library for X and cairo
ii  libplist1:amd64                                       1.10-1                                              amd64        Library for handling Apple binary and XML property lists
ii  libplymouth2:amd64                                    0.8.8-0ubuntu17.1                                   amd64        graphical boot animation and logger - shared libraries
ii  libpng12-0:amd64                                      1.2.50-1ubuntu2.14.04.2                             amd64        PNG library - runtime
ii  libpocketsphinx1                                      0.8.0+real-0ubuntu6                                 amd64        lightweight speech recognition - library
ii  libpod-latex-perl                                     0.61-1                                              all          module to convert Pod data to formatted LaTeX
ii  libpolkit-agent-1-0:amd64                             0.105-4ubuntu3.14.04.1                              amd64        PolicyKit Authentication Agent API
ii  libpolkit-backend-1-0:amd64                           0.105-4ubuntu3.14.04.1                              amd64        PolicyKit backend API
ii  libpolkit-gobject-1-0:amd64                           0.105-4ubuntu3.14.04.1                              amd64        PolicyKit Authorization API
ii  libpoppler-glib8:amd64                                0.24.5-2ubuntu4.3                                   amd64        PDF rendering library (GLib-based shared library)
ii  libpoppler44:amd64                                    0.24.5-2ubuntu4.3                                   amd64        PDF rendering library
ii  libpopt0:amd64                                        1.16-8ubuntu1                                       amd64        lib for parsing cmdline parameters
ii  libportaudio2:amd64                                   19+svn20140130-1                                    amd64        Portable audio I/O - shared library
ii  libprocps3:amd64                                      1:3.3.9-1ubuntu2.2                                  amd64        library for accessing process information from /proc
ii  libprotobuf8:amd64                                    2.5.0-9ubuntu1                                      amd64        protocol buffers C++ library
ii  libproxy1:amd64                                       0.4.11-0ubuntu4                                     amd64        automatic proxy configuration management library (shared)
ii  libproxy1-plugin-gsettings:amd64                      0.4.11-0ubuntu4                                     amd64        automatic proxy configuration management library (GSettings plugin)
ii  libproxy1-plugin-networkmanager:amd64                 0.4.11-0ubuntu4                                     amd64        automatic proxy configuration management library (Network Manager plugin)
ii  libpulse-mainloop-glib0:amd64                         1:4.0-0ubuntu11.1                                   amd64        PulseAudio client libraries (glib support)
ii  libpulse0:amd64                                       1:4.0-0ubuntu11.1                                   amd64        PulseAudio client libraries
ii  libpulsedsp:amd64                                     1:4.0-0ubuntu11.1                                   amd64        PulseAudio OSS pre-load library
ii  libpurple-bin                                         1:2.10.9-0ubuntu3.2                                 all          multi-protocol instant messaging library - extra utilities
ii  libpurple0                                            1:2.10.9-0ubuntu3.2                                 amd64        multi-protocol instant messaging library
ii  libpwquality-common                                   1.2.3-1ubuntu1.1                                    all          library for password quality checking and generation (data files)
ii  libpwquality1:amd64                                   1.2.3-1ubuntu1.1                                    amd64        library for password quality checking and generation
ii  libpython-stdlib:amd64                                2.7.5-5ubuntu3                                      amd64        interactive high-level object-oriented language (default python version)
ii  libpython2.7:amd64                                    2.7.6-8ubuntu0.2                                    amd64        Shared Python runtime library (version 2.7)
ii  libpython2.7-minimal:amd64                            2.7.6-8ubuntu0.2                                    amd64        Minimal subset of the Python language (version 2.7)
ii  libpython2.7-stdlib:amd64                             2.7.6-8ubuntu0.2                                    amd64        Interactive high-level object-oriented language (standard library, version 2.7)
ii  libpython3-stdlib:amd64                               3.4.0-0ubuntu2                                      amd64        interactive high-level object-oriented language (default python3 version)
ii  libpython3.4:amd64                                    3.4.3-1ubuntu1~14.04.3                              amd64        Shared Python runtime library (version 3.4)
ii  libpython3.4-minimal:amd64                            3.4.3-1ubuntu1~14.04.3                              amd64        Minimal subset of the Python language (version 3.4)
ii  libpython3.4-stdlib:amd64                             3.4.3-1ubuntu1~14.04.3                              amd64        Interactive high-level object-oriented language (standard library, version 3.4)
ii  libpyzy-1.0-0                                         1.0.1-4                                             amd64        Chinese PinYin and Bopomofo conversion library
ii  libqdjango-db0:amd64                                  0.4.0-1ubuntu2                                      amd64        Database library for the QDjango framework
ii  libqgsttools-p1:amd64                                 5.2.1-0ubuntu5                                      amd64        GStreamer tools for  Qt 5 Multimedia module
ii  libqmi-glib0:amd64                                    1.4.0-1                                             amd64        Support library to use the Qualcomm MSM Interface (QMI) protocol
ii  libqpdf13:amd64                                       5.1.1-1                                             amd64        runtime library for PDF transformation/inspection software
ii  libqt4-dbus:amd64                                     4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 D-Bus module
ii  libqt4-declarative:amd64                              4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 Declarative module
ii  libqt4-designer:amd64                                 4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 designer module
ii  libqt4-help:amd64                                     4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 help module
ii  libqt4-network:amd64                                  4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 network module
ii  libqt4-opengl:amd64                                   4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 OpenGL module
ii  libqt4-script:amd64                                   4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 script module
ii  libqt4-scripttools:amd64                              4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 script tools module
ii  libqt4-sql:amd64                                      4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 SQL module
ii  libqt4-sql-sqlite:amd64                               4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 SQLite 3 database driver
ii  libqt4-svg:amd64                                      4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 SVG module
ii  libqt4-test:amd64                                     4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 test module
ii  libqt4-xml:amd64                                      4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 XML module
ii  libqt4-xmlpatterns:amd64                              4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 XML patterns module
ii  libqt5core5a:amd64                                    5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 core module
ii  libqt5dbus5:amd64                                     5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 D-Bus module
ii  libqt5feedback5:amd64                                 5.0~git20130529-0ubuntu3                            amd64        Qt Feedback module
ii  libqt5gui5:amd64                                      5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 GUI module
ii  libqt5multimedia5:amd64                               5.2.1-0ubuntu5                                      amd64        Qt 5 Multimedia module
ii  libqt5multimedia5-plugins:amd64                       5.2.1-0ubuntu5                                      amd64        Qt 5 Multimedia module plugins
ii  libqt5multimediaquick-p5:amd64                        5.2.1-0ubuntu5                                      amd64        Qt 5 Multimedia Quick module
ii  libqt5multimediawidgets5:amd64                        5.2.1-0ubuntu5                                      amd64        Qt 5 Multimedia Widgets module
ii  libqt5network5:amd64                                  5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 network module
ii  libqt5opengl5:amd64                                   5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 OpenGL module
ii  libqt5organizer5:amd64                                5.0~git20140203~e0c5eebe-0ubuntu2                   amd64        Qt PIM module, Organizer library
ii  libqt5positioning5:amd64                              5.2.1-1ubuntu2                                      amd64        Qt Positioning module
ii  libqt5printsupport5:amd64                             5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 print support module
ii  libqt5qml-graphicaleffects:amd64                      5.2.1-1                                             amd64        Qt 5 Graphical Effects module
ii  libqt5qml5:amd64                                      5.2.1-3ubuntu15.1                                   amd64        Qt 5 QML module
ii  libqt5quick5:amd64                                    5.2.1-3ubuntu15.1                                   amd64        Qt 5 Quick library
ii  libqt5sensors5:amd64                                  5.2.1+dfsg-2ubuntu2                                 amd64        Qt Sensors module
ii  libqt5sql5:amd64                                      5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 SQL module
ii  libqt5sql5-sqlite:amd64                               5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 SQLite 3 database driver
ii  libqt5svg5:amd64                                      5.2.1-1                                             amd64        Qt 5 SVG module
ii  libqt5test5:amd64                                     5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 test module
ii  libqt5webkit5:amd64                                   5.1.1-1ubuntu8                                      amd64        Web content engine library for Qt
ii  libqt5webkit5-qmlwebkitplugin:amd64                   5.1.1-1ubuntu8                                      amd64        Qt WebKit QML plugin
ii  libqt5widgets5:amd64                                  5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 widgets module
ii  libqt5xml5:amd64                                      5.2.1+dfsg-1ubuntu14.3                              amd64        Qt 5 XML module
ii  libqtassistantclient4:amd64                           4.6.3-6                                             amd64        Qt Assistant client library (runtime)
ii  libqtcore4:amd64                                      4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 core module
ii  libqtdbus4:amd64                                      4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 D-Bus module library
ii  libqtgui4:amd64                                       4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 GUI module
ii  libqtwebkit4:amd64                                    2.3.2-0ubuntu7                                      amd64        Web content engine library for Qt
ii  libquadmath0:amd64                                    4.8.4-2ubuntu1~14.04.1                              amd64        GCC Quad-Precision Math Library
ii  libraptor2-0:amd64                                    2.0.13-1                                            amd64        Raptor 2 RDF syntax library
ii  librasqal3:amd64                                      0.9.32-1                                            amd64        Rasqal RDF query library
ii  libraw1394-11:amd64                                   2.1.0-1ubuntu1                                      amd64        library for direct access to IEEE 1394 bus (aka FireWire)
ii  libraw9:amd64                                         0.15.4-1                                            amd64        raw image decoder library
ii  librdf0:amd64                                         1.0.17-1                                            amd64        Redland Resource Description Framework (RDF) library
ii  libreadline5:amd64                                    5.2+dfsg-2                                          amd64        GNU readline and history libraries, run-time libraries
ii  libreadline6:amd64                                    6.3-4ubuntu2                                        amd64        GNU readline and history libraries, run-time libraries
ii  libreoffice-avmedia-backend-gstreamer                 1:4.2.8-0ubuntu4                                    amd64        GStreamer backend for LibreOffice
ii  libreoffice-base-core                                 1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- shared library
ii  libreoffice-calc                                      1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- spreadsheet
ii  libreoffice-common                                    1:4.2.8-0ubuntu4                                    all          office productivity suite -- arch-independent files
ii  libreoffice-core                                      1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- arch-dependent files
ii  libreoffice-draw                                      1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- drawing
ii  libreoffice-gnome                                     1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- GNOME integration
ii  libreoffice-gtk                                       1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- GTK+ integration
ii  libreoffice-impress                                   1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- presentation
ii  libreoffice-math                                      1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- equation editor
ii  libreoffice-ogltrans                                  1:4.2.8-0ubuntu4                                    amd64        LibreOffice Impress extension for transitions using OpenGL
ii  libreoffice-pdfimport                                 1:4.2.8-0ubuntu4                                    amd64        PDF Import component for LibreOffice
ii  libreoffice-presentation-minimizer                    1:4.2.8-0ubuntu4                                    all          transitional package for the LibreOffice presentation minimizer
ii  libreoffice-style-human                               1:4.2.8-0ubuntu4                                    all          office productivity suite -- Human symbol style
ii  libreoffice-writer                                    1:4.2.8-0ubuntu4                                    amd64        office productivity suite -- word processor
ii  librest-0.7-0:amd64                                   0.7.90-0ubuntu1                                     amd64        REST service access library
ii  librhythmbox-core8                                    3.0.2-0ubuntu2                                      amd64        support library for the rhythmbox music player
ii  libroken18-heimdal:amd64                              1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - roken support library
ii  librsvg2-2:amd64                                      2.40.2-1                                            amd64        SAX-based renderer library for SVG files (runtime)
ii  librsvg2-common:amd64                                 2.40.2-1                                            amd64        SAX-based renderer library for SVG files (extra runtime)
ii  librsync1:amd64                                       0.9.7-10                                            amd64        rsync remote-delta algorithm library
ii  librtmp0:amd64                                        2.4+20121230.gitdf6c518-1                           amd64        toolkit for RTMP streams (shared library)
ii  libsamplerate0:amd64                                  0.1.8-7                                             amd64        Audio sample rate conversion library
ii  libsane:amd64                                         1.0.23-3ubuntu3.1                                   amd64        API library for scanners
ii  libsane-common                                        1.0.23-3ubuntu3.1                                   amd64        API library for scanners -- documentation and support files
ii  libsane-hpaio                                         3.14.3-0ubuntu3.4                                   amd64        HP SANE backend for multi-function peripherals
ii  libsasl2-2:amd64                                      2.1.25.dfsg1-17build1                               amd64        Cyrus SASL - authentication abstraction library
ii  libsasl2-modules:amd64                                2.1.25.dfsg1-17build1                               amd64        Cyrus SASL - pluggable authentication modules
ii  libsasl2-modules-db:amd64                             2.1.25.dfsg1-17build1                               amd64        Cyrus SASL - pluggable authentication modules (DB)
ii  libsbc1:amd64                                         1.1-2ubuntu2                                        amd64        Sub Band CODEC library - runtime
ii  libsecret-1-0:amd64                                   0.16-0ubuntu1                                       amd64        Secret store
ii  libsecret-common                                      0.16-0ubuntu1                                       all          Secret store (common files)
ii  libselinux1:amd64                                     2.2.2-1ubuntu0.1                                    amd64        SELinux runtime shared libraries
ii  libsemanage-common                                    2.2-1                                               all          Common files for SELinux policy management libraries
ii  libsemanage1:amd64                                    2.2-1                                               amd64        SELinux policy management library
ii  libsensors4:amd64                                     1:3.3.4-2ubuntu1                                    amd64        library to read temperature/voltage/fan sensors
ii  libsepol1:amd64                                       2.2-1ubuntu0.1                                      amd64        SELinux library for manipulating binary security policies
ii  libsgutils2-2                                         1.36-1ubuntu1                                       amd64        utilities for devices using the SCSI command set (shared libraries)
ii  libshout3:amd64                                       2.3.1-3                                             amd64        MP3/Ogg Vorbis broadcast streaming library
ii  libsigc++-2.0-0c2a:amd64                              2.2.10-0.2ubuntu2                                   amd64        type-safe Signal Framework for C++ - runtime
ii  libsignon-extension1                                  8.56+14.04.20140307-0ubuntu2                        amd64        Single Sign On framework
ii  libsignon-glib1                                       1.10daily13.06.25-0ubuntu2                          amd64        library for signond
ii  libsignon-plugins-common1                             8.56+14.04.20140307-0ubuntu2                        amd64        Single Sign On framework
ii  libsignon-qt5-1                                       8.56+14.04.20140307-0ubuntu2                        amd64        Single Sign On framework
ii  libsigsegv2:amd64                                     2.10-2                                              amd64        Library for handling page faults in a portable way
ii  libslang2:amd64                                       2.2.4-15ubuntu1                                     amd64        S-Lang programming library - runtime version
ii  libsm6:amd64                                          2:1.2.1-2                                           amd64        X11 Session Management library
ii  libsmbclient:amd64                                    2:4.1.6+dfsg-1ubuntu2.14.04.12                      amd64        shared library for communication with SMB/CIFS servers
ii  libsndfile1:amd64                                     1.0.25-7ubuntu2.1                                   amd64        Library for reading/writing audio files
ii  libsnmp-base                                          5.7.2~dfsg-8.1ubuntu3.1                             all          SNMP configuration script, MIBs and documentation
ii  libsnmp30:amd64                                       5.7.2~dfsg-8.1ubuntu3.1                             amd64        SNMP (Simple Network Management Protocol) library
ii  libsocket6-perl                                       0.25-1                                              amd64        Perl extensions for IPv6
ii  libsonic0:amd64                                       0.1.18-0ubuntu1                                     amd64        Simple library to speed up or slow down speech
ii  libsoup-gnome2.4-1:amd64                              2.44.2-1ubuntu2                                     amd64        HTTP library implementation in C -- GNOME support library
ii  libsoup2.4-1:amd64                                    2.44.2-1ubuntu2                                     amd64        HTTP library implementation in C -- Shared library
ii  libspectre1:amd64                                     0.2.7-2ubuntu1.1                                    amd64        Library for rendering PostScript documents
ii  libspeechd2:amd64                                     0.8-5ubuntu1                                        amd64        Speech Dispatcher: Shared libraries
ii  libspeex1:amd64                                       1.2~rc1.1-1ubuntu1                                  amd64        The Speex codec runtime library
ii  libspeexdsp1:amd64                                    1.2~rc1.1-1ubuntu1                                  amd64        The Speex extended runtime library
ii  libsphinxbase1                                        0.8-0ubuntu10                                       amd64        Sphinx base libraries
ii  libspice-server1:amd64                                0.12.4-0nocelt2ubuntu1.2                            amd64        Implements the server side of the SPICE protocol
ii  libsqlite3-0:amd64                                    3.8.2-1ubuntu2.1                                    amd64        SQLite 3 shared library
ii  libss2:amd64                                          1.42.9-3ubuntu1.3                                   amd64        command-line interface parsing library
ii  libssh-4:amd64                                        0.6.1-0ubuntu3.3                                    amd64        tiny C SSH library
ii  libssl1.0.0:amd64                                     1.0.1f-1ubuntu2.18                                  amd64        Secure Sockets Layer toolkit - shared libraries
ii  libstartup-notification0:amd64                        0.12-3ubuntu1                                       amd64        library for program launch feedback (shared library)
ii  libstdc++-4.8-dev:amd64                               4.8.4-2ubuntu1~14.04.1                              amd64        GNU Standard C++ Library v3 (development files)
ii  libstdc++6:amd64                                      4.8.4-2ubuntu1~14.04.1                              amd64        GNU Standard C++ Library v3
ii  libsub-identify-perl                                  0.04-1build3                                        amd64        Retrieve names of code references
ii  libsub-name-perl                                      0.05-1build4                                        amd64        module for assigning a new name to referenced sub
ii  libsystemd-daemon0:amd64                              204-5ubuntu20.18                                    amd64        systemd utility library
ii  libsystemd-journal0:amd64                             204-5ubuntu20.18                                    amd64        systemd journal utility library
ii  libsystemd-login0:amd64                               204-5ubuntu20.18                                    amd64        systemd login utility library
ii  libt1-5                                               5.1.2-3.6ubuntu1                                    amd64        Type 1 font rasterizer library - runtime
ii  libtag1-vanilla:amd64                                 1.9.1-2                                             amd64        audio meta-data library - vanilla flavour
ii  libtag1c2a:amd64                                      1.9.1-2                                             amd64        audio meta-data library
ii  libtalloc2:amd64                                      2.1.0-1                                             amd64        hierarchical pool based memory allocator
ii  libtasn1-6:amd64                                      3.4-3ubuntu0.3                                      amd64        Manage ASN.1 structures (runtime)
ii  libtcl8.6:amd64                                       8.6.1-4ubuntu1                                      amd64        Tcl (the Tool Command Language) v8.6 - run-time library files
ii  libtdb1:amd64                                         1.2.12-1                                            amd64        Trivial Database - shared library
ii  libtelepathy-farstream3:amd64                         0.6.1-0ubuntu1                                      amd64        Glue library between telepathy and farstream
ii  libtelepathy-glib0:amd64                              0.22.1-1ubuntu2                                     amd64        Telepathy framework - GLib library
ii  libtelepathy-logger3:amd64                            0.8.0-3                                             amd64        Telepathy logger service - utility library
ii  libterm-ui-perl                                       0.42-1                                              all          Term::ReadLine UI made easy
ii  libtevent0:amd64                                      0.9.19-1                                            amd64        talloc-based event loop library - shared library
ii  libtext-charwidth-perl                                0.04-7build3                                        amd64        get display widths of characters on the terminal
ii  libtext-iconv-perl                                    1.7-5build2                                         amd64        converts between character sets in Perl
ii  libtext-levenshtein-perl                              0.06~01-2                                           all          implementation of the Levenshtein edit distance
ii  libtext-soundex-perl                                  3.4-1build1                                         amd64        implementation of the soundex algorithm
ii  libtext-wrapi18n-perl                                 0.06-7                                              all          internationalized substitute of Text::Wrap
ii  libthai-data                                          0.1.20-3                                            all          Data files for Thai language support library
ii  libthai0:amd64                                        0.1.20-3                                            amd64        Thai language support library
ii  libtheora0:amd64                                      1.1.1+dfsg.1-3.2                                    amd64        Theora Video Compression Codec
ii  libthumbnailer0:amd64                                 1.1+14.04.20150205-0ubuntu1                         amd64        generate thumbnails from files
ii  libtiff5:amd64                                        4.0.3-7ubuntu0.3                                    amd64        Tag Image File Format (TIFF) library
ii  libtimedate-perl                                      2.3000-1                                            all          collection of modules to manipulate date/time information
ii  libtimezonemap1                                       0.4.1                                               amd64        GTK+3 timezone map widget
ii  libtinfo5:amd64                                       5.9+20140118-1ubuntu1                               amd64        shared low-level terminfo library for terminal handling
ii  libtinyxml2-0.0.0:amd64                               0~git20120518.1.a2ae54e-1                           amd64        C++ XML parsing library
ii  libtk8.6:amd64                                        8.6.1-3ubuntu2                                      amd64        Tk toolkit for Tcl and X11 v8.6 - run-time files
ii  libtool                                               2.4.2-1.7ubuntu1                                    amd64        Generic library support script
ii  libtotem-plparser18                                   3.10.2-0ubuntu1                                     amd64        Totem Playlist Parser library - runtime files
ii  libtotem0                                             3.10.1-1ubuntu4                                     amd64        Main library for the Totem media player
ii  libtsan0:amd64                                        4.8.4-2ubuntu1~14.04.1                              amd64        ThreadSanitizer -- a Valgrind-based detector of data races (runtime)
ii  libtxc-dxtn-s2tc0:amd64                               0~git20131104-1.1                                   amd64        Texture compression library for Mesa
ii  libudev1:amd64                                        204-5ubuntu20.18                                    amd64        libudev shared library
ii  libudisks2-0:amd64                                    2.1.3-1ubuntu0.1                                    amd64        GObject based library to access udisks2
ii  libufe-xidgetter0                                     3.0.0+14.04.20140416-0ubuntu1.14.04.1               amd64        Firefox extension: Unity Integration
ii  libunistring0:amd64                                   0.9.3-5ubuntu3                                      amd64        Unicode string library for C
ii  libunity-action-qt1:amd64                             1.1.0+14.04.20140304-0ubuntu1                       amd64        Unity Action Qt API
ii  libunity-control-center1                              14.04.3+14.04.20150916-0ubuntu1                     amd64        utilities to configure the GNOME desktop
ii  libunity-core-6.0-9                                   7.2.6+14.04.20151021-0ubuntu1                       amd64        core library for the Unity interface
ii  libunity-gtk2-parser0:amd64                           0.0.0+14.04.20141212-0ubuntu1                       amd64        GtkMenuShell to GMenuModel parser
ii  libunity-gtk3-parser0:amd64                           0.0.0+14.04.20141212-0ubuntu1                       amd64        GtkMenuShell to GMenuModel parser
ii  libunity-misc4                                        4.0.5+14.04.20140115-0ubuntu1                       amd64        Miscellaneous functions for Unity - shared library
ii  libunity-protocol-private0:amd64                      7.1.4+14.04.20140210-0ubuntu1                       amd64        binding to get places into the launcher - private library
ii  libunity-scopes-json-def-desktop                      7.1.4+14.04.20140210-0ubuntu1                       all          binding to get places into the launcher - desktop def file
ii  libunity-webapps0                                     2.5.0~+14.04.20140409-0ubuntu1                      amd64        Web Apps integration with the Unity desktop
ii  libunity9:amd64                                       7.1.4+14.04.20140210-0ubuntu1                       amd64        binding to get places into the launcher - shared library
ii  libunityvoice1:amd64                                  0.1+14.04.20140304-0ubuntu1                         amd64        client library for Unity voice service
ii  libupower-glib1:amd64                                 0.9.23-2ubuntu1somerville1                          amd64        abstraction for power management - shared library
ii  libupstart-app-launch2:amd64                          0.3+14.04.20140411-0ubuntu1                         amd64        library for sending requests to the upstart app launch
ii  libupstart1:amd64                                     1.12.1-0ubuntu4.2                                   amd64        Upstart Client Library
ii  liburcu1                                              0.7.12-0ubuntu2                                     amd64        userspace RCU (read-copy-update) library
ii  liburi-perl                                           1.60-1                                              all          module to manipulate and access URI strings
ii  liburl-dispatcher1:amd64                              0.1+14.04.20140403-0ubuntu1                         amd64        library for sending requests to the url dispatcher
ii  libusb-0.1-4:amd64                                    2:0.1.12-23.3ubuntu1                                amd64        userspace USB programming library
ii  libusb-1.0-0:amd64                                    2:1.0.17-1ubuntu2                                   amd64        userspace USB programming library
ii  libusbmuxd2                                           1.0.8-2ubuntu1                                      amd64        USB multiplexor daemon for iPhone and iPod Touch devices - library
ii  libusermetricsinput1:amd64                            1.1.1+14.04.20140305-0ubuntu2                       amd64        library for exporting anonymous metrics about users
ii  libustr-1.0-1:amd64                                   1.0.4-3ubuntu2                                      amd64        Micro string library: shared library
ii  libutempter0                                          1.1.5-4build1                                       amd64        A privileged helper for utmp/wtmp updates (runtime)
ii  libuuid-perl                                          0.05-1                                              amd64        Perl extension for using UUID interfaces as defined in e2fsprogs
ii  libuuid1:amd64                                        2.20.1-5.1ubuntu20.7                                amd64        Universally Unique ID library
ii  libv4l-0:amd64                                        1.0.1-1                                             amd64        Collection of video4linux support libraries
ii  libv4lconvert0:amd64                                  1.0.1-1                                             amd64        Video4linux frame format conversion library
ii  libvisio-0.0-0                                        0.0.31-1ubuntu2                                     amd64        library for parsing the visio file structure
ii  libvisual-0.4-0:amd64                                 0.4.0-5                                             amd64        Audio visualization framework
ii  libvisual-0.4-plugins:amd64                           0.4.0.dfsg.1-7build1                                amd64        Audio visualization framework plugins
ii  libvncserver0:amd64                                   0.9.9+dfsg-1ubuntu1.1                               amd64        API to write one's own vnc server
ii  libvorbis0a:amd64                                     1.3.2-1.3ubuntu1                                    amd64        The Vorbis General Audio Compression Codec (Decoder library)
ii  libvorbisenc2:amd64                                   1.3.2-1.3ubuntu1                                    amd64        The Vorbis General Audio Compression Codec (Encoder library)
ii  libvorbisfile3:amd64                                  1.3.2-1.3ubuntu1                                    amd64        The Vorbis General Audio Compression Codec (High Level API)
ii  libvpx1:amd64                                         1.3.0-2                                             amd64        VP8 video codec (shared library)
ii  libvte-2.90-9                                         1:0.34.9-1ubuntu2                                   amd64        Terminal emulator widget for GTK+ 3.0 - runtime files
ii  libvte-2.90-common                                    1:0.34.9-1ubuntu2                                   all          Terminal emulator widget for GTK+ 3.0 - common files
ii  libwacom-common                                       0.8-1                                               all          Wacom model feature query library (common files)
ii  libwacom2:amd64                                       0.8-1                                               amd64        Wacom model feature query library
ii  libwavpack1:amd64                                     4.70.0-1                                            amd64        audio codec (lossy and lossless) - library
ii  libwayland-client0:amd64                              1.4.0-1ubuntu1                                      amd64        wayland compositor infrastructure - client library
ii  libwayland-cursor0:amd64                              1.4.0-1ubuntu1                                      amd64        wayland compositor infrastructure - cursor library
ii  libwayland-egl1-mesa:amd64                            10.1.3-0ubuntu0.6                                   amd64        implementation of the Wayland EGL platform -- runtime
ii  libwayland-server0:amd64                              1.4.0-1ubuntu1                                      amd64        wayland compositor infrastructure - server library
ii  libwbclient0:amd64                                    2:4.1.6+dfsg-1ubuntu2.14.04.12                      amd64        Samba winbind client library
ii  libwebkitgtk-3.0-0:amd64                              2.4.8-1ubuntu1~ubuntu14.04.1                        amd64        Web content engine library for GTK+
ii  libwebkitgtk-3.0-common                               2.4.8-1ubuntu1~ubuntu14.04.1                        all          Web content engine library for GTK+ - data files
ii  libwebp5:amd64                                        0.4.0-4                                             amd64        Lossy compression of digital photographic images.
ii  libwebpmux1:amd64                                     0.4.0-4                                             amd64        Lossy compression of digital photographic images.
ii  libwhoopsie-preferences0                              0.12                                                amd64        Ubuntu error tracker submission settings - shared library
ii  libwhoopsie0                                          0.2.24.6ubuntu2                                     amd64        Ubuntu error tracker submission - shared library
ii  libwind0-heimdal:amd64                                1.6~git20131207+dfsg-1ubuntu1.1                     amd64        Heimdal Kerberos - stringprep implementation
ii  libwmf0.2-7:amd64                                     0.2.8.4-10.3ubuntu1.14.04.1                         amd64        Windows metafile conversion library
ii  libwmf0.2-7-gtk                                       0.2.8.4-10.3ubuntu1.14.04.1                         amd64        Windows metafile conversion library
ii  libwnck-3-0:amd64                                     3.4.7-0ubuntu3.1                                    amd64        Window Navigator Construction Kit - runtime files
ii  libwnck-3-common                                      3.4.7-0ubuntu3.1                                    all          Window Navigator Construction Kit - common files
ii  libwnck-common                                        1:2.30.7-0ubuntu4                                   all          Window Navigator Construction Kit - common files
ii  libwnck22                                             1:2.30.7-0ubuntu4                                   amd64        Window Navigator Construction Kit - runtime files
ii  libwpd-0.9-9                                          0.9.9-1                                             amd64        Library for handling WordPerfect documents (shared library)
ii  libwpg-0.2-2                                          0.2.2-1ubuntu1                                      amd64        WordPerfect graphics import/convert library (shared library)
ii  libwps-0.2-2                                          0.2.9-2ubuntu1                                      amd64        Works text file format import filter library (shared library)
ii  libwrap0:amd64                                        7.6.q-25                                            amd64        Wietse Venema's TCP wrappers library
ii  libwww-perl                                           6.05-2                                              all          simple and consistent interface to the world-wide web
ii  libwww-robotrules-perl                                6.01-1                                              all          database of robots.txt-derived permissions
ii  libx11-6:amd64                                        2:1.6.2-1ubuntu2                                    amd64        X11 client-side library
ii  libx11-data                                           2:1.6.2-1ubuntu2                                    all          X11 client-side library
ii  libx11-xcb1:amd64                                     2:1.6.2-1ubuntu2                                    amd64        Xlib/XCB interface library
ii  libx86-1:amd64                                        1.1+ds1-10                                          amd64        x86 real-mode library
ii  libxapian22                                           1.2.16-2ubuntu1                                     amd64        Search engine library
ii  libxatracker2:amd64                                   10.1.3-0ubuntu0.6                                   amd64        X acceleration library -- runtime
ii  libxau6:amd64                                         1:1.0.8-1                                           amd64        X11 authorisation library
ii  libxaw7:amd64                                         2:1.0.12-1                                          amd64        X11 Athena Widget library
ii  libxcb-dri2-0:amd64                                   1.10-2ubuntu1                                       amd64        X C Binding, dri2 extension
ii  libxcb-dri3-0:amd64                                   1.10-2ubuntu1                                       amd64        X C Binding, dri3 extension
ii  libxcb-glx0:amd64                                     1.10-2ubuntu1                                       amd64        X C Binding, glx extension
ii  libxcb-icccm4:amd64                                   0.4.1-1ubuntu1                                      amd64        utility libraries for X C Binding -- icccm
ii  libxcb-image0:amd64                                   0.3.9-1ubuntu2                                      amd64        utility libraries for X C Binding -- image
ii  libxcb-keysyms1:amd64                                 0.3.9-1ubuntu1                                      amd64        utility libraries for X C Binding -- keysyms
ii  libxcb-present0:amd64                                 1.10-2ubuntu1                                       amd64        X C Binding, present extension
ii  libxcb-randr0:amd64                                   1.10-2ubuntu1                                       amd64        X C Binding, randr extension
ii  libxcb-render-util0:amd64                             0.3.8-1.1ubuntu1                                    amd64        utility libraries for X C Binding -- render-util
ii  libxcb-render0:amd64                                  1.10-2ubuntu1                                       amd64        X C Binding, render extension
ii  libxcb-shape0:amd64                                   1.10-2ubuntu1                                       amd64        X C Binding, shape extension
ii  libxcb-shm0:amd64                                     1.10-2ubuntu1                                       amd64        X C Binding, shm extension
ii  libxcb-sync1:amd64                                    1.10-2ubuntu1                                       amd64        X C Binding, sync extension
ii  libxcb-util0:amd64                                    0.3.8-2ubuntu1                                      amd64        utility libraries for X C Binding -- atom, aux and event
ii  libxcb-xfixes0:amd64                                  1.10-2ubuntu1                                       amd64        X C Binding, xfixes extension
ii  libxcb-xkb1:amd64                                     1.10-2ubuntu1                                       amd64        X C Binding, XKEYBOARD extension
ii  libxcb1:amd64                                         1.10-2ubuntu1                                       amd64        X C Binding
ii  libxcomposite1:amd64                                  1:0.4.4-1                                           amd64        X11 Composite extension library
ii  libxcursor1:amd64                                     1:1.1.14-1                                          amd64        X cursor management library
ii  libxdamage1:amd64                                     1:1.1.4-1ubuntu1                                    amd64        X11 damaged region extension library
ii  libxdmcp6:amd64                                       1:1.1.1-1                                           amd64        X11 Display Manager Control Protocol library
ii  libxext6:amd64                                        2:1.3.2-1ubuntu0.0.14.04.1                          amd64        X11 miscellaneous extension library
ii  libxfixes3:amd64                                      1:5.0.1-1ubuntu1.1                                  amd64        X11 miscellaneous 'fixes' extension library
ii  libxfont1:amd64                                       1:1.4.7-1ubuntu0.2                                  amd64        X11 font rasterisation library
ii  libxft2:amd64                                         2.3.1-2                                             amd64        FreeType-based font drawing library for X
ii  libxi6:amd64                                          2:1.7.1.901-1ubuntu1.1                              amd64        X11 Input extension library
ii  libxinerama1:amd64                                    2:1.1.3-1                                           amd64        X11 Xinerama extension library
ii  libxkbcommon-x11-0:amd64                              0.4.1-0ubuntu1                                      amd64        library to create keymaps with the XKB X11 protocol
ii  libxkbcommon0:amd64                                   0.4.1-0ubuntu1                                      amd64        library interface to the XKB compiler - shared library
ii  libxkbfile1:amd64                                     1:1.0.8-1                                           amd64        X11 keyboard file manipulation library
ii  libxklavier16                                         5.4-0ubuntu1                                        amd64        X Keyboard Extension high-level API
ii  libxml-parser-perl                                    2.41-1build3                                        amd64        Perl module for parsing XML files
ii  libxml2:amd64                                         2.9.1+dfsg1-3ubuntu4.7                              amd64        GNOME XML library
ii  libxmu6:amd64                                         2:1.1.1-1                                           amd64        X11 miscellaneous utility library
ii  libxmuu1:amd64                                        2:1.1.1-1                                           amd64        X11 miscellaneous micro-utility library
ii  libxp6:amd64                                          1:1.0.2-1ubuntu1                                    amd64        X Printing Extension (Xprint) client library
ii  libxpm4:amd64                                         1:3.5.10-1                                          amd64        X11 pixmap library
ii  libxrandr2:amd64                                      2:1.4.2-1                                           amd64        X11 RandR extension library
ii  libxrender1:amd64                                     1:0.9.8-1build0.14.04.1                             amd64        X Rendering Extension client library
ii  libxres1:amd64                                        2:1.0.7-1                                           amd64        X11 Resource extension library
ii  libxshmfence1:amd64                                   1.1-2                                               amd64        X shared memory fences - shared library
ii  libxslt1.1:amd64                                      1.1.28-2build1                                      amd64        XSLT 1.0 processing library - runtime library
ii  libxss1:amd64                                         1:1.2.2-1                                           amd64        X11 Screen Saver extension library
ii  libxt6:amd64                                          1:1.1.4-1                                           amd64        X11 toolkit intrinsics library
ii  libxtables10                                          1.4.21-1ubuntu1                                     amd64        netfilter xtables library
ii  libxtst6:amd64                                        2:1.2.2-1                                           amd64        X11 Testing -- Record extension library
ii  libxv1:amd64                                          2:1.0.10-1                                          amd64        X11 Video extension library
ii  libxvmc1:amd64                                        2:1.0.8-1ubuntu1                                    amd64        X11 Video extension library
ii  libxxf86dga1:amd64                                    2:1.1.4-1                                           amd64        X11 Direct Graphics Access extension library
ii  libxxf86vm1:amd64                                     1:1.1.3-1                                           amd64        X11 XFree86 video mode extension library
ii  libyajl2:amd64                                        2.0.4-4                                             amd64        Yet Another JSON Library
ii  libyaml-tiny-perl                                     1.56-1                                              all          Perl module for reading and writing YAML files
ii  libyelp0                                              3.10.2-0ubuntu1                                     amd64        Library for the GNOME help browser
ii  libzeitgeist-1.0-1                                    0.3.18-1ubuntu2                                     amd64        library to access Zeitgeist - shared library
ii  libzeitgeist-2.0-0:amd64                              0.9.14-0ubuntu4.1                                   amd64        library to access Zeitgeist - shared library
ii  libzen0:amd64                                         0.4.29-1                                            amd64        ZenLib C++ utility library -- runtime
ii  libzephyr4:amd64                                      3.1.2-1                                             amd64        Project Athena's notification service - non-Kerberos libraries
ii  light-themes                                          14.04+14.04.20140410-0ubuntu1                       all          Light Themes (Ambiance and Radiance)
ii  lightdm                                               1.10.6-0ubuntu1                                     amd64        Display Manager
ii  lintian                                               2.5.22ubuntu1                                       all          Debian package checker
ii  linux-firmware                                        1.127.20                                            all          Firmware for Linux kernel drivers
ii  linux-generic                                         3.13.0.79.85                                        amd64        Complete Generic Linux kernel and headers
ii  linux-headers-3.13.0-37                               3.13.0-37.64bdw1                                    all          Header files related to Linux kernel version 3.13.0
ii  linux-headers-3.13.0-37-generic                       3.13.0-37.64bdw1                                    amd64        Linux kernel headers for version 3.13.0 on 64 bit x86 SMP
ii  linux-headers-3.13.0-79                               3.13.0-79.123                                       all          Header files related to Linux kernel version 3.13.0
ii  linux-headers-3.13.0-79-generic                       3.13.0-79.123                                       amd64        Linux kernel headers for version 3.13.0 on 64 bit x86 SMP
ii  linux-headers-generic                                 3.13.0.79.85                                        amd64        Generic Linux kernel headers
ii  linux-image-3.13.0-37-generic                         3.13.0-37.64bdw1                                    amd64        Linux kernel image for version 3.13.0 on 64 bit x86 SMP
ii  linux-image-3.13.0-79-generic                         3.13.0-79.123                                       amd64        Linux kernel image for version 3.13.0 on 64 bit x86 SMP
ii  linux-image-extra-3.13.0-37-generic                   3.13.0-37.64bdw1                                    amd64        Linux kernel extra modules for version 3.13.0 on 64 bit x86 SMP
ii  linux-image-extra-3.13.0-79-generic                   3.13.0-79.123                                       amd64        Linux kernel extra modules for version 3.13.0 on 64 bit x86 SMP
ii  linux-image-generic                                   3.13.0.79.85                                        amd64        Generic Linux kernel image
ii  linux-libc-dev:amd64                                  3.13.0-79.123                                       amd64        Linux Kernel Headers for development
ii  linux-sound-base                                      1.0.25+dfsg-0ubuntu4                                all          base package for ALSA and OSS sound systems
rc  locale-support-plugin                                 1.10kittyhawk3                                      all          Ubiquity plugin to conditionally install packages based on locale.
ii  localechooser-data                                    2.49ubuntu5                                         all          Lists of locales supported by the installer
ii  locales                                               2.13+git20120306-12.1                               all          common files for locale support
ii  lockfile-progs                                        0.1.17                                              amd64        Programs for locking and unlocking files and mailboxes
ii  login                                                 1:4.1.5.1-1ubuntu9.2                                amd64        system login tools
ii  logrotate                                             3.8.7-1ubuntu1                                      amd64        Log rotation utility
ii  lp-solve                                              5.5.0.13-7build1                                    amd64        Solve (mixed integer) linear programming problems
ii  lsb-base                                              4.1+Debian11ubuntu6                                 all          Linux Standard Base 4.1 init script functionality
ii  lsb-release                                           4.1+Debian11ubuntu6                                 all          Linux Standard Base version reporting utility
ii  lshw                                                  02.16-2ubuntu1.3                                    amd64        information about hardware configuration
ii  lsof                                                  4.86+dfsg-1ubuntu2                                  amd64        Utility to list open files
ii  ltrace                                                0.7.3-4ubuntu5.1                                    amd64        Tracks runtime library calls in dynamically linked programs
ii  lupin-casper                                          0.55                                                all          Add support for loop-mount installations to casper
ii  lvm2                                                  2.02.98-6ubuntu2                                    amd64        Linux Logical Volume Manager
ii  m4                                                    1.4.17-2ubuntu1                                     amd64        a macro processing language
ii  make                                                  3.81-8.2ubuntu3                                     amd64        An utility for Directing compilation.
ii  makedev                                               2.3.1-93ubuntu1                                     all          creates device files in /dev
ii  man-db                                                2.6.7.1-1ubuntu1                                    amd64        on-line manual pager
ii  manage-distro-upgrade                                 2.0kittyhawk1                                       all          Disable upgrade for OEM.
ii  manage-estar-settings                                 1.1                                                 all          Energy Star related settings
ii  manpages                                              3.54-1ubuntu1                                       all          Manual pages about using a GNU/Linux system
ii  manpages-dev                                          3.54-1ubuntu1                                       all          Manual pages about using GNU/Linux for development
ii  mawk                                                  1.3.3-17ubuntu2                                     amd64        a pattern scanning and text processing language
ii  mcp-account-manager-uoa                               3.8.6-0ubuntu9.2                                    amd64        GNOME multi-protocol chat and call client (UOA plugin)
ii  media-player-info                                     21-0ubuntu1                                         all          Media player identification files
ii  memtest86+                                            4.20-1.1ubuntu8                                     amd64        thorough real-mode memory tester
ii  mesa-utils                                            8.1.0-2                                             amd64        Miscellaneous Mesa GL utilities
ii  metacity                                              1:2.34.13-0ubuntu4.1                                amd64        lightweight GTK+ window manager
ii  metacity-common                                       1:2.34.13-0ubuntu4.1                                all          shared files for the Metacity window manager
ii  mime-support                                          3.54ubuntu1.1                                       all          MIME files 'mime.types' & 'mailcap', and support programs
ii  mingw-w64                                             3.1.0-1                                             all          Development environment targetting 32- and 64-bit Windows
ii  mingw-w64-common                                      3.1.0-1                                             all          Common files for Mingw-w64
ii  mingw-w64-i686-dev                                    3.1.0-1                                             all          Development files for MinGW-w64 targeting Win32
ii  mingw-w64-x86-64-dev                                  3.1.0-1                                             all          Development files for MinGW-w64 targeting Win64
ii  mlocate                                               0.26-1ubuntu1                                       amd64        quickly find files on the filesystem based on their name
ii  mobile-broadband-provider-info                        20140317-1                                          all          database of mobile broadband service providers
ii  modemmanager                                          1.0.0-2ubuntu1.1                                    amd64        D-Bus service for managing modems
ii  module-init-tools                                     15-0ubuntu6                                         all          transitional dummy package (module-init-tools to kmod)
ii  mono-4.0-gac                                          3.2.8+dfsg-4ubuntu1.1                               all          Mono GAC tool (for CLI 4.0)
ii  mono-gac                                              3.2.8+dfsg-4ubuntu1.1                               all          Mono GAC tool
ii  mono-runtime                                          3.2.8+dfsg-4ubuntu1.1                               amd64        Mono runtime - default version
ii  mono-runtime-common                                   3.2.8+dfsg-4ubuntu1.1                               amd64        Mono runtime - common files
ii  mono-runtime-sgen                                     3.2.8+dfsg-4ubuntu1.1                               amd64        Mono runtime - SGen
ii  mount                                                 2.20.1-5.1ubuntu20.7                                amd64        Tools for mounting and manipulating filesystems
ii  mountall                                              2.53                                                amd64        filesystem mounting tool
ii  mousetweaks                                           3.8.0-2                                             amd64        mouse accessibility enhancements for the GNOME desktop
ii  mscompress                                            0.4-3                                               amd64        Microsoft "compress.exe/expand.exe" compatible (de)compressor
ii  mtools                                                4.0.18-1ubuntu1                                     amd64        Tools for manipulating MSDOS files
ii  mtr-tiny                                              0.85-2                                              amd64        Full screen ncurses traceroute tool
ii  multiarch-support                                     2.19-0ubuntu6.7                                     amd64        Transitional package to ensure multiarch compatibility
ii  myspell-en-au                                         2.1-5.4                                             all          English_australian dictionary for myspell
ii  myspell-en-gb                                         1:4.2.1-0ubuntu1.1                                  all          English_british dictionary for myspell
ii  myspell-en-za                                         1:4.2.1-0ubuntu1.1                                  all          English_southafrican dictionary for myspell
ii  mythes-en-us                                          1:4.2.1-0ubuntu1.1                                  all          English Thesaurus for LibreOffice
ii  nano                                                  2.2.6-1ubuntu1                                      amd64        small, friendly text editor inspired by Pico
ii  nautilus                                              1:3.10.1-0ubuntu9.11                                amd64        file manager and graphical shell for GNOME
ii  nautilus-data                                         1:3.10.1-0ubuntu9.11                                all          data files for nautilus
ii  nautilus-sendto                                       3.6.1-2ubuntu1                                      amd64        integrates Evolution and Pidgin into the Nautilus file manager
ii  nautilus-sendto-empathy                               3.8.6-0ubuntu9.2                                    amd64        GNOME multi-protocol chat and call client (nautilus-sendto plugin)
ii  nautilus-share                                        0.7.3-1ubuntu5                                      amd64        Nautilus extension to share folder using Samba
ii  ncurses-base                                          5.9+20140118-1ubuntu1                               all          basic terminal type definitions
ii  ncurses-bin                                           5.9+20140118-1ubuntu1                               amd64        terminal-related programs and man pages
ii  net-tools                                             1.60-25ubuntu2.1                                    amd64        The NET-3 networking toolkit
ii  netbase                                               5.2                                                 all          Basic TCP/IP networking system
ii  netcat-openbsd                                        1.105-7ubuntu1                                      amd64        TCP/IP swiss army knife
ii  network-manager                                       0.9.8.8-0ubuntu7.2                                  amd64        network management framework (daemon and userspace tools)
ii  network-manager-gnome                                 0.9.8.8-0ubuntu4.4                                  amd64        network management framework (GNOME frontend)
ii  network-manager-pptp                                  0.9.8.2-1ubuntu2                                    amd64        network management framework (PPTP plugin core)
ii  network-manager-pptp-gnome                            0.9.8.2-1ubuntu2                                    amd64        network management framework (PPTP plugin GNOME GUI)
ii  notify-osd                                            0.9.35+14.04.20140213-0ubuntu1                      amd64        daemon that displays passive pop-up notifications
ii  notify-osd-icons                                      0.8+14.04.20151016-0ubuntu1                         all          Notify-OSD icons
ii  ntfs-3g                                               1:2013.1.13AR.1-2ubuntu2                            amd64        read/write NTFS driver for FUSE
ii  ntpdate                                               1:4.2.6.p5+dfsg-3ubuntu2.14.04.8                    amd64        client for setting system time from NTP servers
ii  nux-tools                                             4.0.6+14.04.20141107-0ubuntu1                       amd64        Visual rendering toolkit for real-time applications - tools
ii  obex-data-server                                      0.4.6-0ubuntu2                                      amd64        D-Bus service for OBEX client and server side functionality
ii  obexd-client                                          0.46-1ubuntu7                                       amd64        D-Bus OBEX client
ii  oem-audio-hda-daily-dkms                              0.1                                                 all          oem-audio-hda-daily driver in DKMS format.
ii  oem-browser-defaults                                  20kittyhawk3                                        all          Customize the browser default search engine and homepage
rc  oem-config                                            2.18.8.8kittyhawk1somerville3                       all          Perform end-user configuration after initial OEM installation
rc  oem-config-gtk                                        2.18.8.8kittyhawk1somerville3                       all          GTK+ frontend for end-user post-OEM-install configuration
ii  oem-hotkey-osd                                        0.3kittyhawk2                                       all          hotkey OSD support for Watauga
ii  oem-kernel-cmdline                                    1.4kittyhawk7somerville3                            all          Add kernel parameters that will be effective after OOBE
ii  oem-superkey-workaround                               2kittyhawk2                                         all          Watauga superkey workaround configuration package
ii  oem-unity-auto-scale                                  1.0kittyhawk3somerville1                            all          Auto DPI tuning at first login.
ii  onboard                                               1.0.1-0ubuntu1                                      amd64        Simple On-screen Keyboard
ii  onboard-data                                          1.0.1-0ubuntu1                                      all          Language model files for the word suggestion feature of Onboard
ii  oneconf                                               0.3.7.14.04.1                                       all          synchronize your configuration data over the network
ii  oneconf-common                                        0.3.7.14.04.1                                       all          synchronize your configuration data over the network
rc  oobe-dim-disable                                      1.0kittyhawk1                                       all          Disables screen dimming.
ii  openjdk-6-jre:amd64                                   6b38-1.13.10-0ubuntu0.14.04.1                       amd64        OpenJDK Java runtime, using Hotspot JIT
ii  openjdk-6-jre-headless:amd64                          6b38-1.13.10-0ubuntu0.14.04.1                       amd64        OpenJDK Java runtime, using Hotspot JIT (headless)
ii  openjdk-6-jre-lib                                     6b38-1.13.10-0ubuntu0.14.04.1                       all          OpenJDK Java runtime (architecture independent libraries)
ii  openoffice.org-hyphenation                            0.7.1                                               all          Hyphenation patterns for OpenOffice.org
ii  openprinting-ppds                                     20140410-0ubuntu1                                   all          OpenPrinting printer support - PostScript PPD files
ii  openssh-client                                        1:6.6p1-2ubuntu2.6                                  amd64        secure shell (SSH) client, for secure access to remote machines
ii  openssl                                               1.0.1f-1ubuntu2.18                                  amd64        Secure Sockets Layer toolkit - cryptographic utility
ii  os-prober                                             1.63ubuntu1.1                                       amd64        utility to detect other OSes on a set of drives
ii  overlay-scrollbar                                     0.2.16+r359+14.04.20131129-0ubuntu1                 all          Scrollbar overlay
ii  overlay-scrollbar-gtk2:amd64                          0.2.16+r359+14.04.20131129-0ubuntu1                 amd64        GTK 2 module for overlay scrollbars
ii  overlay-scrollbar-gtk3:amd64                          0.2.16+r359+14.04.20131129-0ubuntu1                 amd64        GTK 3 module for overlay scrollbars
ii  oxideqt-codecs:amd64                                  1.12.7-0ubuntu0.14.04.1                             amd64        Web browser engine library for Qt (codecs)
ii  p11-kit                                               0.20.2-2ubuntu2                                     amd64        p11-glue utilities
ii  p11-kit-modules:amd64                                 0.20.2-2ubuntu2                                     amd64        p11-glue proxy and trust modules
ii  parted                                                2.3-19ubuntu1.14.04.1                               amd64        disk partition manipulator
ii  passwd                                                1:4.1.5.1-1ubuntu9.2                                amd64        change and administer password and group data
ii  patch                                                 2.7.1-4ubuntu2.3                                    amd64        Apply a diff file to an original
ii  patchutils                                            0.3.2-3                                             amd64        Utilities to work with patches
ii  pciutils                                              1:3.2.1-1ubuntu5.1                                  amd64        Linux PCI Utilities
ii  pcmciautils                                           018-8                                               amd64        PCMCIA utilities for Linux 2.6
ii  perl                                                  5.18.2-2ubuntu1                                     amd64        Larry Wall's Practical Extraction and Report Language
ii  perl-base                                             5.18.2-2ubuntu1                                     amd64        minimal Perl system
ii  perl-modules                                          5.18.2-2ubuntu1                                     all          Core Perl modules
ii  pkg-config                                            0.26-1ubuntu4                                       amd64        manage compile and link flags for libraries
ii  plainbox-provider-checkbox                            0.4-1                                               amd64        CheckBox provider for PlainBox
ii  plainbox-provider-resource-generic                    0.3-1                                               amd64        CheckBox generic resource jobs provider
ii  plainbox-secure-policy                                0.5.3-2                                             all          policykit policy required to use plainbox (secure version)
ii  plymouth                                              0.8.8-0ubuntu17.1                                   amd64        graphical boot animation and logger - main package
ii  plymouth-label                                        0.8.8-0ubuntu17.1                                   amd64        graphical boot animation and logger - label control
ii  plymouth-theme-ubuntu-logo                            0.8.8-0ubuntu17.1                                   amd64        graphical boot animation and logger - ubuntu-logo theme
ii  plymouth-theme-ubuntu-text                            0.8.8-0ubuntu17.1                                   amd64        graphical boot animation and logger - ubuntu-logo theme
ii  pm-utils                                              1.4.1-13ubuntu0.2                                   all          utilities and scripts for power management
ii  policykit-1                                           0.105-4ubuntu3.14.04.1                              amd64        framework for managing administrative policies and privileges
ii  policykit-1-gnome                                     0.105-1ubuntu4                                      amd64        GNOME authentication agent for PolicyKit-1
ii  policykit-desktop-privileges                          0.17                                                all          run common desktop actions without password
ii  poppler-data                                          0.4.6-4                                             all          encoding data for the poppler PDF rendering library
ii  poppler-utils                                         0.24.5-2ubuntu4.3                                   amd64        PDF utilities (based on Poppler)
ii  popularity-contest                                    1.57ubuntu1                                         all          Vote for your favourite packages automatically
ii  powermgmt-base                                        1.31build1                                          amd64        Common utils and configs for power management
ii  ppp                                                   2.4.5-5.1ubuntu2.2                                  amd64        Point-to-Point Protocol (PPP) - daemon
ii  pppconfig                                             2.3.19ubuntu1                                       all          A text menu based utility for configuring ppp
ii  pppoeconf                                             1.20ubuntu1                                         all          configures PPPoE/ADSL connections
ii  pptp-linux                                            1.7.2-7                                             amd64        Point-to-Point Tunneling Protocol (PPTP) Client
ii  printer-driver-c2esp                                  27~rc1-1                                            amd64        printer driver for Kodak ESP AiO color inkjet Series
ii  printer-driver-foo2zjs                                20140209dfsg0-1ubuntu1                              amd64        printer driver for ZjStream-based printers
ii  printer-driver-foo2zjs-common                         20140209dfsg0-1ubuntu1                              all          printer driver for ZjStream-based printers - common files
ii  printer-driver-gutenprint                             5.2.10~pre2-0ubuntu2                                amd64        printer drivers for CUPS
ii  printer-driver-hpcups                                 3.14.3-0ubuntu3.4                                   amd64        HP Linux Printing and Imaging - CUPS Raster driver (hpcups)
ii  printer-driver-min12xxw                               0.0.9-8ubuntu1                                      amd64        printer driver for KonicaMinolta PagePro 1[234]xxW
ii  printer-driver-pnm2ppa                                1.13+nondbs-0ubuntu4                                amd64        printer driver for HP-GDI printers
ii  printer-driver-postscript-hp                          3.14.3-0ubuntu3.4                                   all          HP Printers PostScript Descriptions
ii  printer-driver-ptouch                                 1.3-8                                               amd64        printer driver Brother P-touch label printers
ii  printer-driver-pxljr                                  1.4+repack0-3                                       amd64        printer driver for HP Color LaserJet 35xx/36xx
ii  printer-driver-sag-gdi                                0.1-3                                               all          printer driver for Ricoh Aficio SP 1000s/SP 1100s
ii  printer-driver-splix                                  2.0.0+svn315-2fakesync1                             amd64        Driver for Samsung and Xerox SPL2 and SPLc laser printers
ii  procps                                                1:3.3.9-1ubuntu2.2                                  amd64        /proc file system utilities
ii  psmisc                                                22.20-1ubuntu2                                      amd64        utilities that use the proc file system
ii  pulseaudio                                            1:4.0-0ubuntu11.1                                   amd64        PulseAudio sound server
ii  pulseaudio-module-bluetooth                           1:4.0-0ubuntu11.1                                   amd64        Bluetooth module for PulseAudio sound server
ii  pulseaudio-module-x11                                 1:4.0-0ubuntu11.1                                   amd64        X11 module for PulseAudio sound server
ii  pulseaudio-utils                                      1:4.0-0ubuntu11.1                                   amd64        Command line tools for the PulseAudio sound server
ii  python                                                2.7.5-5ubuntu3                                      amd64        interactive high-level object-oriented language (default version)
ii  python-apt                                            0.9.3.5ubuntu2                                      amd64        Python interface to libapt-pkg
ii  python-apt-common                                     0.9.3.5ubuntu2                                      all          Python interface to libapt-pkg (locales)
ii  python-aptdaemon                                      1.1.1-1ubuntu5.2                                    all          Python 2 module for the server and client of aptdaemon
ii  python-aptdaemon.gtk3widgets                          1.1.1-1ubuntu5.2                                    all          Python 2 GTK+ 3 widgets to run an aptdaemon client
ii  python-cairo                                          1.8.8-1ubuntu5                                      amd64        Python bindings for the Cairo vector graphics library
ii  python-chardet                                        2.0.1-2build2                                       all          universal character encoding detector
ii  python-commandnotfound                                0.3ubuntu12                                         all          Python 2 bindings for command-not-found.
ii  python-crypto                                         2.6.1-4build1                                       amd64        cryptographic algorithms and protocols for Python
ii  python-cups                                           1.9.66-0ubuntu2                                     amd64        Python bindings for CUPS
ii  python-cupshelpers                                    1.4.3+20140219-0ubuntu2.6                           all          Python modules for printer configuration with CUPS
ii  python-dbus                                           1.2.0-2build2                                       amd64        simple interprocess messaging system (Python interface)
ii  python-dbus-dev                                       1.2.0-2build2                                       all          main loop integration development files for python-dbus
ii  python-debian                                         0.1.21+nmu2ubuntu2                                  all          Python modules to work with Debian-related data formats
ii  python-debtagshw                                      1.12ubuntu2                                         all          Match debtags hardware:: tags against the actual hardware
ii  python-defer                                          1.0.6-2build1                                       all          Small framework for asynchronous programming (Python 2)
ii  python-dirspec                                        13.10-0ubuntu2                                      all          Python User Folders Specification Library
ii  python-distutils-extra                                2.38-1build1                                        all          enhancements to the Python build system
ii  python-gconf                                          2.28.1+dfsg-1ubuntu2                                amd64        Python bindings for the GConf configuration database system
ii  python-gdbm                                           2.7.5-1ubuntu1                                      amd64        GNU dbm database support for Python
ii  python-gi                                             3.12.0-1ubuntu1                                     amd64        Python 2.x bindings for gobject-introspection libraries
ii  python-gi-cairo                                       3.12.0-1ubuntu1                                     amd64        Python Cairo bindings for the GObject library
ii  python-glade2                                         2.24.0-3ubuntu3                                     amd64        GTK+ bindings: Glade support
ii  python-gnomekeyring                                   2.32.0+dfsg-3                                       amd64        Python bindings for the GNOME keyring library
ii  python-gobject                                        3.12.0-1ubuntu1                                     all          Python 2.x bindings for GObject - transitional package
ii  python-gobject-2                                      2.28.6-12build1                                     amd64        deprecated static Python bindings for the GObject library
ii  python-gtk2                                           2.24.0-3ubuntu3                                     amd64        Python bindings for the GTK+ widget set
ii  python-httplib2                                       0.8-2build1                                         all          comprehensive HTTP client library written for Python
ii  python-ibus                                           1.5.5-1ubuntu3.2                                    all          Intelligent Input Bus - Python support
ii  python-imaging                                        2.3.0-1ubuntu3                                      all          Python Imaging Library compatibility layer
ii  python-ldb                                            1:1.1.16-1ubuntu0.1                                 amd64        Python bindings for LDB
ii  python-libxml2                                        2.9.1+dfsg1-3ubuntu4.7                              amd64        Python bindings for the GNOME XML library
ii  python-lockfile                                       1:0.8-2ubuntu2                                      all          file locking library for Python
ii  python-lxml                                           3.3.3-1ubuntu0.1                                    amd64        pythonic binding for the libxml2 and libxslt libraries
ii  python-minimal                                        2.7.5-5ubuntu3                                      amd64        minimal subset of the Python language (default version)
ii  python-notify                                         0.1.1-3ubuntu2                                      amd64        Python bindings for libnotify
ii  python-ntdb                                           1.0-2ubuntu1                                        amd64        Python bindings for NTDB
ii  python-oauthlib                                       0.6.1-1                                             all          generic, spec-compliant implementation of OAuth for Python
ii  python-oneconf                                        0.3.7.14.04.1                                       all          synchronize your configuration data over the network (Python 2)
ii  python-openssl                                        0.13-2ubuntu6                                       amd64        Python 2 wrapper around the OpenSSL library
ii  python-pam                                            0.4.2-13.1ubuntu3                                   amd64        Python interface to the PAM library
ii  python-pexpect                                        3.1-1ubuntu0.1                                      all          Python module for automating interactive applications
ii  python-pil                                            2.3.0-1ubuntu3                                      amd64        Python Imaging Library (Pillow fork)
ii  python-piston-mini-client                             0.7.5-0ubuntu2                                      all          library for writing clients for Django's Piston REST APIs
ii  python-pkg-resources                                  3.3-1ubuntu2                                        all          Package Discovery and Resource Access using pkg_resources
ii  python-pycurl                                         7.19.3-0ubuntu3                                     amd64        Python bindings to libcurl
ii  python-qt4                                            4.10.4+dfsg-1ubuntu1                                amd64        Python bindings for Qt4
ii  python-qt4-dbus                                       4.10.4+dfsg-1ubuntu1                                amd64        D-Bus Support for PyQt4
ii  python-renderpm                                       3.0-1build1                                         amd64        python low level render interface
ii  python-reportlab                                      3.0-1build1                                         all          ReportLab library to create PDF documents using Python
ii  python-reportlab-accel                                3.0-1build1                                         amd64        C coded extension accelerator for the ReportLab Toolkit
ii  python-requests                                       2.2.1-1ubuntu0.3                                    all          elegant and simple HTTP library for Python, built for human beings
ii  python-samba                                          2:4.1.6+dfsg-1ubuntu2.14.04.12                      amd64        Python bindings for Samba
ii  python-serial                                         2.6-1build1                                         all          pyserial - module encapsulating access for the serial port
ii  python-sip                                            4.15.5-1build1                                      amd64        Python/C++ bindings generator runtime library
ii  python-six                                            1.5.2-1ubuntu1                                      all          Python 2 and 3 compatibility library (Python 2 interface)
ii  python-smbc                                           1.0.14.1-0ubuntu2                                   amd64        Python bindings for Samba clients (libsmbclient)
ii  python-support                                        1.0.15                                              all          automated rebuilding support for Python modules
ii  python-talloc                                         2.1.0-1                                             amd64        hierarchical pool based memory allocator - Python bindings
ii  python-tdb                                            1.2.12-1                                            amd64        Python bindings for TDB
ii  python-twisted-bin                                    13.2.0-1ubuntu1                                     amd64        Event-based framework for internet applications
ii  python-twisted-core                                   13.2.0-1ubuntu1                                     all          Event-based framework for internet applications
ii  python-twisted-web                                    13.2.0-1ubuntu1                                     all          HTTP protocol implementation together with clients and servers
ii  python-ubuntu-sso-client                              13.10-0ubuntu6                                      all          Ubuntu Single Sign-On client - Python library
ii  python-urllib3                                        1.7.1-1ubuntu4                                      all          HTTP library with thread-safe connection pooling for Python
ii  python-xapian                                         1.2.16-2ubuntu1                                     amd64        Xapian search engine interface for Python
ii  python-xdg                                            0.25-4                                              all          Python 2 library to access freedesktop.org standards
ii  python-zeitgeist                                      0.9.14-0ubuntu4.1                                   all          event logging framework - Python bindings
ii  python-zope.interface                                 4.0.5-1ubuntu4                                      amd64        Interfaces for Python
ii  python2.7                                             2.7.6-8ubuntu0.2                                    amd64        Interactive high-level object-oriented language (version 2.7)
ii  python2.7-minimal                                     2.7.6-8ubuntu0.2                                    amd64        Minimal subset of the Python language (version 2.7)
ii  python3                                               3.4.0-0ubuntu2                                      amd64        interactive high-level object-oriented language (default python3 version)
ii  python3-apport                                        2.14.1-0ubuntu3.19                                  all          Python 3 library for Apport crash report handling
ii  python3-apt                                           0.9.3.5ubuntu2                                      amd64        Python 3 interface to libapt-pkg
ii  python3-aptdaemon                                     1.1.1-1ubuntu5.2                                    all          Python 3 module for the server and client of aptdaemon
ii  python3-aptdaemon.gtk3widgets                         1.1.1-1ubuntu5.2                                    all          Python 3 GTK+ 3 widgets to run an aptdaemon client
ii  python3-aptdaemon.pkcompat                            1.1.1-1ubuntu5.2                                    all          PackageKit compatibilty for AptDaemon
ii  python3-brlapi                                        5.0-2ubuntu2                                        amd64        Braille display access via BRLTTY - Python3 bindings
ii  python3-cairo                                         1.10.0+dfsg-3ubuntu2                                amd64        Python 3 bindings for the Cairo vector graphics library
ii  python3-chardet                                       2.2.1-2~ubuntu1                                     all          universal character encoding detector for Python3
ii  python3-checkbox-ng                                   0.3-2                                               all          PlainBox based test runner (Python 3 library)
ii  python3-checkbox-support                              0.2-1                                               all          collection of Python modules used by PlainBox providers
ii  python3-commandnotfound                               0.3ubuntu12                                         all          Python 3 bindings for command-not-found.
ii  python3-crypto                                        2.6.1-4build1                                       amd64        cryptographic algorithms and protocols for Python 3
ii  python3-dbus                                          1.2.0-2build2                                       amd64        simple interprocess messaging system (Python 3 interface)
ii  python3-debian                                        0.1.21+nmu2ubuntu2                                  all          Python 3 modules to work with Debian-related data formats
ii  python3-defer                                         1.0.6-2build1                                       all          Small framework for asynchronous programming (Python 3)
ii  python3-distupgrade                                   1:0.220.8                                           all          manage release upgrades
ii  python3-feedparser                                    5.1.3-2                                             all          Universal Feed Parser for Python 3
ii  python3-gdbm:amd64                                    3.4.3-1~14.04.2                                     amd64        GNU dbm database support for Python 3.x
ii  python3-gi                                            3.12.0-1ubuntu1                                     amd64        Python 3 bindings for gobject-introspection libraries
ii  python3-gi-cairo                                      3.12.0-1ubuntu1                                     amd64        Python 3 Cairo bindings for the GObject library
ii  python3-httplib2                                      0.8-2build1                                         all          comprehensive HTTP client library written for Python3
ii  python3-icu                                           1.5-2ubuntu4                                        amd64        Python 3 extension wrapping the ICU C++ API
ii  python3-louis                                         2.5.3-2ubuntu1                                      all          Python bindings for liblouis
ii  python3-lxml                                          3.3.3-1ubuntu0.1                                    amd64        pythonic binding for the libxml2 and libxslt libraries
ii  python3-mako                                          0.9.1-1                                             all          fast and lightweight templating for the Python 3 platform
ii  python3-markupsafe                                    0.18-1build2                                        amd64        HTML/XHTML/XML string library for Python 3
ii  python3-minimal                                       3.4.0-0ubuntu2                                      amd64        minimal subset of the Python language (default python3 version)
ii  python3-oauthlib                                      0.6.1-1                                             all          generic, spec-compliant implementation of OAuth for Python3
ii  python3-oneconf                                       0.3.7.14.04.1                                       all          synchronize your configuration data over the network (Python 3)
ii  python3-pam                                           0.4.2-13.1ubuntu3                                   amd64        Python interface to the PAM library
ii  python3-piston-mini-client                            0.7.5-0ubuntu2                                      all          library for writing clients for Django's Piston REST APIs
ii  python3-pkg-resources                                 3.3-1ubuntu2                                        all          Package Discovery and Resource Access using pkg_resources
ii  python3-plainbox                                      0.5.3-2                                             all          toolkit for software and hardware testing (python3 module)
ii  python3-problem-report                                2.14.1-0ubuntu3.19                                  all          Python 3 library to handle problem reports
ii  python3-progressbar                                   2.3-1                                               all          text progress bar library for Python (Python 3)
ii  python3-pyatspi                                       2.10.0+dfsg-1                                       all          Assistive Technology Service Provider Interface - Python3 bindings
ii  python3-pycurl                                        7.19.3-0ubuntu3                                     amd64        Python 3 bindings to libcurl
ii  python3-pyparsing                                     2.0.1+dfsg1-1build1                                 all          Python parsing module, Python3 package
ii  python3-requests                                      2.2.1-1ubuntu0.3                                    all          elegant and simple HTTP library for Python3, built for human beings
ii  python3-six                                           1.5.2-1ubuntu1                                      all          Python 2 and 3 compatibility library (Python 3 interface)
ii  python3-software-properties                           0.92.37.7                                           all          manage the repositories that you install software from
ii  python3-speechd                                       0.8-5ubuntu1                                        all          Python interface to Speech Dispatcher
ii  python3-uno                                           1:4.2.8-0ubuntu4                                    amd64        Python-UNO bridge
ii  python3-update-manager                                1:0.196.14                                          all          python 3.x module for update-manager
ii  python3-urllib3                                       1.7.1-1ubuntu4                                      all          HTTP library with thread-safe connection pooling for Python3
ii  python3-xdg                                           0.25-4                                              all          Python 3 library to access freedesktop.org standards
ii  python3-xkit                                          0.5.0ubuntu2                                        all          library for the manipulation of xorg.conf files (Python 3)
ii  python3.4                                             3.4.3-1ubuntu1~14.04.3                              amd64        Interactive high-level object-oriented language (version 3.4)
ii  python3.4-minimal                                     3.4.3-1ubuntu1~14.04.3                              amd64        Minimal subset of the Python language (version 3.4)
ii  qdbus                                                 4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             amd64        Qt 4 D-Bus tool
ii  qpdf                                                  5.1.1-1                                             amd64        tools for and transforming and inspecting PDF files
ii  qt-at-spi:amd64                                       0.3.1-4fakesync1                                    amd64        at-spi accessibility plugin for Qt
ii  qtchooser                                             39-g4717841-3                                       amd64        Wrapper to select between Qt development binary versions
ii  qtcore4-l10n                                          4:4.8.5+git192-g085f851+dfsg-2ubuntu4.1             all          Qt 4 core module translations
ii  qtdeclarative5-accounts-plugin                        0.4+14.04.20140317-0ubuntu1                         amd64        Expose the Online Accounts API to QML applications
ii  qtdeclarative5-dialogs-plugin:amd64                   5.2.1-3ubuntu15.1                                   amd64        Qt 5 Dialogs QML plugin
ii  qtdeclarative5-friends0.2                             0.2.0+14.04.20140317-0ubuntu1                       amd64        QML Bindings for the Friends library
ii  qtdeclarative5-localstorage-plugin:amd64              5.2.1-3ubuntu15.1                                   amd64        Qt 5 localstorage QML plugin
ii  qtdeclarative5-privatewidgets-plugin:amd64            5.2.1-3ubuntu15.1                                   amd64        Qt 5 Private Widgets QML plugin
ii  qtdeclarative5-qtfeedback-plugin:amd64                5.0~git20130529-0ubuntu3                            amd64        Qt Feedback module - QML plugin
ii  qtdeclarative5-qtmultimedia-plugin:amd64              5.2.1-0ubuntu5                                      amd64        Qt 5 Multimedia QML plugin
ii  qtdeclarative5-qtquick2-plugin:amd64                  5.2.1-3ubuntu15.1                                   amd64        Qt 5 Qt Quick 2 QML plugin
ii  qtdeclarative5-ubuntu-ui-extras-browser-plugin:amd64  0.23+14.04.20140428-0ubuntu1                        amd64        Ubuntu web browser QML plugin
ii  qtdeclarative5-ubuntu-ui-extras-browser-plugin-assets 0.23+14.04.20140428-0ubuntu1                        all          Ubuntu web browser QML plugin assets
ii  qtdeclarative5-ubuntu-ui-extras0.1                    0.1+14.04.20140331-0ubuntu2                         amd64        Ubuntu UI Extra Components
ii  qtdeclarative5-ubuntu-ui-toolkit-plugin:amd64         0.1.46+14.04.20140408.1-0ubuntu1                    amd64        Qt Components for Ubuntu - QML plugin
ii  qtdeclarative5-unity-action-plugin:amd64              1.1.0+14.04.20140304-0ubuntu1                       amd64        Unity Action QML Components
ii  qtdeclarative5-usermetrics0.1                         1.1.1+14.04.20140305-0ubuntu2                       amd64        QML bindings for libusermetrics
ii  qtdeclarative5-window-plugin:amd64                    5.2.1-3ubuntu15.1                                   amd64        Qt 5 window QML plugin
ii  quilt                                                 0.61-1                                              all          Tool to work with series of patches
ii  rdate                                                 1:1.2-5                                             amd64        sets the system's date from a remote host
ii  readline-common                                       6.3-4ubuntu2                                        all          GNU readline and history libraries, common files
ii  remmina                                               1.0.0-4ubuntu3                                      amd64        remote desktop client for GNOME desktop environment
ii  remmina-common                                        1.0.0-4ubuntu3                                      all          common files for remmina remote desktop client
ii  remmina-plugin-rdp                                    1.0.0-4ubuntu3                                      amd64        RDP plugin for remmina remote desktop client
ii  remmina-plugin-vnc                                    1.0.0-4ubuntu3                                      amd64        VNC plugin for remmina remote desktop client
ii  resolvconf                                            1.69ubuntu1.1                                       all          name server information handler
ii  rfkill                                                0.5-1ubuntu1                                        amd64        tool for enabling and disabling wireless devices
ii  rhythmbox                                             3.0.2-0ubuntu2                                      amd64        music player and organizer for GNOME
ii  rhythmbox-data                                        3.0.2-0ubuntu2                                      all          data files for rhythmbox
ii  rhythmbox-mozilla                                     3.0.2-0ubuntu2                                      amd64        Rhythmbox Mozilla plugin
ii  rhythmbox-plugin-cdrecorder                           3.0.2-0ubuntu2                                      amd64        burning plugin for rhythmbox music player
ii  rhythmbox-plugin-magnatune                            3.0.2-0ubuntu2                                      amd64        Magnatune plugin for rhythmbox music player
ii  rhythmbox-plugin-zeitgeist                            3.0.2-0ubuntu2                                      all          zeitgeist plugin for rhythmbox music player
ii  rhythmbox-plugins                                     3.0.2-0ubuntu2                                      amd64        plugins for rhythmbox music player
ii  rsync                                                 3.1.0-2ubuntu0.2                                    amd64        fast, versatile, remote (and local) file-copying tool
ii  rsyslog                                               7.4.4-1ubuntu2.6                                    amd64        reliable system and kernel logging daemon
ii  rtkit                                                 0.10-3                                              amd64        Realtime Policy and Watchdog Daemon
ii  samba-common                                          2:4.1.6+dfsg-1ubuntu2.14.04.12                      all          common files used by both the Samba server and client
ii  samba-common-bin                                      2:4.1.6+dfsg-1ubuntu2.14.04.12                      amd64        Samba common files used by both the server and the client
ii  samba-libs:amd64                                      2:4.1.6+dfsg-1ubuntu2.14.04.12                      amd64        Samba core libraries
ii  sane-utils                                            1.0.23-3ubuntu3.1                                   amd64        API library for scanners -- utilities
ii  sbsigntool                                            0.6-0ubuntu7                                        amd64        utility for signing and verifying files for UEFI Secure Boot
ii  seahorse                                              3.10.2-0ubuntu1                                     amd64        GNOME front end for GnuPG
ii  secureboot-db                                         1.1                                                 amd64        Secure Boot updates for DB and DBX
ii  sed                                                   4.2.2-4ubuntu1                                      amd64        The GNU sed stream editor
ii  sensible-utils                                        0.0.9                                               all          Utilities for sensible alternative selection
ii  session-migration                                     0.2.1                                               amd64        Tool to migrate in user session settings
ii  sessioninstaller                                      0.20+bzr141-0ubuntu4                                all          APT based installer using PackageKit's session DBus API
ii  sgml-base                                             1.26+nmu4ubuntu1                                    all          SGML infrastructure and SGML catalog file support
ii  shared-mime-info                                      1.2-0ubuntu3                                        amd64        FreeDesktop.org shared MIME database and spec
ii  shim                                                  0.8-0ubuntu2                                        amd64        boot loader to chain-load signed boot loaders under Secure Boot
ii  shim-signed                                           1.9+0.8-0ubuntu2                                    amd64        Secure Boot chain-loading bootloader (Microsoft-signed binary)
ii  shotwell                                              0.18.0-0ubuntu4.4                                   amd64        digital photo organizer
ii  shotwell-common                                       0.18.0-0ubuntu4.4                                   all          digital photo organizer - common files
ii  signon-keyring-extension                              0.6+14.04.20140307-0ubuntu1                         amd64        GNOME keyring extension for signond
ii  signon-plugin-oauth2                                  0.19+14.04.20140305-0ubuntu2                        amd64        Single Signon oauth2 plugin
ii  signon-plugin-password                                8.56+14.04.20140307-0ubuntu2                        amd64        Plain Password plugin for Single Sign On
ii  signon-ui                                             0.16+14.04.20140304.is.0.15+14.04.20140313-0ubuntu1 amd64        Single Sign-on UI
ii  signond                                               8.56+14.04.20140307-0ubuntu2                        amd64        Single Sign On framework
ii  simple-scan                                           3.12.1-0ubuntu1                                     amd64        Simple Scanning Utility
ii  smartmontools                                         6.2+svn3841-1.2                                     amd64        control and monitor storage systems using S.M.A.R.T.
ii  smbclient                                             2:4.1.6+dfsg-1ubuntu2.14.04.12                      amd64        command-line SMB/CIFS clients for Unix
ii  sni-qt:amd64                                          0.2.6-0ubuntu1                                      amd64        indicator support for Qt
ii  software-center                                       13.10-0ubuntu4.1                                    all          Utility for browsing, installing, and removing software
ii  software-center-aptdaemon-plugins                     0.1.6build1                                         all          The aptdaemon plugins for software-center
ii  software-properties-common                            0.92.37.7                                           all          manage the repositories that you install software from (common)
ii  software-properties-gtk                               0.92.37.7                                           all          manage the repositories that you install software from (gtk)
ii  somerville-platform-dino                              6                                                   all          transitional dummy package
ii  sound-theme-freedesktop                               0.8-1                                               all          freedesktop.org sound theme
ii  speech-dispatcher                                     0.8-5ubuntu1                                        amd64        Common interface to speech synthesizers
ii  speech-dispatcher-audio-plugins:amd64                 0.8-5ubuntu1                                        amd64        Speech Dispatcher: Audio output plugins
ii  sphinx-voxforge-hmm-en                                0.1.1~daily20130301-0ubuntu1                        all          English sphinx acoustic model built from Voxforge audio corpus
ii  sphinx-voxforge-lm-en                                 0.1.1~daily20130301-0ubuntu1                        all          English sphinx language model built from Voxforge audio corpus
ii  sqlite3                                               3.8.2-1ubuntu2.1                                    amd64        Command line interface for SQLite 3
ii  ssh-askpass-gnome                                     1:6.6p1-2ubuntu2.6                                  amd64        interactive X program to prompt users for a passphrase for ssh-add
ii  ssl-cert                                              1.0.33                                              all          simple debconf wrapper for OpenSSL
ii  strace                                                4.8-1ubuntu5                                        amd64        A system call tracer
ii  sudo                                                  1.8.9p5-1ubuntu1.2                                  amd64        Provide limited super user privileges to specific users
ii  synaptic-i2c-hid-3.13.0-32-backport-dkms              1.6.4                                               all          synaptic-i2c-hid-3.13.0-32-backport driver in DKMS format.
ii  sysinfo                                               0.7-9                                               all          display computer and system information
ii  syslinux                                              3:4.05+dfsg-6+deb8u1                                amd64        collection of boot loaders
ii  syslinux-common                                       3:4.05+dfsg-6+deb8u1                                all          collection of boot loaders (common files)
ii  syslinux-legacy                                       2:3.63+dfsg-2ubuntu5                                amd64        Bootloader for Linux/i386 using MS-DOS floppies
ii  system-config-printer-common                          1.4.3+20140219-0ubuntu2.6                           all          Printer configuration GUI
ii  system-config-printer-gnome                           1.4.3+20140219-0ubuntu2.6                           all          Printer configuration GUI
ii  system-config-printer-udev                            1.4.3+20140219-0ubuntu2.6                           amd64        Printer auto-configuration facility based on udev
ii  systemd-services                                      204-5ubuntu20.18                                    amd64        systemd runtime services
ii  systemd-shim                                          6-2bzr1                                             amd64        shim for systemd
ii  sysv-rc                                               2.88dsf-41ubuntu6.3                                 all          System-V-like runlevel change mechanism
ii  sysvinit-utils                                        2.88dsf-41ubuntu6.3                                 amd64        System-V-like utilities
ii  t1utils                                               1.37-2ubuntu1.1                                     amd64        Collection of simple Type 1 font manipulation programs
ii  tar                                                   1.27.1-1                                            amd64        GNU version of the tar archiving utility
ii  tcl                                                   8.6.0+6ubuntu3                                      amd64        Tool Command Language (default version) - shell
ii  tcl8.6                                                8.6.1-4ubuntu1                                      amd64        Tcl (the Tool Command Language) v8.6 - shell
ii  tcpd                                                  7.6.q-25                                            amd64        Wietse Venema's TCP wrapper utilities
ii  tcpdump                                               4.5.1-2ubuntu1.2                                    amd64        command-line network traffic analyzer
ii  telepathy-gabble                                      0.18.3-0ubuntu0.1                                   amd64        Jabber/XMPP connection manager
ii  telepathy-haze                                        0.8.0-1                                             amd64        Telepathy connection manager that uses libpurple
ii  telepathy-idle                                        0.2.0-1                                             amd64        IRC connection manager for Telepathy
ii  telepathy-indicator                                   0.3.1+14.04.20140411-0ubuntu1                       amd64        Desktop service to integrate Telepathy with the messaging menu.
ii  telepathy-logger                                      0.8.0-3                                             amd64        Telepathy logger service - Daemon
ii  telepathy-mission-control-5                           1:5.16.1-1ubuntu3                                   amd64        management daemon for Telepathy real-time communication framework
ii  telepathy-salut                                       0.8.1-1ubuntu3                                      amd64        Link-local XMPP connection manager for the Telepathy framework
ii  telnet                                                0.17-36build2                                       amd64        The telnet client
ii  thunderbird                                           1:38.5.1+build2-0ubuntu0.14.04.1                    amd64        Email, RSS and newsgroup client with integrated spam filter
ii  thunderbird-gnome-support                             1:38.5.1+build2-0ubuntu0.14.04.1                    amd64        Email, RSS and newsgroup client - GNOME support
ii  thunderbird-locale-en                                 1:38.5.1+build2-0ubuntu0.14.04.1                    amd64        English language pack for Thunderbird
ii  thunderbird-locale-en-us                              1:38.5.1+build2-0ubuntu0.14.04.1                    all          Transitional English language pack for Thunderbird
ii  time                                                  1.7-24                                              amd64        GNU time program for measuring CPU resource usage
ii  tk                                                    8.6.0+6ubuntu3                                      amd64        Toolkit for Tcl and X11 (default version) - windowing shell
ii  tk8.6                                                 8.6.1-3ubuntu2                                      amd64        Tk toolkit for Tcl and X11 v8.6 - windowing shell
ii  tlp                                                   0.4-1~kittyhawk2                                    all          Save battery power on laptops
ii  tlp-rdw                                               0.4-1~kittyhawk2                                    all          Radio device wizard
ii  toshset                                               1.76-4                                              amd64        Access much of the Toshiba laptop hardware interface
ii  totem                                                 3.10.1-1ubuntu4                                     amd64        Simple media player for the GNOME desktop based on GStreamer
ii  totem-common                                          3.10.1-1ubuntu4                                     all          Data files for the Totem media player
ii  totem-mozilla                                         3.10.1-1ubuntu4                                     amd64        Totem Mozilla plugin
ii  totem-plugins                                         3.10.1-1ubuntu4                                     amd64        Plugins for the Totem media player
ii  transmission-common                                   2.82-1.1ubuntu3.1                                   all          lightweight BitTorrent client (common files)
ii  transmission-gtk                                      2.82-1.1ubuntu3.1                                   amd64        lightweight BitTorrent client (GTK+ interface)
ii  ttf-dejavu-extra                                      2.34-1ubuntu1                                       all          transitional dummy package
ii  ttf-indic-fonts-core                                  1:0.5.14ubuntu1                                     all          Core collection of free fonts for languages of India
ii  ttf-punjabi-fonts                                     1:0.5.14ubuntu1                                     all          Free TrueType fonts for the Punjabi language
ii  ttf-ubuntu-font-family                                0.80-0ubuntu6                                       all          Ubuntu Font Family, sans-serif typeface hinted for clarity
ii  tzdata                                                2015g-0ubuntu0.14.04                                all          time zone and daylight-saving time data
ii  tzdata-java                                           2015g-0ubuntu0.14.04                                all          time zone and daylight-saving time data for use by java runtimes
ii  ubuntu-artwork                                        1:14.04+14.04.20140410-0ubuntu1                     all          Ubuntu themes and artwork
ii  ubuntu-desktop                                        1.325                                               amd64        The Ubuntu desktop system
ii  ubuntu-docs                                           14.04.5                                             all          Ubuntu Desktop Guide
ii  ubuntu-drivers-common                                 1:0.2.91.11                                         amd64        Detect and install additional Ubuntu driver packages
ii  ubuntu-extras-keyring                                 2010.09.27                                          all          GnuPG keys of the Ubuntu extras archive
ii  ubuntu-keyring                                        2012.05.19                                          all          GnuPG keys of the Ubuntu archive
ii  ubuntu-minimal                                        1.325                                               amd64        Minimal core of Ubuntu
ii  ubuntu-mono                                           14.04+14.04.20140410-0ubuntu1                       all          Ubuntu Mono Icon theme
ii  ubuntu-release-upgrader-core                          1:0.220.8                                           all          manage release upgrades
ii  ubuntu-release-upgrader-gtk                           1:0.220.8                                           all          manage release upgrades
ii  ubuntu-session                                        3.9.90-0ubuntu12.1                                  all          Ubuntu session
ii  ubuntu-settings                                       14.04.5                                             all          default settings for the Ubuntu desktop
ii  ubuntu-sounds                                         0.13                                                all          Ubuntu's GNOME audio theme
ii  ubuntu-sso-client                                     13.10-0ubuntu6                                      all          Ubuntu Single Sign-On client
ii  ubuntu-sso-client-qt                                  13.10-0ubuntu6                                      all          Ubuntu Single Sign-On client - Qt frontend
ii  ubuntu-standard                                       1.325                                               amd64        The Ubuntu standard system
ii  ubuntu-system-service                                 0.2.5build1                                         all          Dbus service to set various system-wide configurations
ii  ubuntu-ui-toolkit-theme                               0.1.46+14.04.20140408.1-0ubuntu1                    amd64        Qt Components for Ubuntu - Ubuntu Theme
ii  ubuntu-wallpapers                                     14.04.0.1-0ubuntu1                                  all          Ubuntu Wallpapers
ii  ubuntu-wallpapers-trusty                              14.04.0.1-0ubuntu1                                  all          Ubuntu 14.04 Wallpapers
ii  ubuntuone-client-data                                 13.05-0ubuntu1                                      all          Data files for Ubuntu One
ii  ucf                                                   3.0027+nmu1                                         all          Update Configuration File(s): preserve user changes to config files
ii  udev                                                  204-5ubuntu20.18                                    amd64        /dev/ and hotplug management daemon
ii  udisks2                                               2.1.3-1ubuntu0.1                                    amd64        D-BUS service to access and manipulate storage devices
ii  ufw                                                   0.34~rc-0ubuntu2                                    all          program for managing a Netfilter firewall
ii  unattended-upgrades                                   0.82.1ubuntu2.4                                     all          automatic installation of security upgrades
ii  unity                                                 7.2.6+14.04.20151021-0ubuntu1                       amd64        Interface designed for efficiency of space and interaction.
ii  unity-asset-pool                                      0.8.24daily13.06.10-0ubuntu1                        all          Unity Assets Pool
ii  unity-control-center                                  14.04.3+14.04.20150916-0ubuntu1                     amd64        utilities to configure the GNOME desktop
ii  unity-control-center-signon                           0.1.7~+14.04.20140211.2-0ubuntu4                    amd64        Unity Control Center extension for single signon
ii  unity-greeter                                         14.04.11-0ubuntu1somerville1                        amd64        Unity Greeter
ii  unity-gtk-module-common                               0.0.0+14.04.20141212-0ubuntu1                       all          Common files for GtkMenuShell D-Bus exporter
ii  unity-gtk2-module:amd64                               0.0.0+14.04.20141212-0ubuntu1                       amd64        GtkMenuShell D-Bus exporter
ii  unity-gtk3-module:amd64                               0.0.0+14.04.20141212-0ubuntu1                       amd64        GtkMenuShell D-Bus exporter
ii  unity-lens-applications                               7.1.0+13.10.20131011-0ubuntu2                       amd64        Application lens for unity
ii  unity-lens-files                                      7.1.0+13.10.20130920-0ubuntu1                       amd64        File lens for unity
ii  unity-lens-friends                                    0.1.3+14.04.20140317-0ubuntu1                       amd64        Friends scope for unity
ii  unity-lens-music                                      6.9.0+14.04.20151120.2-0ubuntu1                     amd64        Music lens for unity
ii  unity-lens-photos                                     1.0+14.04.20140318-0ubuntu1                         all          Photos lens for Unity
ii  unity-lens-video                                      0.3.15+13.10.20130920-0ubuntu1                      amd64        Unity Video lens
ii  unity-scope-audacious                                 0.1+13.10.20130927.1-0ubuntu1                       all          Audacious scope for Unity
ii  unity-scope-calculator                                0.1+14.04.20140328-0ubuntu1                         all          Calculator scope for Unity
ii  unity-scope-clementine                                0.1+13.10.20130723-0ubuntu1                         all          Clementine scope for Unity
ii  unity-scope-colourlovers                              0.1+13.10.20130723-0ubuntu1                         all          COLOURlovers scope for Unity
ii  unity-scope-devhelp                                   0.1+14.04.20140328-0ubuntu1                         all          devhelp scope for Unity
ii  unity-scope-gdrive                                    0.9+13.10.20130723-0ubuntu1                         all          Google Drive scope for Unity
ii  unity-scope-gmusicbrowser                             0.1+13.10.20130723-0ubuntu1                         all          gmusicbrowser scope for Unity
ii  unity-scope-gourmet                                   0.1+13.10.20130723-0ubuntu1                         all          Gourmet Recipe Manager scope for Unity
ii  unity-scope-guayadeque                                0.1+13.10.20130927.1-0ubuntu1                       all          Guayadeque scope for Unity
ii  unity-scope-home                                      6.8.2+14.04.20131029.1-0ubuntu1                     amd64        Home scope that aggregates results from multiple scopes
ii  unity-scope-manpages                                  3.0+14.04.20140324-0ubuntu1                         all          Manual pages scope for Unity
ii  unity-scope-musicstores                               6.9.0+14.04.20151120.2-0ubuntu1                     amd64        Ubuntu One music store scope for unity
ii  unity-scope-musique                                   0.1+13.10.20130723-0ubuntu1                         all          Musique scope for Unity
ii  unity-scope-openclipart                               0.1+13.10.20130723-0ubuntu1                         all          OpenClipArt scope for Unity
ii  unity-scope-texdoc                                    0.1+14.04.20140328-0ubuntu1                         all          Texdoc scope for Unity
ii  unity-scope-tomboy                                    0.1+13.10.20130723-0ubuntu1                         all          Tomboy scope for Unity
ii  unity-scope-video-remote                              0.3.15+13.10.20130920-0ubuntu1                      amd64        Remote videos engine
ii  unity-scope-virtualbox                                0.1+13.10.20130723-0ubuntu1                         all          VirtualBox scope for Unity
ii  unity-scope-yelp                                      0.1+13.10.20130723-0ubuntu1                         all          Help scope for Unity
ii  unity-scope-zotero                                    0.1+13.10.20130723-0ubuntu1                         all          Zotero scope for Unity
ii  unity-scopes-master-default                           6.8.2+14.04.20131029.1-0ubuntu1                     all          Home scope that aggregates results from multiple scopes
ii  unity-scopes-runner                                   7.1.4+14.04.20140210-0ubuntu1                       all          desktop runner for misceallenous scopes
ii  unity-services                                        7.2.6+14.04.20151021-0ubuntu1                       amd64        Services for the Unity interface
ii  unity-settings-daemon                                 14.04.0+14.04.20151012-0ubuntu1                     amd64        daemon handling the Unity session settings
ii  unity-voice-service:amd64                             0.1+14.04.20140304-0ubuntu1                         amd64        Voice recognition service for unity
ii  unity-webapps-common                                  2.4.17+14.04.20140416-0ubuntu1                      all          Unity WebApp integration scripts
ii  unity-webapps-qml                                     0.1+14.04.20140408-0ubuntu1                         amd64        Unity Webapps QML component
ii  unity-webapps-service                                 2.5.0~+14.04.20140409-0ubuntu1                      amd64        Service for Web Apps integration with the Unity desktop
ii  uno-libs3                                             4.2.8-0ubuntu4                                      amd64        LibreOffice UNO runtime environment -- public shared libraries
ii  unzip                                                 6.0-9ubuntu1.5                                      amd64        De-archiver for .zip files
ii  update-inetd                                          4.43                                                all          inetd configuration file updater
ii  update-manager                                        1:0.196.14                                          all          GNOME application that manages apt updates
ii  update-manager-core                                   1:0.196.14                                          all          manage release upgrades
ii  update-notifier                                       0.154.1ubuntu1                                      amd64        Daemon which notifies about package updates
ii  update-notifier-common                                0.154.1ubuntu1                                      all          Files shared between update-notifier and other packages
ii  upower                                                0.9.23-2ubuntu1somerville1                          amd64        abstraction for power management
ii  upstart                                               1.12.1-0ubuntu4.2                                   amd64        event-based init daemon
ii  ure                                                   4.2.8-0ubuntu4                                      amd64        LibreOffice UNO runtime environment
ii  ureadahead                                            0.100.0-16                                          amd64        Read required files in advance
ii  usb-creator-common                                    0.2.56.3ubuntu0.1                                   amd64        create a startup disk using a CD or disc image (common files)
ii  usb-creator-gtk                                       0.2.56.3ubuntu0.1                                   amd64        create a startup disk using a CD or disc image (for GNOME)
ii  usb-modeswitch                                        2.1.1+repack0-1ubuntu1                              amd64        mode switching tool for controlling "flip flop" USB devices
ii  usb-modeswitch-data                                   20140327-1                                          all          mode switching data for usb-modeswitch
ii  usbmuxd                                               1.0.8-2ubuntu1                                      amd64        USB multiplexor daemon for iPhone and iPod Touch devices
ii  usbutils                                              1:007-2ubuntu1                                      amd64        Linux USB utilities
ii  user-setup                                            1.48ubuntu2                                         all          Set up initial user and password
ii  usermetricsservice:amd64                              1.1.1+14.04.20140305-0ubuntu2                       amd64        library for exporting anonymous metrics about users
ii  util-linux                                            2.20.1-5.1ubuntu20.7                                amd64        Miscellaneous system utilities
ii  uuid-runtime                                          2.20.1-5.1ubuntu20.7                                amd64        runtime components for the Universally Unique ID library
ii  vbetool                                               1.1-3                                               amd64        run real-mode video BIOS code to alter hardware state
ii  vim-common                                            2:7.4.052-1ubuntu3                                  amd64        Vi IMproved - Common files
ii  vim-tiny                                              2:7.4.052-1ubuntu3                                  amd64        Vi IMproved - enhanced vi editor - compact version
ii  vino                                                  3.8.1-0ubuntu1                                      amd64        VNC server for GNOME
ii  wakeonlan                                             0.41-11                                             all          Sends 'magic packets' to wake-on-LAN enabled ethernet adapters
ii  wamerican                                             7.1-1                                               all          American English dictionary words for /usr/share/dict
ii  watershed                                             7                                                   amd64        reduce superfluous executions of idempotent command
ii  wbritish                                              7.1-1                                               all          British English dictionary words for /usr/share/dict
ii  webaccounts-extension-common                          0.5-0ubuntu2.14.04.1                                amd64        Ubuntu Online Accounts browser extension - common files
ii  webapp-container                                      0.23+14.04.20140428-0ubuntu1                        amd64        Ubuntu web applications container
ii  webbrowser-app                                        0.23+14.04.20140428-0ubuntu1                        amd64        Ubuntu web browser
ii  wget                                                  1.15-1ubuntu1.14.04.1                               amd64        retrieves files from the web
ii  whiptail                                              0.52.15-2ubuntu5                                    amd64        Displays user-friendly dialog boxes from shell scripts
ii  whoopsie                                              0.2.24.6ubuntu2                                     amd64        Ubuntu error tracker submission
ii  whoopsie-preferences                                  0.12                                                amd64        System preferences for error reporting
ii  wireless-regdb                                        2013.02.13-1ubuntu1                                 all          wireless regulatory database
ii  wireless-tools                                        30~pre9-8ubuntu1                                    amd64        Tools for manipulating Linux Wireless Extensions
ii  wodim                                                 9:1.1.11-2ubuntu3                                   amd64        command line CD/DVD writing tool
ii  workaround-native-backlight-trusty                    10                                                  all          Use the option "use_native_backlight=1" for "video" kernel module
ii  workaround-set-acpi-osi                               1.4                                                 all          Set acpi_osi to Windows 2013,
ii  wpasupplicant                                         2.1-0ubuntu1.4                                      amd64        client support for WPA and WPA2 (IEEE 802.11i)
ii  x11-apps                                              7.7+2                                               amd64        X applications
ii  x11-common                                            1:7.7+1ubuntu8.1                                    all          X Window System (X.Org) infrastructure
ii  x11-session-utils                                     7.7+1                                               amd64        X session utilities
ii  x11-utils                                             7.7+1                                               amd64        X11 utilities
ii  x11-xfs-utils                                         7.7+1                                               amd64        X font server utilities
ii  x11-xkb-utils                                         7.7+1                                               amd64        X11 XKB utilities
ii  x11-xserver-utils                                     7.7+2ubuntu1                                        amd64        X server utilities
ii  xauth                                                 1:1.0.7-1ubuntu1                                    amd64        X authentication utility
ii  xbitmaps                                              1.1.1-2                                             all          Base X bitmaps
ii  xcursor-themes                                        1.0.3-1                                             all          Base X cursor themes
ii  xdg-user-dirs                                         0.15-1ubuntu3                                       amd64        tool to manage well known user directories
ii  xdg-user-dirs-gtk                                     0.10-1ubuntu1                                       amd64        tool to manage well known user directories (Gtk extension)
ii  xdg-utils                                             1.1.0~rc1-2ubuntu7.1                                all          desktop integration utilities from freedesktop.org
ii  xdiagnose                                             3.6.3build2                                         all          X.org diagnosis tool
ii  xfonts-base                                           1:1.0.3                                             all          standard fonts for X
ii  xfonts-encodings                                      1:1.0.4-1ubuntu1                                    all          Encodings for X.Org fonts
ii  xfonts-mathml                                         6ubuntu1                                            all          Type1 Symbol font for MathML
ii  xfonts-scalable                                       1:1.0.3-1                                           all          scalable fonts for X
ii  xfonts-utils                                          1:7.7+1                                             amd64        X Window System font utility programs
ii  xinit                                                 1.3.2-1                                             amd64        X server initialisation tool
ii  xinput                                                1.6.1-1                                             amd64        Runtime configuration and test of XInput devices
ii  xkb-data                                              2.10.1-1ubuntu1                                     all          X Keyboard Extension (XKB) configuration data
ii  xml-core                                              0.13+nmu2                                           all          XML infrastructure and XML catalog file support
ii  xorg                                                  1:7.7+1ubuntu8.1                                    amd64        X.Org X Window System
ii  xorg-docs-core                                        1:1.7-1                                             all          Core documentation for the X.org X Window System
ii  xserver-common                                        2:1.15.1-0ubuntu2.7                                 all          common files used by various X servers
ii  xserver-xorg                                          1:7.7+1ubuntu8.1                                    amd64        X.Org X server
ii  xserver-xorg-core                                     2:1.15.1-0ubuntu2.7                                 amd64        Xorg X server - core server
ii  xserver-xorg-input-all                                1:7.7+1ubuntu8.1                                    amd64        X.Org X server -- input driver metapackage
ii  xserver-xorg-input-evdev                              1:2.8.2-1ubuntu2                                    amd64        X.Org X server -- evdev input driver
ii  xserver-xorg-input-mouse                              1:1.9.0-1build1                                     amd64        X.Org X server -- mouse input driver
ii  xserver-xorg-input-synaptics                          1.7.4-0ubuntu1                                      amd64        Synaptics TouchPad driver for X.Org server
ii  xserver-xorg-input-vmmouse                            1:13.0.0-1build1                                    amd64        X.Org X server -- VMMouse input driver to use with VMWare
ii  xserver-xorg-input-wacom                              1:0.23.0-0ubuntu2                                   amd64        X.Org X server -- Wacom input driver
ii  xserver-xorg-video-all                                1:7.7+1ubuntu8.1                                    amd64        X.Org X server -- output driver metapackage
ii  xserver-xorg-video-ati                                1:7.3.0-1ubuntu3.1                                  amd64        X.Org X server -- AMD/ATI display driver wrapper
ii  xserver-xorg-video-cirrus                             1:1.5.2-1build1                                     amd64        X.Org X server -- Cirrus display driver
ii  xserver-xorg-video-fbdev                              1:0.4.4-1build1                                     amd64        X.Org X server -- fbdev display driver
ii  xserver-xorg-video-glamoregl                          0.6.0-0ubuntu4                                      amd64        X.Org X server -- graphics acceleration module based on OpenGL
ii  xserver-xorg-video-intel                              2:2.99.910-0ubuntu1.6                               amd64        X.Org X server -- Intel i8xx, i9xx display driver
ii  xserver-xorg-video-mach64                             6.9.4-1build1                                       amd64        X.Org X server -- ATI Mach64 display driver
ii  xserver-xorg-video-mga                                1:1.6.3-1build1                                     amd64        X.Org X server -- MGA display driver
ii  xserver-xorg-video-modesetting                        0.8.1-1build1                                       amd64        X.Org X server -- Generic modesetting driver
ii  xserver-xorg-video-neomagic                           1:1.2.8-1build1                                     amd64        X.Org X server -- Neomagic display driver
ii  xserver-xorg-video-nouveau                            1:1.0.10-1ubuntu2                                   amd64        X.Org X server -- Nouveau display driver
ii  xserver-xorg-video-openchrome                         1:0.3.3-1build1                                     amd64        X.Org X server -- VIA display driver
ii  xserver-xorg-video-qxl                                0.1.1-0ubuntu3                                      amd64        X.Org X server -- QXL display driver
ii  xserver-xorg-video-r128                               6.9.2-1build1                                       amd64        X.Org X server -- ATI r128 display driver
ii  xserver-xorg-video-radeon                             1:7.3.0-1ubuntu3.1                                  amd64        X.Org X server -- AMD/ATI Radeon display driver
ii  xserver-xorg-video-s3                                 1:0.6.5-0ubuntu4                                    amd64        X.Org X server -- legacy S3 display driver
ii  xserver-xorg-video-savage                             1:2.3.7-2ubuntu2                                    amd64        X.Org X server -- Savage display driver
ii  xserver-xorg-video-siliconmotion                      1:1.7.7-2build1                                     amd64        X.Org X server -- SiliconMotion display driver
ii  xserver-xorg-video-sis                                1:0.10.7-0ubuntu6                                   amd64        X.Org X server -- SiS display driver
ii  xserver-xorg-video-sisusb                             1:0.9.6-2build1                                     amd64        X.Org X server -- SiS USB display driver
ii  xserver-xorg-video-tdfx                               1:1.4.5-1build1                                     amd64        X.Org X server -- tdfx display driver
ii  xserver-xorg-video-trident                            1:1.3.6-0ubuntu5                                    amd64        X.Org X server -- Trident display driver
ii  xserver-xorg-video-vesa                               1:2.3.3-1build1                                     amd64        X.Org X server -- VESA display driver
ii  xserver-xorg-video-vmware                             1:13.0.2-2ubuntu1                                   amd64        X.Org X server -- VMware display driver
ii  xterm                                                 297-1ubuntu1                                        amd64        X terminal emulator
rc  xul-ext-ubufox                                        2.8-0ubuntu1                                        all          Ubuntu-specific configuration defaults and apt support for Firefox
ii  xul-ext-websites-integration                          2.3.6+13.10.20130920.1-0ubuntu1.2                   all          Firefox extension: Website Integration
ii  xz-utils                                              5.1.1alpha+20120614-2ubuntu2                        amd64        XZ-format compression utilities
ii  yelp                                                  3.10.2-0ubuntu1                                     amd64        Help browser for GNOME
ii  yelp-xsl                                              3.10.1-1                                            all          XSL stylesheets for the yelp help browser
ii  zeitgeist                                             0.9.14-0ubuntu4.1                                   all          event logging framework
ii  zeitgeist-core                                        0.9.14-0ubuntu4.1                                   amd64        event logging framework - engine
ii  zeitgeist-datahub                                     0.9.14-0ubuntu4.1                                   amd64        event logging framework - passive logging daemon
ii  zenity                                                3.8.0-1ubuntu1                                      amd64        Display graphical dialog boxes from shell scripts
ii  zenity-common                                         3.8.0-1ubuntu1                                      all          Display graphical dialog boxes from shell scripts (common files)
ii  zip                                                   3.0-8                                               amd64        Archiver for .zip files
ii  zlib1g:amd64                                          1:1.2.8.dfsg-1ubuntu1                               amd64        compression library - runtime
```
