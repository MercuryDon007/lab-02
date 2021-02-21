# lab-02
Google mail

Short description: Google mail is a google mail service provided by Google.

Task 1: Create A account

Non-technical: You need to have an account where Google stores information about yourself in order to provide mail services. You need to give your Name, date of birth, mobile number, and other details.

Technical: Google has a personal database where each piece of information is going to store. In most of the cases, they are using the three-level database to back up. If you are first time creating an account that case you need to verify your mobile number for synchronization purposes. For the verification, Google sends your mobile number one time password that needs to be submitted while creating an account the first time. For storing the password for your account they are using a one-way hashing mechanism that is nearly impossible to crack.

What can go wrong: You need to be select a mail address that is unique and selects a strong password that is not easily guessable.  

Task 2: Log in to your account:

Non-technical: In-order to use mail services you need to login into a dashboard where you can be sent and check your mail. For that need to pass your mail address and password correctly.

Technical: When you provide your mail address and password, a post request sent to google's back-end including your email address and password in an encrypted format. In-order to encryption and decryption they are using the public key and private key approach that is most secure till now. If you provide the correct email address and password, you will be redirected to the default dashboard otherwise the response will be sent that you are provided the wrong email address or password.

What can go wrong: If you provide the wrong mail address or wrong password then you will not able to login to the system.

Task 3: Sent an email to other clients.

Non-technical: In-order to sent a mail or your message to another client, you need to provide the client mail address properly, you also need to give the subject of the mail and body then your message will be sent to provided clients.

Technical: In order to send mail you need to login into your Google mail SMTP account. SMTP is a protocol using which google sends your mail to another address. SMTP is basically a simple mail transfer protocol. You send a mail, that mail basically sends to SMTP server where it stored to a particular address. Then the client can push that mail and check the mail accordingly.

What can go wrong: You need to provide the correct client mail address otherwise this mail will be sent to some other client which can be a security problem.
