<h1>Linux User Levels and Sudo</h1>
Here are some of the most common commands to navigate User Levels in a Linux system</b>:<br/>
	<h2>“whoami”</h2> Command to check which user you currently are</h2>
	<h2>“cd / “</h2> Go to the root (top level) directory</h2>
	<h2>“cd ~ “</h2> Takes you to the Home directory</h2>
  <h2>“su root” - change into the root user</h2>
	<b>NOTE</b> - it is not good practice to work from the root user (use regular account)</b>.<br/>

 <h1>What is "Sudo"?</h1>
 Sudo is a command-line utility that allows users to temporarily run commands with elevated privileges on Unix-like operating systems, such as Linux and macOS</b>.<br/>

 <h1>What does Sudo do?</h1>
Sudo allows users to run commands as the root user, or as another user with elevated privileges. For example, you can use sudo to install a package, disable a network interface, or restart the system</b>.<br/>

<h1>How Sudo works:</h1>
To use sudo, you add the sudo keyword before the command you want to run. The system will then prompt you for your password, and if you're authorized, it will execute the command</b>.<br/>

<h1>Why it's useful:</h1>
Sudo helps users think more carefully about what they're doing before running commands with unlimited power</b>.<br/>

<h1>How it's configured:</h1>
Administrators can use configuration files to restrict and manage privileged access. These files can be located in <b>/etc/sudoers</b> or in the <b>/etc/sudoers.d</b> directory</b>.<br/>
 
