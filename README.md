# Screenshots
<img width="1901" height="879" alt="изображение" src="https://github.com/user-attachments/assets/70d7e7fc-5480-41c4-94ff-547d0dde824c" />
<img width="1900" height="881" alt="изображение" src="https://github.com/user-attachments/assets/23e05e8b-6377-496b-af0b-527f2cc3cc55" />
# AI_CGPT_Tor
A set of programs for quick access, in one click, to gpt chat, via the Tor network.

Minimum system requirements:
Windows 10x86

===========================================================================================================================================================================
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Instructions~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
===========================================================================================================================================================================

The program runs completely automatically from the desktop shortcut "ChatGPT" or from the folder at the path "C:\ChatGPT\Obfs4AI.exe".

If you have problems with the connection, replace the bridges in the torrc configuration files. New obfs4 bridges can be requested via the Telegram messenger or the
Tor browser. To replace the snowflake and meek bridges, use the Tor Expert Bundle, which can be downloaded from the official Tor project website
(https://www.torproject.org/download/tor/). Unzip the downloaded archive and find the pt_config.json file at the path
\...\tor-expert-bundle-windows-****-****\tor\pluggable_transports. Check the pt_config.json file for new bridges.

To update the executable files responsible for connecting to the Tor network - tor.exe, lyrebird.exe - download the new version of the Tor browser or Tor Expert Bundle
from the official website. Here is where you can find the updated transport module and meta transport plugin:
1) Path for Tor Browser: \...\Tor Browser\Browser\TorBrowser\Tor
2) Path for Tor Expert Bundle: \...\tor-expert-bundle-windows-****-****\tor\
Copy the files you need to the folder with the ChatGPT program.

To update the browser, download the portable version of Firefox or update the current one via the built-in automatic update mechanism.

In the first case, you need to replace the entire contents of the C:\ChatGPT\core\FP folder via the installation package, in the second case, just restart the browser.
Please note that the CGPT.exe executable file has a hierarchical dependency structure - do not move or rename it in the folders: FP; core; ChatGPT.
The corresponding objects must remain unchanged and in their places, otherwise Obfs4AI.exe will not be able to launch the browser in automatic mode with opening the
corresponding chat page. Any other manipulations with objects inside the root directory of the program are also unacceptable and may lead to incorrect operation of the
program, except for cases when it is necessary to register new bridges in the torrc configuration files.

===========================================================================================================================================================================
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~Instructions~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
===========================================================================================================================================================================

####################################################################################NOTE###################################################################################

After starting the procedure for connecting to the Tor network, processes such as tor.exe and lyrebird.exe will not be completed until you click the "Disconnect from Tor" 
button or stop them through the Windows Task Manager. Simply closing the application will not stop these processes and they will continue to function in the background.
Please note that when you restart the application, an error may occur: "Error: (32) The process cannot access the file because the file is in use by another process."
 - just click continue to continue working with the application. In case you need to finish the work, click "Disconnect from Tor", but for such a scenario, you must first
click the continue button in the error window.

####################################################################################NOTE###################################################################################

Donate to the project:
USDT(TRC20): TWmpTMTDtwShQ3D7ZVb2ofRpgodiMfyF9o

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Developed by Celsius - 2025 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Version 1.0 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Subversion 2.0.19 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Scripting language AHK2.0 %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
