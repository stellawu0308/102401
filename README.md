# 102401
import re
email= r'^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$'
entered_email=input('Plz enter ur Email address.')
if re.match(email, entered_email):
    print('Valid Email address!')
else:
    print('invalid Email address! Plz enter again!')
