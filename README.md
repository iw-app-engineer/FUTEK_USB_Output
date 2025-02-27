	1. Download VSCode (popular code editor for writing code)
	Download Visual Studio Code - Mac, Linux, Windows
	
	2. Download Python from Microsoft store
	
	3. Use this USB225_serial.py code as a starting point.  
	
	4. Change "COM5" to your specific COM + #.
		Demo how to find COM#
		Make sure you have a USB225 hooked up to a sensor and plugged into computer
	
	5. Set BAUD rate to 2000000 as per USB225 pro specs.
		a. Works at other values - but I was told by our EE team to leave it at this setting.
		
	6. After this you are ready to run the application. 
		
		a. Open your command line using ( crtl + ` )and navigate using cd (current directory) to your file location
			i. Another tip is also to use ls to "list" out files in a directory
				1) A directory is a folder
		 
		b. Next thing, if you don't have this library - which you won't at the beginning
			i. Run "pip install pyserial" to download the library so it can be used
		
		Now we can run our code and get an ASCII output!!
