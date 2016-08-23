LinFreeze 0.9.4
===============

__NOTE:__ This script is outdated and may not work on modern versions of Linux. Use at your own risk.

__LOCALIZATION:__ I have a basic .pot file ready, so if you know another language you can use that to help. Keep the variables intact please!

# AUTHORS
  * Ryan Peters <peter232 [--at--] purduecal [--dot--] edu>
  * Spanish (es) translation: http://identi.ca/larusalka

# DESCRIPTION
  LinFreeze is a script you can use to "freeze" a user's home directory or any other directory so that file changes are not permanent.
It does this by layering a tmpfs layer on top of the user's home folder (or the directory of your choosing), where all changes will be stored.
Optionally, you may use a "static" directory to be layered on top of the directory containing temporary, read-only files and folders.

# DEPENDENCIES
  1.	`aufs` (aufs2 on Arch Linux)
  2.	`bash`
  3.	`sed`
  4.	`gzip`
  5.	A standard, UNIX-like filesystem structure with /etc/fstab and user directories in /home

# INSTALL
  1. Copy "linfreeze" to /usr/bin.
  2. Compress "linfreeze.1", the man page, with gzip.
  3. Copy "linfreeze.1.gz" to /usr/share/man/man1.

# PACKAGES [DISCONTINUED]
  Arch Linux: http://aur.archlinux.org/packages.php?ID=41504

# INSTRUCTIONS
  * run `linfreeze -h` to see a list of commands and `linfreeze -v` to see the version number.
  * `linfreeze -d [directory]` recursively 'freezes' a directory.
  * `linfreeze -f [user]` lets you 'freeze' a user.
  * `linfreeze -u` 'unfreezes' all users and removes their temporary directories.
  * `linfreeze -s [user or directory]` 'unfreezes' a specific user or directory, leaving the others untouched.
  * `linfreeze -c` removes the temporary directories for users and directories.
  * `linfreeze -l` lists the 'frozen' users and directories

# COPYING
  LinFreeze is distributed under the GPL Version 3 or any higher version.
