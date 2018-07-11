# ZendeskAPIscript
Python script to perform Zendesk API calls to extract all ticket information

You can reuse that script to extract all tickets relative to a user (based on email address). This can be useful to answer GDPR access requests until Zendesk provides an easy way to do it.


1) replace the variables in the python script

adminemail 
adminAPItoken 
Zendesk domain 

2) Run the script in a terminal (requires Python 3 and pandas installed)

python3 scriptZendeskGDPR.py

3) Enter the email address of the user you want to extract tickets from

4) The script will create a file answer.txt in the same directory with all tickets and comments (without name of the person who added a comment to preserve the agents names)
