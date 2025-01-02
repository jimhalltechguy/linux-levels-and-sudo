<h1>Linux User Levels and Sudo</h1>
Here are some of the most common commands to navigate User Levels in a Linux system</b>:<br/>
	</h2>“whoami”</h2> - command to check which user you currently are</h2>
	</h2>“cd / “</h2> - go to the root (top level) directory</h2>
	</h2>“cd ~ “</h2> - takes you to the Home directory</h2>
  <h2>“su root” - change into the root user</h2>
	<b>NOTE</b> - it is not good practice to work from the root user (use regular account)</b>:<br/>

 <h1>What is "Sudo"?</h1>
 Sudo is a command-line utility that allows users to temporarily run commands with elevated privileges on Unix-like operating systems, such as Linux and macOS</b>.<br/>

 <h1>What does Sudo do?</h1>
Sudo allows users to run commands as the root user, or as another user with elevated privileges. For example, you can use sudo to install a package, disable a network interface, or restart the system</b>.<br/>

<h1>How Sudo works:</h1>
To use sudo, you add the sudo keyword before the command you want to run. The system will then prompt you for your password, and if you're authorized, it will execute the command</b>.<br/>

<h1>Why it's useful:</h1>
Sudo helps users think more carefully about what they're doing before running commands with unlimited power</b>.<br/>

<h1>How it's configured</h1>
Administrators can use configuration files to restrict and manage privileged access. These files can be located in /etc/sudoers or in the /etc/sudoers.d directory</b>.<br/>
 






<h1>Local and Domain Accounts</h1>
This repo outlines key elements of <b>Windows Local and Domain Accounts</b>.<br/>
	<h2>Local Account</h2> 
 		One user on one PC, with one username and one password</h2>
	<h2>Domain Account</h2> 
 		Allows many users to log onto a PC by using a Domain Controller (server) to store all of the many different Users and their Usernames and Passwords</h2>
	<h2>Domain Controller Directory</h2> 
 		Acts like a phone book to record all of the different Users and their Permissions, along with their Usernames and Passwords</h2>
	<h2>Administering Local User Accounts</h2>	
 		This link is a very helpful resource for implementing and maintaining Local User Accounts</h2>
   		<p>https://learn.microsoft.com/en-us/windows/security/identity-protection/access-control/local-accounts</p>
	<h2>Administering Local User Accounts</h2>
		<p>Click on <b>Start</b> (blue box at bottom left of task bar on Windows 11)</p>
		<p>Type “<b>control panel</b>” in <b>Search Box</b></p>
		<p>Click on <b>Control Panel</b> -> <b>User Accounts</b></p>
		<p>Then make user account changes you want</p>
    	<b><p>OR</b></p>
		<p>Click on <b>Start</b> (blue box at bottom left of task bar on Windows 11)</p>
		<p>Type “<b>run</b>” in <b>Search Box</b> and click on <b>Run</b></p>
		<p>Click “<b>Ok</b>” when “lusrmgr.msc” pop-up box appears and make account setting changes</p>
