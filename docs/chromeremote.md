# Using Chrome Remote Desktop

Google's [Chrome Remote Desktop](https://remotedesktop.google.com/home) is a simple,
powerful, and completely free way to access full screens on remote servers.
You may choose to use Chrome Remote Desktop for the Nautilus server,
if you prefer access with a full screen instead of a command line accessible
from an SSH window.

<img src="remotedesktop.png"  width="400">

* You will first need to [get an account and SSH](./login.md) into the nautilus server.
* On your local machine, go to the [Chrome Remote Desktop access page](https://remotedesktop.google.com/access/).
On the left, select "Set up via SSH".
* Select "Setup another computer"
* The first instruction will be "Download and install Chrome Remote Desktop on the remote computer".
You can skip this step since it has already been set up, so just select "Next"
* On the next screen, select "Authorize".
* You will be given a command for various types of remote machines.  Copy the
command for "Debian Linux".  Paste this command into the SSH terminal on the
remote machine.
    * Note this command is only valid for a few minutes.  If you do not copy
    the command in time, you will need to repeat this step to get a new
    command.
    * After pasting in the command, you will be prompted for a PIN.
    * It may say it is stopping the existing host and take a few minutes.
* Return to the [Chrome Remote Desktop access page](https://remotedesktop.google.com/access/)
and select "Remote access" on the left.  The remote machine with a name
such as `oai-gNB-02.calit2.optiputer.net` should be available.  Select
that machine.  You will be asked to enter the PIN you entered in the previous step.
* You will now see a screen similar to the image above.
* You may wish to adjust the screen resolution.  To change the resolution,
right click in the main window and select "Applications->Settings->Display".






