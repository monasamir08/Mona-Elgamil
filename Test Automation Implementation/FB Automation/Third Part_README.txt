1. Download and install Python (lastest version preferable)
2. Let your PC Know that you have Python installed by dowing the following: 
	a. Go to Control Panel -> System and security -> System
	b. Click on Advanced system settings then Environment Variables.
	c. In system variables, search for PATH variable and at the end of it add the following: (;%PYTHONPATH%) then click OK.
	d. Click on New, Variable Name: PYTHONPATH	Variable Value: The Path where you have your python installed in your PC;then the path 	where you have the DLLs; the path where you have Lib; the path where you have Scripts.
	e. Click Ok until you close all the open windows. 
3. Packages installation:
	a. Open cmd window and write pip3 install selenium
	b. pip3 install ddt
	c. pip3 install Pygments
	d. pip3 install backcall
	e. pip3 install decorator
	f. pip3 install ipython
	g. pip3 install ipython-genutils
	h. pip3 install jedi
	i. pip3 install parso
	j. pip3 install pickleshare
	k. pip3 install prompt-toolkit
	l. pip3 install six
	m. pip3 install traitlets
	n. pip3 install wcwidth
4. Download and install PyCharm code editor (or any other preferable code editor)
5. Download and unzip the project folder from github.
6. Open PyCharm and choose the project folder to launch.
7. Under Trial Folder, Run DD_Login for the login automation.
8. Under Trial Folder, Run Registration_Form for the the registration automation.

IMPORTANT NOTE: Registration is only done for filling the form part with no clicking on sign-up button.
