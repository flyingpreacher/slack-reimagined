Tips and Tricks for Slackware

<b>gparted needs the following and more from sbopkg:</b>

1. atkmm
2. mm-common
3. libsigc++
4. cairomm
5. pangomm
6. gtkmm

Firefox scrolling WITHOUT TEARING works in Openbox!

<b>To install pcmanfm with <i>sbopkg</i>, you need:</b>

1. kbproto
2. libfm-extra
3. libmenu-cache
4. libfm

sbopkg does NOT do dependency checking

slapt-get does dependency checking<br>
How do I get good repos added to slapt-get? (LOOK AT slapt-getrc in repo)

<b>To remove AlienBob's KDE PLASMA from Slackware Current:</b>

go into /root/5/ directory and just backtrack the directions he gives to install. For example:<br>
removepkg x86_64/deps/*.t?z<br>
follow with /deps/telepathy/ and /kde directories

<b>To change KDE icon themes, go into ~/.kde4/share/icons/</b>

Use "less" to see what files are installed by a package. <b>You can KEEP YOUR SYSTEM CLEAN this way!</b>

pkgtool stores its packages in /var/log/packages, scripts in /var/log/scripts

<b>Loading modules is done in /etc/rc.d/rc.modules</b>

Add blacklists to /etc/modprobe.d/ with "blacklist.conf" files

