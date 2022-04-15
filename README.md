# Google-Calender-Integration-with-Django

Before we start, we have to setup  a service account and add it to our calendar that we want the service account to access. Google has written down the three steps to create an account [here](https://github.com/googleapis/google-api-python-client#creatinganaccount). Afterwards, go to https://calendar.google.com, locate on the left side of the screen the calendar you want to share with your new service account and click the triangle next to it. From the drop-down menu choose calendar settings. This takes you to a screen where you'll find the calendar-ID which you'll need later (so write it down) and also displays a tab at the top to share access to the calendar. As "person" insert the email address from the service account, give it the respective permissions and  click save  (if you don't click save the service account won't be added).


I'm using oauth2client version 2.2.0 (`pip install oauth2client`).
