---------------------------------
   Activation
---------------------------------

 - This script applies the registry lock method to activate the Internet Download Manager (IDM).

 - This method requires Internet at the time of activation.

 - IDM updates can be installed directly without having to activate again.

 - After the activation, if in some cases, the IDM starts to show an activation nag screen, 
   then just run the activation option again.


---------------------------------
   Reset IDM Activation / Trial
---------------------------------

 - The Internet Download Manager provides 30 days trial period, you can use this script to 
   reset this Activation / Trial period whenever you want.
 
 - This option also can be used to restore status if in case the IDM reports a fake serial
   key and other similar errors.


---------------------------------
   OS Requirement
---------------------------------

 - Project is supported only for Windows 7/8/8.1/10/11 and their Server equivalent.


---------------------------------
   Advanced Info
---------------------------------

   - For activation in unattended mode, run the script with /act parameter.
   - For reset in unattended mode, run the script with /res parameter.
   - To enable silent mode with the above two methods, run the script with /s parameter.

Possible accepted values,

"IDMA-xxxxxxxx.cmd" /act
"IDMA-xxxxxxxx.cmd" /res
"IDMA-xxxxxxxx.cmd" /act /s
"IDMA-xxxxxxxx.cmd" /res /s


---------------------------------
   Troubleshooting
---------------------------------

   - If any other activator was used to activate IDM previously then make sure to properly
     uninstall it with that same activator (if there is an option), this is especially important
     if any registry/firewall block method was used.

   - Uninstall the IDM from the control panel.

   - Make sure the latest original IDM setup is used for the installation,
     you can download it from https://www.internetdownloadmanager.com/download.html

   - Now install the IDM and use the activate option in this script if failed then,

     - Disable the windows firewall with the script option, this helps in case of leftover entries of
       previously used activator (some file patch method also creates firewall entries).

     - Some security programs may block this script, this is false-positive, as long as you 
       downloaded the file from the original post (mentioned below on this page), temporary suspend
       Antivirus real-time protection, or exclude the downloaded file/extracted folder from scanning.

     - If you are still facing any issues, please contact me (mentioned below on this page).


---------------------------------
   Credits
---------------------------------

   @Dukun Cabul         - Original researcher of this IDM trial reset and activation logic,
                          made an Autoit tool for these methods, IDM-AIO_2020_Final
                          nsaneforums.com/topic/371047--/?do=findComment&comment=1632062
                         
   @WindowsAddict       - Ported the above Autoit tool to a batch script

   @AveYo aka @BAU      - Snippet to set registry ownership and permission recursively
                          pastebin.com/XTPt0JSC

   @abbodi1406          - Awesome batch script tricks and help

   @dbenham             - Set buffer height independently of window height
                          stackoverflow.com/a/13351373

   @ModByPiash          - Added and fixed some missing features.
   
   @dhuchgess (Me)      - Improved IDM UI.


---------------------------------
   IDM Activator
---------------------------------
   
   🌍 GitHub:- https://github.com/dhuchgess/IDM-Activator
   
   👤 Contact:- https://t.me/dhuchges

---------------------------------
