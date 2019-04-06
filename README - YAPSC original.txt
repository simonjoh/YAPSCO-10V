YAPSC:10V
Analog-input Servo Amplifiers controller


###############################################################################
  Tips

/firmware contains the controller's firmware (.hex)
/bootloader contains:
	/source
		/btldr.hex : modified bootloader from Ingenia. You should program this
		    on the dsPIC with your fav. dsPIC programmer (ICD2, picKit...)
	/IBLInstaller.zip : contains the windows GUI for the bootloader. Make 
	    YAPSC updates with Ingenia's bootloader.
	/ibl_dspiclist.xml : you will have to update the original file in 
	    C:\Program Files\Ingenia\dsPICbootloader\
/schema_pcb : contains the KiCAD project files (schematics&PCB), PCB as .PS,
    and Gerbers files.
/ProgKey : containt the programming key (RS232 or FTDI USB UART bridge) used
    with the bootloader (upgrade) or with a terminal (configuration)


###############################################################################
  Release notes

15 Aug 2009:
    Version 0.9.3 of the firmware
	The "step input response" test has been improved a bit. This should now 
	work straigthfully.
	The communication speed with YTT has been changed from 9600Bps to 57600Bps
	for improved response speed in YTT.
	This firmware is now fully operationnal with YTT, as all the parameters
	can be changed easily.
	The settings save/restore function suffered from a bug that would erase
	your settings from times to times, with no visible reason; this bug is now
	fixed.
	NOTE : You will need YTT version 1.2 or higher!
	
	The archive now contains "ibl_dspiclist.xml", which is used by the Ingenia
	bootloader software to detect the YAPSC boards.
	After the installation of Ingenia dsPIC Bootloader, replace the original
	file (by default in folder C:\Program Files\Ingenia\dsPICbootloader\) by
	this new one.
	This is also


###############################################################################
  Contact / website

Mail : max-mod@max-mod-shop.com
Web : http://max-mod-shop.com/index.php?option=com_content&view=article&id=47
Project page on CNCZONE : http://www.cnczone.com/forums/showthread.php?p=589305
Project page on USINAGES.COM