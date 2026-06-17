# Birthday-email-sender-A python application that automatically sends personalized birthday wishes via email using SMTP.
import smtplib
from email.mime.text import MIMEText
sender="your_email@gmail.com"
password="your_app_password"
receiver=input("Enter receiver email:")
name=input("enter your name:")
msg=MIMEText(f"🎂HAPPY BIRTHDAY ,{name}❤️and have a great day🫶🏻")
msg['subject']="❤️congratulations"
msg['From']=sender
msg['To']=receiver
server=smtplib.SMTP_SSL("smtp.gmail.com", 465)
server.login(sender,password)
server.send_message(msg)
server.quit()
print("email sent successfully!")

