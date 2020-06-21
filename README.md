# Windows-Server-VirtualBox
How to setup Windows Server 2019 on VirtualBox
<h1>Windows Server</h1>
<ol>
  <li>Download the Windows Server ISO file from the <a href="https://www.microsoft.com/en-US/evalcenter/evaluate-windows-server-2019?filetype=ISO">official Microsoft website</a>.</li>
  <li>Fillout the details needed to download the file(s).</li>
  <li>Download VirtualBox through the website. Setup is the same as per-usual.</li>
  <li>Be sure to change the Network configurations of the VM to use "Bridged Adapter". Assuming this will be used for Development purposes, you will want to be able to access the server on your (and others') computer.</li>
  <li>Create a VM and set an ideal amount of dedicated resources to hosting the VM. This is obviously scaled towards your computer/laptop specs.</li>
  <li>Startup the dedicated VM and select the downloaded Windows Server ISO. Go through the installation process like you would with Windows for desktop.</li>
  <li><b>[If you are a beginner]</b> When prompted, be sure to select the "Desktop Experience" option. This installs the GUI version of Windows Server which can be significantly better unless you know the needed commands to get Windows Server running.</li>
  <li><b>[If you are an expert]</b> Select the non-desktop experience profile. This removes all GUI aspects of Windows Server which minimises the amount of system resources to host the VM.</li>
  <li>Continue the installation as prompted.</li>
</ol>
<br />
<h1>MySQL Host</h1>
<ol>
  <li><a href="https://dev.mysql.com/downloads/installer/">Click here</a> to download the MySQL suite installer. Because we are mainly interested in the database server hosting aspect, we can select the "Server" option. Though it doesn't hurt to have the additional features.</li>
  <li>Go through the installation process as per-normal. Because we are installing this on a server, it is ideal to install the addtional Logging features for troubleshooting potential errors.</li>
  ### Add more stuff
</ol>
