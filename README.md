#Virtual reality tool for superviosry patent examiners.
###Saurabh Parikh | Prithiv Natarajan

This file contains the description of each file essential to the project.
The project has been divided into three parts Scraping, Data Analysis,
and Virtual Reality. Each part can be worked on independently, however
care must be taken during the transfer of data. Hence, the input format
for each step has been described below.

### SCRAPING

The files were downloaded from PatFT:
	
	http://patft.uspto.gov/netahtml/PTO/index.html

** DownloadData.py **
	This script scrapes the data from the PatFT website for USPC 706
	class. The data is stored locally for further analysis.
	The process can be stopped anytime by pressing CTRL + C

** ScrapeData.py **
	It takes a BeautifulSoup (Python Library) object of an .html page
	downloaded using DownloadData.py and returns the required information.

** SummarizeData.py **
	Uses the ScrapeData.py script to format the data from all the 
	downloaded patents into a .csv file which will be used in the Analysis.

### ANALYSIS

### VIRTUAL REALITY

Everything required for the project is contained in the ./Assets folder

** ./Data **
	* * FILL *

** ./Editor **
	###FILL###

** ./ Materials **
	###FILL###

** ./nuget_packages **
	* Do not edit. Handled by the plugins.

** ./Plugins **
	Do not edit. Plugins to use VR.
	* SteamVR: Interface between the headset and the computer
	* TextMeshPro: Handles text shown in 3D.
	* VRTK: Virtual reality toolkit contains the basic components required
		  VR such as, the model of the controller, handling input etc.

** ./Prefabs **
	* ControllerScripts: Handles input.
	* Dragger: Handles the dragging of the patent to show more information
	* Environment: The lights and the floor.
	* Filter: Contains the text and selector for the chosen filter.
	* ObjectTooltip: ###FILL###
	* PatentManager: Prefab for the patent manager script
	* PatentPopUp: The panel containing the patent information
	* SettingsPanel: The controller of the VR space. Contains three panels
		color coding, filter, and patent info

** ./Resources **
	###EDIT###

** ./Scenes **
	* Contains only the main scene.

** ./Scripts **
	* Description is present in the script itself.

** ./Shaders **
	* 3DTextCullBack: Used to show text visible only from one direction.

** ./Textures **
	The images used in the project. Their description is apparent from
	their name.


