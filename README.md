VLSI VS1011 is End-of-Life. The most easy way to replace VS1011 is using VS1003. Here is the sucess story how to replace VS1011. 


Hardware:

   1. Change CVDD voltage, CVDD voltage range 2.4V~2.85V 

   PS: VS1011 DVDD (Digital Power Supply) = VS1003 CVDD (Core Power Supply)  

 

Option, improve audio quality:

   1. Change VS1011 26MHz crystal to 12.288MHz, modify SCI_CLOCKF setting 

   2. Change all capacitors of power supply from 10nF to 100nF

 

Software:

If not set below in VS1011, then ignore the change: 

   1. change VS1011 patch to VS1003 patch

   2. change SM_LAYER12 to SM_SETTOZERO 





Reference: 
1. https://www.vlsi.fi/fileadmin/app_notes/migrate11to03.pdf 
2. https://www.vlsi.fi/fileadmin/news/EOL_VS1011E_2023.pdf 
3. https://www.unitedlink.hk/forum/vlsi-solution/vs1011-migrate-to-vs1003-sucess-story/ 