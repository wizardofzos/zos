# z/OS
####Random mainframe stuff

racf.rule - hashcat rule for cracking RACF passwords, probably needs more tweaking!

MVS Control Blocks.txt - File for use in ISRDDN to make browsing storage easier. Based on [this](http://www.meerkatcomputerservices.com/mfblog/wp-content/uploads/2016/07/Browsing-MVS-Control-Blocks-Using-DDLIST.pdf)

##Other useful notes
To find DES encrypted RVARY passwords:  

```
TSO ISRDDN  
BROWSE 10.?+3e0?+1B0+8  
```
