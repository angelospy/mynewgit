# mynewgit
mail/sender


import random

def mypassfile():
    lords = open('lords.txd','r')
    lines = lords.readline()
    for line in range (1):
        print(lines)


asa = (str(int(random.uniform(100000, 999999))))

inll = 'errortipe10110001'

gmail = input('plese enter your gmail:')

if gmail == 'angeloreinapirata@gmail.com':

    import smtplib

    from email.message import EmailMessage

    EMAIL_ADDRESS = ('angeloreinapirata5@gmail.com')
    EMAIL_PASSWORD = ('uqijkbmlvpjyrvsy')

    contacts = ['YourAddress@gmail.com', 'test@example.com']

    lol = EmailMessage()
    lol['Subject'] = asa
    lol['From'] = EMAIL_ADDRESS
    lol['To'] = 'angeloreinapirata5@gmail.com'

    with smtplib.SMTP_SSL('smtp.gmail.com', 465) as smtp:
        smtp.login(EMAIL_ADDRESS, EMAIL_PASSWORD)
        smtp.send_message(lol)

else:
    print(inll)

username = input('plese enter the pass word we just send to you ')

if username == asa:

    print('your old pass is: ')
    mypassfile()

    lords = open('lords.txd', 'w').close()

    outputfile = input('plese enter your new pass:')

    if outputfile == mypassfile:
        print('plese try another password')
    else:
        lords = open('lords.txd','a')
        lords.write(outputfile)

    lisa = ('your new pass is:')
    
    mypassfile()

    ask = input('you arr all done:')
else:
    print('sorry bye')
    
    
