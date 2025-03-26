Success Story: Seamlessly Replacing VS1011 with VS1003

VLSI's VS1011 has been declared End-of-Life (EOL), and the easiest replacement option is the VS1003. Here’s a quick success story of the transition:


Hardware Changes:

    CVDD Voltage:
    
        Change CVDD voltage to 2.4V–2.85V.
        
        Note: VS1011's DVDD (Digital Power Supply) = VS1003's CVDD (Core Power Supply).
        
    Optional Audio Quality Improvements:
        Replace VS1011's 26MHz crystal with a 12.288MHz crystal and adjust the SCI_CLOCKF setting.
        Upgrade all power supply capacitors from 10nF to 100nF.

Software Changes (if not already set in VS1011):
    Replace the VS1011 patch with the VS1003 patch.
    Change SM_LAYER12 to SM_SETTOZERO.

This summarizes the necessary changes for a smooth transition from VS1011 to VS1003, ensuring compatibility and potential audio quality improvement.

Reference: 
1. https://www.vlsi.fi/fileadmin/app_notes/migrate11to03.pdf 
2. https://www.vlsi.fi/fileadmin/news/EOL_VS1011E_2023.pdf 
3. https://www.unitedlink.hk/forum/vlsi-solution/vs1011-migrate-to-vs1003-sucess-story/
4. https://www.vlsi.fi/fileadmin/datasheets/vs1003.pdf
5. https://www.vlsi.fi/fileadmin/datasheets/vs1011.pdf 
