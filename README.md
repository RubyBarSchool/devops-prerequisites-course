# devops-prerequisites-course
devops prerequisites course freecodecamp

## Linus Basic Commands

### Basic Commands
```cmd
# Print tp screen
echo Hi
Hi

#List files & folders
ls
File.txt my_dir1 file2.txt

#Change directory
cd my_dir1

#Present Working Directory
pwd
/home/my_dir1
```

###Commands Directories
```cmd
#Make Directory
mkdir mew_directory

#Multiple commands
cd new_directory; mkdir www; pwd
/home/my_dir1/new_directory

#Make directory hierarchy

Type1
mkdir tmp/asia
mkdir tmp/asoa/india
mkdir tmp/aisa/india/bangalore

Type2
mkdir -p tmp/asia/india/bangalore

#Remove directory
rm -r /tmp/my_dir1

#Copy Directory
cp -r my_dir1 /tmp/my_dir1
```

### Commands Files
```cmd

#Create a new file ( no contents )
touch new_file.txt 

#Add contents to file
cat > new_file.txt
This is some sample contents
hihi
<CTRL + D > Exit type edit

#View contents of file 
cat new_file.txt
This is some sample contents
hihi

#copy file
cp new_file.txt copyfile.txt

#Move(Rename) file
mv new_file.txt sample_file.txt

#Remove ( Delete ) file
rm new_file.txt
```

### UserAccount
```cmd

whoami
<name>

id
information user : uid, gid, groups

su <name user2> : switch user
Password:

ls /root
ls: cannot open directory /root:  Permission denied

sudo ls /root
anacoda-fs.cfg initial-setup-ks.cfg
```
### Download files

```cmd
curl http://www.some-site.com/some-file.txt -O
some-file.txt

wget http://www.some-site.com/some-file.txt -O some-file.txt
some-file.txt
```

### Check OS Version
```cmd
ls /etc/*release*

cat /etc/*release*
```

## Linus PAckage Manager

###  RPM (Red Hat Package Manager)
```cmd
install package
rpm -i telnet.rpm

uninstall package
rpm -e telnet.rpm

query package
rpm -q telnet.rpm
```
### YUM

```cmd
install package
yum install ansible

Yum Repos
yum repolist

ls /etc/yum.repos.d

cat /etc/yum.repos.d/CentOS-Base.repo

yum list ansible

yum remove ansible

yum --showduplicates list ansible

yum install ansible-2.4.2.0
```

### Service
```cmd
# Start HTTPD service
service httpd start

# Start HTTPD service
systemctl start httpd

#Stop HTTPD service
systemctl stop httpd

#Check HTTTPD service Status
systemctl status httpd

#Configure HTTPD to start at startup
systemctl enable httpd
```

### VIM Editor
```cmd
vi index.html

# Command mode: ESC

# Insert mode: i

# Move around
< ^ v>  or hkjl

# Delete
x   or dd

# Copy & Paste
yy   or p

# Scroll Up/Down
CTRL+u and CTRL+d

# Command 
:

# Save
:w or :w filename

#Quit(Discard)
:q

# Save and Quit
:wq

# find 
/of  n 
```




