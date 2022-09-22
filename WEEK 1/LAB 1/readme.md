# Identity and Access Management (IAM)

## Task

1. Login on your AWS account
2. Activate Multifactor authentication for root user
3. Create a user who is an admin for the root user





## My LAB Experience 


## 1. Login on your AWS account

Search on aws.amazon.com when it opened i then clicked on sign in to console that is at the top right corner of the web page which took me to where i can input my login details.


## 2. Activate Multifactor authentication for root user.

Multi-factor authentication (MFA) is a security control with which a user is granted access only after successfully providing evidence to an authentication device.

One can sign in to the root user using the email and password used for creating the account meanwhile to ensure a firm security against unauthorized users into your services it is always advicable to enable MFA in the root user as well as the IAM users

Here are the steps to take to enabling the MFA user on the root user 

Click on the right-top corner where your username is written it would drop down several option, then select *"my security credential"*. It would open a new page with several options then click on Multifactor authentication and then click on activate MFA which bring out 3 major option of the kind MFA set-up that AWS offers

          it could be (i) Virtual MFA device
                      (ii) U2F security Key 
                      (iii) Hardware MFA device
                  
Then click on the *"virtual MFA device"* the aws algorithm automatically select it for you ... afterwards, it opens a page that requires you scan a QR code.. To achieve this one will need an app authenticator preferably use google authenticator app... Scan the QR code from the google authenticator app, when it is successful you will get a code on the app that changes with time,

 Then you will input the code in the MFA code 1 and 2, then submit.
 
 
  
 ## 3. Create a user who is an admin for the root user
 
 

