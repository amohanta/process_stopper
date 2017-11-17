Author: Abhijit Mohanta
email: abhijit.mohanta.15.08@gmail.com

Malware analysts sometimes need to view memory of a malicious process.windows Process memory can be viewed with tools like process Explorer, or process Hacker. Sometimes the malicious process terminates even before analyst gets a chance to look into the memory.
Process Stopper is a malware analysis tool that does not allow any of the the process to exit after it is installed. 

Process_Stopper is a kernel driver and one can install it using tools like OsrLoader . The tool has been tested on windows XP. 

Disclaimer: This prgram is  a proof on concept tool and sometimes hangs the system.Please test it only inside virtual machine and in windows XP. 

