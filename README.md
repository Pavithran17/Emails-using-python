# Emails-using-python
## Requirements
1) As the python script will access the Gmail account to send emails, we need to turn to Allow less secure apps to ON in this account. This will make it easier for our python program to access your account. Therefore, it is recommended to create a temporary account for this purpose.

2) Next, to send emails with Python, we need to create a text file named template.txt. This text file contains the format of the body of the email:
   ```
   Dear ${PERSON_NAME}
   You have secured the following marks in your mid-term exams:
   Math - ${MATH}
   English - ${ENG}
   Science - ${SCI}
   ```
 
 3)Then the next file you should have is a CSV file. The file I’ll be using has the details that need to fill in the placeholders in the template file. It contains the details that should be sent to the recipients. It can be an Excel file or a CSV file.
 
 4)Finally, don’t forget to close the SMTP connection after sending all messages. 
