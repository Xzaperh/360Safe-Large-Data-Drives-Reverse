# 360Safe
Reverse engineering of large number-driven code                    
Communication components and Shadow SSDT were not reverse engineered (only SSDT functions of interest were analyzed)        

HookPort：      
Responsible for constructing the Hook framework for export to other drivers, without being responsible for implementing the corresponding Fake functions.

SelfProtection：     
Responsible for implementing the corresponding Fake function


# Usage:          
Load HookPort first, then load SelfProtection.    


# Build Tools:    
VS2013 + WDK8.1


Supported Versions:                  
Original Version: Win2k~Win10 (32-bit)                    
Reverse-engineered Code Version: Win7 SP3 (32-bit)


# Author:         
Blink Blink 丶Blink    

# Disclaimer:                     
This document was obtained through reverse engineering and is intended solely for educational and research purposes. I assume no responsibility for any consequences arising from the use of the code contained herein by others.           
  
# References:
1. Release a compilable, replaceable hookport code                  
 Website：https://bbs.pediy.com/thread-157472.htm                       
 2. Tencent Manager Offensive-Defensive Mechanism Analysis - TsFltMgr               
  Website：https://www.jianshu.com/p/718dd8a1dd27               
 3. To summarize, it enables a relatively precise determination of SCM loading.                
  Website：https://bbs.pediy.com/thread-135988.htm      
