# INT-301_CA-3
Q) Investigate the system run time state of a device (RAM), extract the information present in RAM with the help of volatility Framework.

I have uploaded the files "PowerShellCommands.txt" and "PowerShellTranscript.txt" of Commands and outputs of using volatility Framework to extract the information present in memory dump.

Below steps are the process of doing this task:

1) Install Python by this link: https://www.python.org/downloads/

2) Install Volatility Framework: You can download Volatility Framework from the official website or GitHub repository. Once you have downloaded it, extract the files and install the framework on your system by this link: https://www.volatilityfoundation.org/ 

3) Acquire Memory Dump: You need to acquire a memory dump of the device whose RAM you want to investigate. You can use tools like FTK Imager to acquire the memory dump by this link: https://www.exterro.com/ftk-imager 

4) The Memory Dump will be of 10GB size or more, save it in a file.

5) Analyze Memory Dump: Once you have acquired the memory dump, open a command prompt and navigate to the directory where you have installed the Volatility Framework. Use the "volatility" command followed by the desired plugin to analyze the memory dump. For example, you can use the "volatility imageinfo" plugin to display information about the memory dump, such as the operating system, profile, and service pack.

6) Extract Information: You can use various plugins provided by Volatility Framework to extract information present in RAM. For example, you can use the "volatility pslist" plugin to display information about running processes, "volatility info" for displaying information of the windows.
