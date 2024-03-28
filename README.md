# python_mailproject

1)The first step in any python project will be intalling and importing the relevant libraries.In this project first install:
     1.pandas
     2.smtplib
     3.email-to

2)And we imported the needed libraries:
     1.pandas
     2.smtlib
     3.MIMEMultipart
     4.MIMEtext

3) we created a csv file with a column name EmailID and added some emailids in the file then we imported the "kpkp.csv" file into google colab/pyhton IDE.
4) In the next step we have found the length of emails and stored it in the variable 'l'
5) Then run a for loop which contains the body,subject,from and to details of the email to be sent.
6) Run the script and look for errors if any.
7) Quit the connection and check for the email which has to be sent.

# Challenges faced
1) VS failed to read csv file : We added utf-8 with our file name , and just at bottom right of vsCode we have UTF8 option click on that , the pop up comes and save the file.
2) Password : We mentioned our original password , which might be harmful for your account privacy/security as code can be accessed by anyone . So to avoid data breaching we used google's app password , which basically gave us the encyrpted version of password to write in our python script.
