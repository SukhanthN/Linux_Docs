#Linux

	What is linux:
	> Linux is an open source operating system (OS) and IT infrastructure platform.
	> It was originally developed by linus Torvalds in 1991.
	> First version released in 1994.
	> The heart of the OS is the Linux Kernel.
	> Linux can be used as a Server or a Desktop.
	> Linux is the layer between application and hardware.
	
	COPYLEFT LICENCES:
	Linux is released under the GNU general public license(GPL):
	That means anyone can run, study, share, and modify the softawre. The modified code can also be 
	redistributed, and even sold, but must be under the same license.
	
	Lesser GNU public license (LGPL):
	The GNU lesser public license is a free softawre license published by the free softawre foundation (FSF).
	
	Why linux is better:
	> Linux Protects your computer.
	> Reporting Bugs.
	> Freedom.
	> Enjoy Free and Unlimted Support.
	> Don't pay $100 for your OS.
	
	Linux in Cloud:
		When is comes to cloud even on Microsoft's Azure, more than 60% of the inages on the Azure
	Marketplace and nearlly !/3 of virtual machines are Linux-based. Meanwhile, Amazon Web Services,
	Google Cloud and Orcale Platform up multiple distributions of Linux in their publicly available
	images.
		 
	Linux Future Exensibility:
		Linux continues to be the operating of the future, with more systems depending on it's
	stability and Exensibility.
	
	Linux Innovation:
	> Web 2.0 built on top Linux.
	> The Cloud revolution was founded on Linux.
	> Big data solutions, softawre-based storage application, and softawre enabled networking are 
	  Linux based.
	> Microservices and containerized applications are coming from the open source community
	  around Linux.
	> The innovations of the future will be built using Linux.
	
	Linux Distributions:
	> Different Linux distributions with different goals and criteria for selecting and supporting
	the sotware.
	> Simply Linux Kernel plus Addtional softawre.
	> Each distribution can have a different focus.
	> Popular Distributions are:
		> RED HAT.		> CENTOS.
		> FEDORA. 		> OEL.
		> UBUNTU.		> MINTOS.
		> OPEN SUSE.	> ARCH LINUX.
		> KALI LINUX. 	> MANDRIVA.
		
	WHAT IS RED HAT:
	> Red Hat, Inc. is an American multinational softawre company providing-source softawre
	products to the entriprise company.
	> Founded in 1993, Red Hat has its corporate headquaters in Raleigh, North Carolina, with other offices
	worldwide.
	
	Why Red Hat Linux:
	> red Hat Entreprise Linux is the world's leading entreprise Linux platform It's an open source OS.
	> It's the foundation from which you can scale existing apps-and roll out emerging technologies-across 
	bare-metal, virtual, container, and all types of cloud enviroments.
	
	Red Hat Popularity:
		> Banks.
		> Airlines.
		> Telecoms.
		> Healthcare.
		
	Red Hat Enterprise Linux8 (RHEL8):
	> Any cloud, Any workload, One OS.
	> Red Hat 8 is very inteligent and matured operating system espicetlly designed for cloud applications. Red Hat 8 
	supports 100% the latest trending applicatins.
	> Modern IT is Hybrid IT. But turning a sprawing ecosystem into a true hybrid enviroment requironment requires an
	intelligent OS that makes those things possible. That OS is Red Hat Entreprise Linux 8.
	> Traditional datacentres to public cloud services-into a true hybrid enviroment requires a few things.
	anywhere. Yhere's an operating system that makes thoese things possible.
	
	Linux Architecture:
		Every linux operating system has 4 layers.
				User Layer
					↓
				Shell Layer
					↓
				Kernel Layer
					↓
				Hardwaer Layer
	
	The Shell:
		> Shell is like a container. What they contaies, They contaies unix or linux commands. Every command executes from the container only.
		> Interface between users and Kernel O/S.
		> In Linux, we usually means a command line shell.
		> The shell is replaceable on a user-by-user basics.
		> In enables easy remote and automated administraton.
		> The shell is most commonly used to run commands.
		
	Types of Linux Shells:
		> GNOME (GNU Network Object Model Enviroment)
		> KDE (K Desktop Enviroment)
		> Sh (Bourne Shell)
		> Bash (Bourne Again Shell)
		> ksh (Korn Shell)
		> csh and tcsh (tee-see-shell)
		> zsh (z shell)
		
		Find your shell: > echo $0
	
	Linux Kernel:
	> Kernel is a heart of Linux OS.
	> The Kernel is the essential centre of a computer operating system.
	> It was interface between shell and hardware.
	> What the kernel does:
			> Scheduling running programs.
			> Managing hardware.
			> Managing Memory.
			> Manages System Security.
			> Supports user programs.
	> What runes with in thr kernel:
			> Device drives.
			> Networking.
			
	User Spaces & Process:
	User Spaces:
		> User Spaces consists of all processes running outside the Kernel.
	Processes:
		> Each Process has its own a private virtual memory space, a security context,
		a state, a process id number.
		> Types of process:
			> User Process.
			> Daemon process.
			> Kernel thread.
		
	Client Class OS : 		Win7, win10
	Server Class OS :		Windows server 2008 r2, 2012, 2012 r2, 2016, 2019
