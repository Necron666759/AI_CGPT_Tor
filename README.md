# AI_CGPT_Tor
A set of programs for quick access, in one click, to gpt chat, via the Tor network.

Minimum system requirements:
Windows 10x86
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Instructions~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The program is launched completely automatically from the shortcut on the desktop, "ChatGPT" or from the folder along the path "C:\ChatGPT\Obfs4AI.exe".
If you have problems with the connection, replace the bridges in the "torrc" configuration file. New bridges can be requested via the Telegram messenger or the Tor browser.
To update the executable files responsible for connecting to the Tor network - tor.exe, lyrebird.exe download tor-browser-windows-i686-portable-**.*.*.exe
from the official Tor Project website. Extract the installation package and copy the necessary files to the ChatGPT program folder.
To update the browser, download a portable version of Firefox or update the current one via the built-in automatic update mechanism.
In the first case, you need to replace the entire contents of the C:\ChatGPT\core\FP folder via the installation package, in the second case, simply restart the browser.
Note that the CGPT.exe executable file has a hierarchically structural dependency - do not move or rename it, folders: FP; core; ChatGPT. 
The corresponding objects must remain unchanged and in their location, otherwise Obfs4AI.exe will not be able to launch the browser for you in automatic mode with
the opening of the corresponding chat page. Any other manipulations with objects inside the root directory of the program are also unacceptable and can lead to
incorrect operation of the program, except for cases when it is necessary to register new bridges in the "torrc" configuration file.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Instructions~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

####################################################################################NOTE#######################################################################################

Once the procedure for connecting to the Tor network has been started, processes such as tor.exe and lyrebird.exe will not be terminated until you click the
"Disconnect from Tor" button or stop them through the Windows Task Manager. Simply closing the application will not stop these processes.

####################################################################################NOTE#######################################################################################

Donate to the project:
USDT(TRC20): TWmpTMTDtwShQ3D7ZVb2ofRpgodiMfyF9o

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Developed by Celsius - 2025 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Version 1.0 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Subversion 2.0.19 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Scripting language AHK2.0 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
