# Python Automatic Birthday Wisher

Python application which automatically wishes people on their birthday. This application will wish someone automatically on schedule.

We need to install a few modules such as pandas and openpyxl.

We will create an excel sheet inside the respective folder. Add the following rows, such as Sno, Name, Birthday, Dialogue, Year, Email. Now for testing purposes we will add a few entries to it.

We will be using Gmail for this application. Now to use this service we need to enable less secure apps on the gmail account which we are going to use for sending the messages.

To schedule the program you need to do the following:
-We need to create a task in task scheduler which will run our main.py file on 12:00 am everyday so that it can check and wish the person on their respective birthday.
-Open the task scheduler.
-Click on create a task.
-In the General tab, add Name and Description(optional).
-Go to Triggers tab. Click on New. Choose Daily in the settings and set time as 00:00:00 (for 12 am).
-Go to Action tab. Click on New. In Program/script field, click Browse and choose python.exe by browsing (for e.g., C:\Users\Programs\Python\python.exe). In Add arguments field, paste the path of the main.py file within double quotes(for e.g. "C:\Desktop\Birthday Wisher App\main.py").
-In Settings tab, check Run task as soon as possibleafter a scheduledstart is missed.
-Now press Ok and exit.

The program is now ready to run.