------------------------------------------------------------------------------------------------------------------------------
#INSTALLATION OF Linux:
	
	> Install and configuring the linux Servers on VMware work station and orange virtual BOx.
	> Install DVD ISO, Everything ISO, Minimal ISO.
	
		for installation we have configure the 
		LOCALIZATION:- Data and time, Keyboard, Langauge Support.
		
		SECURITY:- Security Policy.	(go with default otion)
		
		SOFTWARE:- Installation Source (auto selection or On the network), Software Selection (select the base enviroment minimal installation or server with GUI or Basic web sever. 
		
		SYSTEM:- Installation Destination(partitation section select the automatically configure partitation or manual partitation) (disk partitation). KDMP (), NETWORK & HOST NAME (Enable Ethernet configure the network with automatic DHCP or manually configure the network IPV4 - settings)
		
		CONFIGURATION: USER SETTINGS:- Adding root password and user creation 
	
	
------------------------------------------------------------------------------------------------------------------------------

we can create 60 thousend user accounts.
	
	(variables declaration)	

	> echo $0					(find the shell)
	> ps -ef | grep httpd		(
	> export PS1='Public-EC2$ ' (for change machine name)
	
	> ./filename.sh				(run the script)
	> sh filename.sh 			(run the script)
	
	> scp -rv test.zip sukhanth@52.254.11:/home/mayur					(copy file one server to another in linux)
	> scp -i /home/kumar/test.pem sukhanth@52.254.11:/home/sukhanth		(copy pem file)
	
	> curl
	> curl -sL					(browse the url)
	> tuned-adm					(
	
	> whoami					(to check current login username)
	> logname					(to check current login username)
	> who						(display who is online)
	> w 						(display the active users list)
	> id						(Gives information about currently workig user)
	> id root					(To view information about root)
	> id-u						(Tells you id)
	> id-un  					(Tells you username)
	> users						(Gives information about logged in users)
	
	> uname						(to get basic information about the OS)
	> uname -a					(everything details about machine)
	> uname -r 					(display current kurnal version)
	> uname -i 					(show current archectutire of the OS)
	> arch	 					(show current archectutire of the OS)
	> cat /etc/redhat-release	(display kurnal release)
	
	> grep 						(Search for a string within an output)
	> grep filename /etc/passwd	(Search for a string within an output)
	
	> w 						(display the active users list)
	> su- / sudo su				(switch to root user (ec2-user is default user))
	
	> which ls					(Search for a string)
	> sudo						(allow user to execute the command with root level permissions)
	> sudo su					(Switch to root user)
	> su 						(switch between users)
	> exit						(Exit from root user to ec2-user)
	
	> clear						(Clears the screen)
	> cls						(Clears the screen)
	> ctrl+l					(Clears the screen)
	
	> man commandname			(to get the info about the command)
	> info commandname			(to get the info about the command)
	> commandname --help		(to get the info about the command)
	> command --help			(to get the info about the command)
	
	> date						(current date)
	> cal 						(for calender)
	> cal 2020					(calender for specific year)
	> cal feb 2020				(month and year)
	> cal 02 02 2020			(day month year)
	> history
	> cd 						(change diretory)
	> pwd						(print working directory)
	
	> ls						(List the files/folders)
	> du -sh filename			(display the file size)
	> ls -a						(List all including hidden files)
	> ls -l 					(List all files with details)
	> ls -l filename			(List all details about specific file)
	> ls -la					(long list all files)
	> ls -lt					(long list recent modified files)
	> ls -ltr					(long list recent modified files reverse order)
	> ls j*						(listing file starts with the java)
	> ls *.cfg					(listing files withextension with .cfg)
	> ls *.py					(listing files withextension with .py)
	> ls ???					(listing three charter files)
	> ls ??e					(listing three chaacter file last word should be 'e')
	> ls -l backup.tar*
	
		Identifying Linux File Types
			- 	> regular file
			d	> directory
			c 	> chaacter device file
			b	> block device file
			I	> symbolic link
			s 	> local socket file
			P 	> named pipe
			
	> cat filename				(open the file)		
	> cat > filename 			(create a file with some data) (ctrl+d for come out)
	> cat >> fielname 			(add more data)
	> cat -n filename			(open the file data with numbers)
	
	> ls -l > filename			(saves the output with file)	(over write)
	> ls -l 1> filename 		(saves the output with file)	by defult there is 1	(over write)
	> ls -j 2> filename			(saves the output with file unsucessful data) 	
	> ls -l a aa >>	filename	(saves the output with file)							(up end write)
	> ls -l a aa 1>> filename	(saves the output with file sucess data only)
	> ls -l a aa 2>> filename 	(saves the output with file sucess data shows unsucessful data)
	> ls -l a aa &>> filename 	(saves the output with file sucess data unsucessful data)	ambus.
	
	> less filename				(display the content page by page)
	> more filename				(same command)
	
	> touch filename			(Create blank/empty files)
	> touch filename			((for change the file time stamp)
	
	> rm filename				(remove a empty file)
	> rm -i filename			(romove file interactive method)
	> rm -f filename			(romove file forcefully)
	> rm -i j*					(remove file name starts with j)
	> rm -ri ???				(remove three chaacter files)
	
	> rm -r 					(remove directory with files)
	> rm -ri					(remove directory with files interactivelly)
	> rmdir						(remove only empty directory)
	> rm -rf					(Delete a directory that contains files with forcefully)

	> mkdir 					(create a directory)
	
	> mkdir name1 name2			(create multiple directories)
	> mkdir {1..3}				(create multiple directories)
	> mkdir -p /me1/h2/h3/h4	(one on one directory)
	
	> tree
	> pstree
	> tree directoryname
	> ls -R directoryname 
	
	> cp									(copy and paste)	(cp filename destination name/)
	> cp -i filename source					(copy file interactive method)
	> cp -f filename source					(copy file foucefully)
	> cp -ri directoryname directoryname 	(copy directory to directory)	
	> cp -rf *.cfg destination				(copy all .cfg file to destination)
	> cp -ri ??? destination				(copy three chaacter files to destination)
	
	> mv 									(cut and paste)
	> to rename a file we use "mv" command :  mv oldfilename newfilename
	
	> sort filename				(get the information alphabetical)
	> nl filename				(add numbers to file info lines)
	> fmt filename				(split latge file into multiple files)
	
	> join file1 file2			(check the both file and if first word is matched)
	> join file1 file2 > filename	(it adds the both file information)
	
	> head 					(file name will show first ten lines)
	> tail					(file name will show first ten lines)
	> head -n 2				(list first two lines)
	> tail -n 2				( list lasr two lines)
	> head -5 				(file name will show first five lines)
	> hail -5 				(file name will show last five lines)
	> head-5 f2 | tail-l
	
	> wc filename 			(shows the lines words and number of charters in the file)
	> wc -l filename 		(for show only lines in the file)
	> wc -w filename 		(for show only words in the file)
	> wc -c filename		(for show only charter in the file)
	> date | wc -l
	> cal | wc -l
	
	> wget
	> tar cvf tesr.tar filename 	(to zip the files)
	> gzip filename					(to compress the file size)
	> tar ztf filename				(to grt the compressed file content)
	> tar zxvf filename				(to unzip the compressed file)
	> unzip							(unzip the files)
	
	> find / -name *httpd*			(enter) 
	
	> whereis	file/directory name		(search the file/directory)
	
	> echo 	(Print any text that follows the command)
	> echo "<h1> sukhanth </h1>" > index.html
	> echo "<h2> sukhanth </h2>" >> index.html
	> echo "<h2> sukhanth </h2>" >> /var/www/html/index.html
	
--------------------------------------------------------------------------------------------------------------------------

PERMISSIONS MANAGEMENT ON FILES AND DIRECTORIES:-

Numerical notation:

	> chmod 			(to modify permissions of a file)
	> chmod -R DN		(give permissions to entire directory)

-rw-r--r--1 root 0 apr 12 02.44 a.txt

	> - 	(indicate file)
	> d 	(indicates directory)
	read 		> r	> 4
	write 		> w	> 2
	execute 	> x	> 1
	
chmod xxx 	a.txt
chmod 700 	a.txt

r+w+x	> 	4+2+1	 > 7
r+w+-	> 	4+2+0	 > 6
r+-+x	> 	4+2+1	 > 5
r+-+-	> 	4+2+1	 > 4
-+w+x	> 	0+2+1	 > 3
-+w+-	> 	0+2+0	 > 2
-+-+x	> 	4+2+1	 > 1
-+-+-	> 	4+2+1	 > 0

alphabetical notation:

owner  		> u
group 		> g
others	 	> o

everyone	> a

	+ 	(+ symbol is use for give the prmission)
	- 	(- symbol is use for remove the permission)
	
chmod o+r f3 	(file/directory name)
chmod o-r f3 	(file/directory name)

chmod u-x,g+x,o+r f3 	(file/directory name) 

chmod u-rwx,g+rx,o+wr f3 	(file/directory name) 

VIM / NANO EDITORS:

VIM Editor : 

	> vim filename		(Open this file in VIM editor)
	> vim -R 			(open the file read only mode)
	> WC fielname 		(word count)
	> i			 		(INSERT Mode)
	> o-r				(open up a new line)
	> l 				(move the curser right)
	> k 				( up line)
	> j					(down line)
	> x 				(delete one letter)
	> dw				(delete entire word)
	> db				(delete work backword)
	> dd 	 			(for delete a line)
	> d$				(delete to end of line)
	> 10G				(for move to 10th line)
	> yy				(for copy the line)
	> p					(to paste below)
	> esc			 	(ReadOnly Mode)
	> :wq				(Write and Quit (Write changes to file and quit the editor)
	> :q!				(Quit the Editor without writing the changes)
	> :qa				(
	
	> vimdiff filename filename			(edit two files at a time)
	
	> sudo apt install vim

nano Editor :

	> nano filename 	(Open this file in nano editor)
	> ctrl+o			(for worite out and save)
	> ctrl+x			(for comeout/exit)
	> ctrl+we			(for search)
	
-----------------------------------------------------------------------------------------------------------------------------

#USER MANAGEMENT SERVICE:

In Linux we have 3 types of Users:
	> Super or root user: User is most powerful user. He is the administrator user.
	> System User: 		  Users created by the software or applications.
	> Normal User:		  Normal users are the created by root user.
	
	--> root or super user (admin) - UID 0 	root 	/root	/bin/bash
	--> system user _ UID 1-200 (mapped) & 201-999	ftp,sh,apache	/var/ftp,etc	/sbin/nologin
		(reserved/allocated based on installed services)	visitor,ec2-user	/home/username	/bin/bash
	--> Regular users - UID 1000+
	
	> useradd username			(to add user)
	> passwd username 			(to add password)
	> userdel username 			(to delete an user)
	
	> cat /etc/passwd 			(This file contains users information)
	> /etc/shadow				(This file contains passwoed information)
	> /etc/group 				(contains group info location) (switch to root user to manage all other users)
	
	> getent passwd username	(entry in passwd file)
	> getent shadow username	(entry in shadow file)
	> getent group username		(entry in group file)
	> getent gshadow username	(entry in gshadow file)
	
	> usermod 					(to edit user)
	> usermod -aG wheel username(add user to wheel group)
	> usermod-a-G/-aG wheel UN	(To change users group)
	> wheel group				(A group where it can control access on su or sudo)
	> id username				(to verify the groups)
	> usermod -L username		(to lock the user)
	> usermod -U username		(to un-lock the user)

	GROUPS:
	
	Every group will have unique GID
	Used to manage shared access to files / directories
	Users can be member of multiple group also
	
	> Group Database files:
	/etc/group 						(contains group info)
	Note: switch to root user to maange all other users....
	
	> chown 						(to change the ownership)
	> chgrp 						(to change the group)
	
	> groups						(tells you what group you belongs to)
	> groups username				(tells you specified user member of how many groups)
	> groupadd groupname			(to create group)
	> groupdel groupname 			(delete the group)
	
	> usermod -aG GN UN 			(add user to group)
	> gpasswd -a UN GN				(add user to group)
	
	> chown :GN filename			(for change the file group)
	
	Shadow file explanation:-
	
	> change username						(change password epire date)
	> change -l username					(password info for perticular user)
	
	> usermod -s /sbin/nologin username		(to remoce from shell)
	> usermod -s /sbin/bash UN 				(to add to shell)
	--------------------------------------------
	> useradd 	(name)
	> adduser	(ubuntu)
	> visudo	(#Allow members of group sudo to execute any command)
	> %teja ALL=(ALL:ALL) NOPASSWD:ALL		(exit)
		
	> visudo								(press i to serch wheel group and remove = and space and save) 
	> useradd -a -G nandam 					(user name)
	
	user management advance:-
	
	How to setup password for ec2-user
	How to login as newly created user
	
	> vim /etc/ssh/sshd_config		(serch for PasswordAuthentication enter yes)	(enable password to ec2-user)
	after that restart the sshd
	> service sshd restart
	
	> vim etc/ssh/sshd_cofig		(authencating ssh login for users) 
	
	AllowUsers sukhanth root
	AllowGroups administrators
	
	> systemctl restart sshd

------------------------------------------------------------------------------------------------------------------------------
#BASIC NETWORK COMMANDS: 		NETWORKING ON LINUX:

	> hostname					(it gives a system name (computer name))
	> hostnamectl				(show complete details of server)
	> env 						( display the all enviromental variables)
	> hostname					(it gives a system name (computer name))
	> hostnamectl set-hostname sukhanth		(for change the host name)
	> cat /etc/hostname			(display hostname list location)
	
	> ping google.com			(call brower)
	> ping google.com -c4 		(pocket internet gopher)
	> dig domainname			(domain infomation gopher)
	> dig ns sukhanth.ml		(shows the name server records)
	> mtr domainname 			(connectivity between local device and website)
	> ss						(shows the port status)
	> ss -lt					(shows services running on TCP ports)
	> ip addr 					(display IP info)
	> ifconfig					(display IP info)
	> ip address show			(display IP info)
	> ip a s					(display IP info)
	> cd /etc/sysconfig/network-scripts/		(it shows the all ip infomation stored)
	> cat ifcfg-etho
	
	> netstart					(display all the active connections)
	
	> netstart -a 			(To show both listening and non-listening sockets.)
	> netstat -at 			(To list all tcp ports)
	> netstat -au			(To list all udp ports)
	> netstat -l			(To list only the listening ports)
	> netstat -lt			(To list only the listening tcp ports)
	> netstat -lu			(o list only the listening udp ports)
	
	NIC Card Information:
	Regular Systems : enp0s3: UP (en: Ethernet, p0 : Port 0, s3: slot 3)
	AWS: etho

	> cd /etc/sysconfig/network-scripts/**  	: Network config filespath	(network file stored place)
	
	> curl http://169.254.169.254/latest/meta-data/
	> curl http://169.254.169.254/latest/meta-data/local-ipv4 > /home/ec2-user/privateip.txt

------------------------------------------------------------------------------------------------------------------------------

MANAGING PROCESSES IN LINUX PACKAGE MANAGEMENT:

	> ctrl+z 	 	(stop the running process)
	> jobs 			(it shows the suspended as well as background process)
	> ps 			(prodcess currentlly running on the terminal)
	> ps a 			(display all process current terminal)
	> ps ax			(display all process on all users)		> ps aux 	(same info in a clenar manaer)
	> ps faux 		(shows process tree also)
	> quit			(quit)
	> top 			(show process, contineously running list/moitor system realtime(press z gives colour)
	> ping
	> tree
	> pstree		(amazon linux)

	> pstree -p | less	(get the info with process ID)
	> process state		R: Running
						S: Sleeping (interrutible)
						D: sleepin
						T: Suspended
						Z: Zombie (deformation)
						
	> uptime		(gives system uptime information howmuch time running)
	> Free			(shows free memory)
	> kill	PID		(kill the process enter process ID)
	
Package Management (rpm vs yum):
	A package format is a type of archive containing computer programs and
	additional metadata needed by package managers.
	In simple, software installations, manages and uninstallation will be taken care
	by Linux Package Manager.
	
	rpm is the Package manager for RedHat systems
	Rpm: RedHat Package Manager.
	
	> serch google > rpm for  httpd	> copy the link
	> wget packagename
	> rpm -ivh package name
	problem with rpm is, it cannot resolve dependencies automatically, so we have YUM
	> cd /etc/yum.repos.d/
	
	To install epel repository:
	
	> yum install -y https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
	> yum-config-manager -enable epel
	> yum repolist
	
	> yum history
	> yum history ID
	> yum history undo ID
	> Yum history rollback ID
	> yum history info ID
	> /var/log/yum.log
	---------------------------------
	Apache web application configuration:
	SSl/TLS Certificate genetation using ACM
	configuring http to https domain redirection
	---------------------------------
	Install Apache Amazon Linux2:
	
	> yum install packagename			(install package)
	> service httpd start				(start the service)
	> systemctl start httpd.service		(start the service)
	> chkconfig httpd on				(service will enable after server restart)
	> serivce httpd status				(get the infi of the service)
	> systemctl status httpd			(get the infi of the service)
	
	> cd /var/www/html					(index file path httpd)
	> cd /var/log/httpd					(log path httpd)
	> cd /usr/share/httpd/					(default page path)
	---------------------------------
	http to https redirection for Apache:

	Open Apache configuration file : > cd /etc/httpd/conf/httpd.conf
	Add a rewrite rule to the VirtualHost section as below

	<VirtualHost *:80>
	RewriteEngine On
	RewriteCond %{HTTP:X-Forwarded-Proto} =http
	RewriteRule .* https://%{HTTP:Host}%{REQUEST_URI} [L,R=permanent]
	</VirtualHost>

	Save file and restart the service

	> service httpd restart
	---------------------------
	Install nginx Amazon Linux2:
	
	> yum install packagename			(install package)
	> service nginx start				(start the service)
	> systemctl start nginx.service		(start the service)
	> chkconfig nginx on				(service will enable after server restart)
	> serivce nginx status				(get the infi of the service) 
	
	> cd /usr/share/nginx/html			(index file path nginx)
	> cd /var/log/nginx					(log path nginx)
	> cd /usr/share/nginx/html			(default page)
	

	Http to https redirection for Nginx:

	Open nginx configuration file :  /etc/nginx/nginx.conf
	Add a below entry

	server {
		listen 80;
		server_name _;
		if ($http_x_forwarded_proto = 'http'){
		return 301 https://$host$request_uri;
		}
	}

	Save file and restart the service
	
	> service nginx restart
	
	-----------------------
	Install Apache Ubuntu:
	> apt install apache2
	> sudo ufw allow 'Apache Full'
	> apt-get purge apache2 apache2-utils apache2-bin apache2.2-common 	(remove web application)

	------------------------
	Install Apache Cent OS:
	> yum install httpd
	> systemctl start httpd
	> systemctl enable httpd
	> systemctl status httpd
	> systemctl status firewalld 
	> systemctl stop firewalld
	
	--------------------------

	rpm : Redhat package manager
	yum : Yellowdog Update manager
	
	> firewall-cmd --permanent --add-port=80/tcp
	> firewall-cmd --permanent --add-port=443/tcp
	> firewall-cmd --reload
	
	> yum install packagename			(install package)
	> yum remove packagename			(uninstall package) 
	> yum info packagename				(package name)
	> apt install packagename			(Ubuntu)
	> apt-get install packagename		(Ubuntu)
	
	> service httpd start				(start the service)
	> systemctl start httpd.service		(start the service)
	> systemctl start httpd				(start the service)
	> chkconfig httpd on				(service will enable after server restart)
	> serivce httpd status				(get the infi of the service)
	> systemctl status httpd			(get the infi of the service)
	
	> rpm -q httpd						(version of the package)
	> rpmquery httpd					(version of the package)
	> httpd -valid						(version of the package)
	
	------------------

	> yum install tree -y
	> yum install stress -y				(To create stress on ec2 machine)
	> sudo amazon-linux-extras install epel -y
	> sudo yum install stress -y
	> stress --cpu 8 --io 4 --vm 2 --vm-bytes 128M --timeout 10s
	> sudo top 	
	> yum install htop -y 				(cpu utilization)
	> yum install tmax					(terminal multiplex)
	
------------------------------------------------------------------------------------------------------------------------------

STORAGE MANAGEMENT ON LINUX:

	In Linux, All torage devices appears in /dev
	
	/dev/sda/ and sda1		(sda-->xvda)
							(s-SCSI/SATA Disk)
							 Disk A
							 Partition 1

	/dev/xvda  : Entire disk 	
	/dev/xvdal : SCSI/SATA Disk A Partition 1
	
	EBS: Elastic Block Storage
		 Storage option for ec2 instances
		 Make sure instance and volume are in same  AZ
		 
	> lsblk			( list all block devices in the liux machine) (to find how many drives we have)
	> fdisk		
	> fdisk -l
	> mount
	> umount
	> umount -d
	> df
	> df -h			(stoarage usage deatails)
	> df -Th		(shows info about volumes and mount points)

	> file -s /dev/volumename		(if you see only "data" that means there is no file system avaliable with in this newelly associated volume you need to setup file system for this block device)	(information aout the file system type)
	> mkfs -t xfs /dev/volumename 	(creating a file system)
	
	Run xfsprogs package if any error comes "mkfs.xfs" not found perform this > yum install xfsprogs
	
	"mkfs.xfs is not available" your getting such kind of isue you need to exegute  ( > yum install xfsprogs)

	> mkdir Suhkanth			(create directory)
	> mount /dev/volumename		(mound volume)
	
	Add an entry in fstab for permanent mount:
	
	> cp /etc/fstab/ /etc/fstab.bkp		(create backup for safe side)
	> cat /etc/mtab
	> vim /etc/fstab					(gives us information about what need to write in fstab)
	> mount -a
	> umount
	> umount -d /dev/volumename			(umount volume)
	
Extending the File System:
	
	> fiel -s  /dev/xvd* 				(to get the file system info)
	> growpart /dev/xvda 1				( 1 is volume ID)
	> xfs_growfs -d /	enter			(resize the volume)
	> xfs_growfs /dev/volume name		(resize the volume)
	> cat /dev/							(attachment details)
	
	> cat /etc/fstab					(to get the volume ID file system details)
	
	if you don't find xfs_growfs as a valid command, Install "xfsprogs" 

	
	Shared Storage for EC2 with EFS:
	
	supports the network file system version 4 (NFSv4.1) protocal
	no pre-provisioning required
	can scale up to the petabytes
	EFS can support thousends of concurrent connections
	need to manage permissions at file level/directory level
	
	EFS lab:

	> sudo mount -t nfs4 -o nfsvers=4.1,rsize=1048576,wsize=1048576,hard,timeo=600,retrans=2,noresvport fs-0105c444db24d1ebb.efs.us-east-1.amazonaws.com:/ directory name/

	> umount 		(mount point)


-----------------------------------------------------------------------------------------------------------------------------

#CRONTAB AND DATETIMECTL MANAGEMENT:
	
	timedatectl command
	corntab command
	
	> timedatectl 							(large info about time and date)
	> timedatectl list-timezones			(list the all time zones)
	  /asia 								(for filter)
	> timedatectl set-timezone Asia/kolkata	(set to time zone) perfom this operation as a sudo user.
	> date									(shows the date and time)
	> cat etc/localtime						(
	> timedatectl set-ntp off				(while coming to default time)
	> timedatectl set-time 09:00:00			(set the time) 

---------------------
#CRONTAB:
	Crontab is basically a task sheduler for specific time for run a program, or send a E-mail, or Display a msg.

	> cd /etc/crontab						(crontab location)
	> crontab -l							(list crontab users)
	> crontab -e							(crontab for root user)
	
------------------------------------------------------------------------------------------------------------------------------
#SHELL SCRIPT:



		SHELL SCRIPT (Simple Shell Script to create 10 files)
		
	> Simple Shell Script to create 10 files.
		> select the folder
		> while [ $I -lt 11 ]
		> do
		> echo $(date) > file$I
		> sleep 5
		> I=$(( $I + 1 ))
		> done
--------------------------------
		
#!/bin/bash
sudo su
yum update -y
yum install httpd -y
cd /var/www/html
echo "This is web application server" > index.html
service httpd start
chkconfig httpd on


#!/bin/bash
sudo su
yum update -y
yum install httpd -y
cd /var/www/html
echo "<body bgcolor="33A8FF"> <h1 style="color:red;"> This is web application server blue </h1>" > index.html
service httpd start
chkconfig httpd on


#!/bin/bash
sudo su
yum update -y
yum install httpd -y
cd /var/www/html
nano <body bgcolor="145A32"> <h1 style="color:orange;"> This is app application server green </h1> index.html
service httpd start
chkconfig httpd on


#!/bin/bash
sudo su
yum update -y
yum install httpd -y
cd /var/www/html
echo "<body bgcolor="#DFFF00"><h1 style="color:Magenta;"> This is test application server yellow </h1>" > index.html
service httpd start
chkconfig httpd on

++++++++++++++++++++++++++++++++++++

 FILE COMPRESSION & ARCHIVING:

It is useful to store a group of files in one file for easy backup, for transfer to another directory, or for
transfer to another computer.
It is also useful to compress large files; compressed files take up less disk space and download faster via the
Internet.
It is important to understand the distination between an archive file and a compressed file.

COMPRESSED FILES:
It is a collection of files and directories that are stored in one file and stored in a way
thhat user less disk space.

ARCHIVING:
It is a collection of files and directories stored in one file. The achive files in not compressed
it uses less disk space.

NOTE: An archive file is not compressed file can be an archive file.

COMPRESSING FILES:

Red Hat Linux provides the bzip2, gzip, and zip tools for compression from a shell prompt.

The bzip2 and gzip compression tools are recommended because it provides the most compresion and is
found on most UNIX-like operating systems.

To transfer files between Linux and other operating system such as MS Windows, use zip because it is
more compatible with the compression utilities available for Windows.

Compression Tool		File Extension			Decompression Tool

bzip2					.bz2					bunzip2
gzip					.gz						gunzip
zip						.zip					unzip

	> bzip java				
	> bunzip java.z2	
	
	> gzip java				(zip the file)
	> gunzip java.gz		(unzip the file)
	
	> zip java.zip java		
	> unzip jaa.zip

ARCHIVING FILES:

TAR: (TAPE ARCHIVE)
A tar file is collection of sevral files/or directories in one fiel. this is a good way to reate
backups and archives.
SYNTAX: $tar [option] [archive-file] [file or directory to be archived]

	OPTIONS:
		-c 	> Create a new archve
		-v  > Verbose information
		-f 	> creates archive filename
		-t  > show tar file content
		
		-r  > append files to the end of an archive
		-z  > compress the file with gzip
		-j  > compress the tar file with bzip2
		-x  > extract files from an archive

	--wildcards: specifypatterns in Unix tar command.
	
	> tar -cvf maybackup.tar myfile aws java templates		(tar is used to combine multiple file to single file)
	> tar -czvf maybackup.tar.gz myfile aws java templates	(combine multiple file to single file with compression)
	> tar -cjvf maybackup.tar.bz2 myfile aws java templates	(combine multiple file to single file with compression)
	> tar -tvf maybackup.tar								(shows the content in the file)
	> tar -rvf maybackup.tar accessfile 					(add new source to exsting tar file)
	
	> tar -xvf maybackup.tar 								(extract the file)
	> tar -xvf maybackup.tar -C devops 						(extract the file to directory)

MANAIPULATEING TEXT WITH SED & GREP:

SED (STREAM EDITOR) and GREP (GLOBAL REGULAR EXPRESsION PRINT) are powerful
ways to save time and make your work faster.
When we deal with log files, text files, or a piece of code, we need to understand that all of these consist of
characters.
When the length of the file is large, it becomes a necessity to filter out certain patterns in order to make
your debugging easier.

SED (STREAM EDITOR):

SED is mainly used for text substitution, find & replace but it can also pertorm other text manipulations
like insertion, deletion, search etc.
It also supports the use ot regular expressions, which makes SED an even more powertul test manipulation
tool.
SED perform complex pattern matching.

	SYNTAX: $sed Options... [SCRIPT] [INPUTFILE...]
	
	> sed 's/ansible/linux/' filename			(replace the word in the fiel)	this wont update the file just display the content
	> sed 's/ansible/linux/g' filename			(replace the word in the file globally)
	> sed 's/ansible/linux/ig' filename			(replace the every word in the file)
	
	
	
	> sed -i 's/ansible/linux/' filename		(replace the word in the fiel)	this is will update the file
	> sed -i 's/ansible/linux/ig' filename		(replace the word in the fiel)
	
	> sed -n '5,10p' filename					(display the content 5 to 10 lines)
	> sed  '10,20d' filename     				(delete the 10 to 20 lines  in the file)
	> sed 's/#/ /' filename						(remove the #)
	> sed 's/ansible/linux/' filename >> filename			(save the outup with new file)   
	
GREP (GLOBAL REGULAR EXPRESSION PRINT):

Grep is uscd to print lines matching a regular expression.
Use grep to search for lines of text that match one or many regular expressions, and outputs only the
matching lines.
It is one of the most uscful command on Linux and Unix-like systems, which is a powerful file pattern
searcher.

	SYNTAX: $grep [options] pattern [files]
