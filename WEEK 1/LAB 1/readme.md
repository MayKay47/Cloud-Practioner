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
  
  
  Sign in to the IAM console after you have log in as a root user by clicking on the service icon and search for IAM.... when its opens up in the navigation pane, click *Users* and then choose *Add users*
  Then set users details by creating a username and then select the AWS access user type --- which has two option;
  
             (i) Programmable Access
             It enables access Key Id and Secret Key for the AWS, API,CLI,SDK and development tools
             (ii) Access management console access
             It enables a password that allows users to sign-in to the AWS management console .. 
             
 *Note* Since i was going to use the management console , i selected the second option that affords me to generate a password i can use to login to the console 
 
 Afterwards, click on next which opens up the page to set permission, meanwhile we have 3 options of which includes.
          
               (i) Add users to group
               
               You can add the user to group you have created so they can have access to all the policies of that group 
               (ii) Copy permission from existing user 
               
               Here you can copy the permission from an existing user account to the user account you are creating and every of the policies factor into that user account would work equally for the new user account being created 
               (iii) Attach existing policy directly 
               
               There are already defined policies on the AWS console that one cann use or we could create a custom-made policy 
               
 furthermore, click on next which opens up the page to add Tags to the users , Tags are information that describes and labels the user you are creating 
 
 Then click on next, to review the user account before clicking on *create user*
 
 
 
 ## Here are some screenshot
 
 ## To Activate MFA on a root user account 
 
 ![rtMFA1](https://user-images.githubusercontent.com/105374941/191771020-c1509eff-c932-4746-ac51-00a505a42ee6.png)
 
 
![rtMFA2](https://user-images.githubusercontent.com/105374941/191771086-c9da47a2-17db-4b32-a38b-c05e5c7f5b46.png)



![rtMFA4](https://user-images.githubusercontent.com/105374941/191771248-0a591551-6e24-435a-aa2d-759baae56dbd.png)

   
![rtMFA5](https://user-images.githubusercontent.com/105374941/191771272-8f09704b-1103-42f8-8cc7-57eb48ac3772.png)



![wk1lb1b](https://user-images.githubusercontent.com/105374941/191771337-6100a20e-6a8d-488e-ac85-d80f1d2eda7c.png)



## To create a user who is an admin for the root user
        
 

