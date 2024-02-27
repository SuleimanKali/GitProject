Basic Commands in Linux

Linux commands are a type of Unix command or shell procedure. They run on the command line interface (CLI) and interact with your system via texts and processes.

Linux commands are used to perform a variety of tasks, including displaying information about files and directories.
sudo command

sudo which is short for superuser do is a command that lets you perform tasks that require administrative permissions.

For example sudo apt upgrade is used to install and download all the latest package information available for the packages currently installed on the system.

sudo apt upgrade
pwd command

pwd stands for print working directory

It writes to standard output the full path name of your current directory.

pwd
cd command

cd stands for change directory and is used to change the current working directory.

cd .. moves one directory up.

cd
ls command

ls lists directory contents of files and directories.

ls

ls -S sorts files and directories by their sizes, listing the largest ones first.

ls -S
cat command

cat is short for Concatenate and is used to list, combine and write file content to the standard output.

cat
cp command

cp means copy and is used to copy a file to a specified location.

cp

To copy more than one file, enter the file names followed by the destination directory.

cp 2

To copy an entire directory, pass the -R flag before typing the source directory followed by the destination directory.

cp - R
mv command

mv can be used to move a file or directory to a new location. It can also be used to rename a file or directory.

mv
mkdir command

mkdir stands for make directory and is used to create a new directory.

mkdir
rmdir command

rmdir stands for remove directory and is used to delete an empty directory.

rmdir
rm command

rm stands for remove is used to delete files within a directory.

rm
touch command

touch is used to create a new empty file.

touch
locate command

locate is used to find a file in the database.

locate
find command

find is used to search for files within a specific directory and perform subsequent operations.

find
grep command

grep stands for global regular expression print and lets you find a word by searching through all the texts in a specific file.

grep
df command

The df command is used to report the system's disk space usage shown in percentage and kilobyte (KB).

df

df -m displays the file system usage in MBs while df -k displays it in KBs.

df_2
du command

du is used to check how much space a file or directory takes up.

du
head command

head displays the first ten lines of a text.

head
tail command

tail displays the last ten lines of a text. It is used to check if a file has new data or to view error messages.

tail
diff command

diff stands for difference and it compares the contents of two files. It then returns the parts that do not match.

diff
tar command

tar archives multiple files into a TAR file.

tar [options] [archive_file] [file or directory to be archived]

tar
chmod command

chmod is used to modify file permissions to control who can read, write, or execute a file.

chmod
chown command

chown is used to change ownership of a file, directory or symbolic limk to a specific username.

chown
jobs command

jobs displays all running processes and their statuses.

jobs
kill command

kill is used to terminate an unresponsive program manually.

kill
ping command

ping is used to check whether a network or server is reachable.

It is also used to troubleshoot various connectivity issues.

ping
wget command

wget lets you download files from the internet without hindering othr running processes.

wget
uname command

uname prints detailed information about your linux system and hardware.

uname
top command

top displays all the running processes and a dynamic real-time view of the current system.

top
history command

history lists up to 500 previously executed commands, allowing you to reuse them without re-entering.

history
man command

man provides a user manual of any commands and utilities you can run in the Terminal including the name, descrption, and options

man
echo command

echo displays a line of text or string using the standard output.

echo
zip, unzip commands

zip is used to compress your files into a zip file .

It is also useful for archiving files and directories hereby reducing disk usage.

zip

unzip is used to extract zipped files from an archive.

unzip
hostname command

hostname returns the system's hostname.

hostname
useradd, userdel commands

useradd is used to create a new user account.

useradd

userdel is used to delete a user account.

userdel
apt get command

apt_get is a command line tool for handling Advanced Package Tool (APT) libraries in Linux.

It lets you retrieve information from authenticated sources to manage, update, remove, and install software and its dependencies.

apt_get
nano, vi, jed commands

Linux lets users edit and manage files via a text editor, such as nano, vi, and jed.

nano.1

nano.2
alias, unalias commands

alias allows you to create a shortcut with the same functionality as a command, file name or text.

unalias deletes an existing alias.

alias, unalias
su command

su stands for switch user and allows you run a program as a different user.

su
htop command

htop monitors system resources and server processes in real time.

htop
pscommand

ps stands for process status and lists all currently running processes.

ps
