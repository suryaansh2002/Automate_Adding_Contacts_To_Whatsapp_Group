# Automate Adding Contacts To Whatsapp Group

This is a basic web scraping script to automate the process of adding groups from a csv or exacel sheel.

First it is necessary that the numbers are stored as contacts in your device, if not the convenient way to do this is to go to https://contacts.google.com/ and import contacts there by uploading a csv. This makes the process really simple.


Ensure that you have selenium, time, and pandas library installed.


To do so run: `pip install selenium time pandas` in cmd.


In the jupyter notebook, set the groupName variable to the name of the group in which participants are to be added, and the PATH variable to the absolute path of your selenium broweser drivers driver.



In the same folder as the Final.ipynb file place an exacel sheet names AddToGroup (You can have a different name but be sure to change it in the code).
The excel sheet should contain a column with header 'Mobile' containing all the numbers you wish to add.

On running the script a new browser window opens up where you will just have to scan the whatsapp qr code to login to your whatsapp account and then the script will add the numbers to the group of your choice.
