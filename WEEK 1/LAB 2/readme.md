# Identity and Access Management (IAM)

## Task

In an organization demo.io, they have 5 people in different unit as listed:

i.   Dele     technical expert 

ii.  Ade      technical support

iii. Segun    Storage expert

iv.  Gbenga   Admin support

v. Sharon  Finance head


Your task in this lab is to create 

1. Groups and add the corresponding user
2. Enforce a password policy
3. Perform clean up operations

Guides:
https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html





## My LAB Experience 



## 1. Groups and add the corresponding user

Groups are collection of IAM users which save the stress of having to assign specific set of permission to each individual user when you can assign a set of permissions to the group that will be added to a user who is added to that group.
Beleow are the steps to follow to set up usergroups;

Click on the IAM services on the dashboard which will open the IAM service page

You then click on "groups" when the page loads up you will see at the top-right corner "create group" then click on it 

Set group name and set the permission by assigning a policy to the group....

Too add individual users to the groups, click on the group action, a drop-down interface would show diffent options - then you click on 'add user'


## 2. Enforce a password policy 

The password policies defines the password strength rules that are used to determine whether a new password is valid.

i followed this step to enforce policy password, i clicked on the IAM dashboard then click on Apply IAM password policy then click on manage policy and then click on set password ...

Meanwhile there are certain conditions required to enforce password policy, which are;

When you configure a custom password policy for your account, you can specify the following conditions:

*password minimum length*

You can specify a minimum of 6 characters and a maximum of 128 characters.

*password strength*

You can select any of the following check boxes to define the strength of your IAM user passwords:

Require at least one uppercase letter from Latin alphabet (A–Z)

Require at least one lowercase letter from Latin alphabet (a–z)

Require at least one number

Require at least one nonalphanumeric character ! @ # $ % ^ & * ( ) _ + - = [ ] { } | '

*enable password expiration*

You can select and specify a minimum of 1 and a maximum of 1,095 days that IAM user passwords are valid after they are set. For example, if you specify an expiration of 90 days, it immediately impacts all of your users. For users with passwords older than 90 days, when they log into the console after the change, they must set a new password. Users with passwords 75-89 days old receive an AWS Management Console warning about their password expiration. IAM users can change their password at any time if they have permission. When they set a new password, the expiration period for that password starts over. An IAM user can have only one valid password at a time.


## Perform clean up operations





## Some Screenshots


![ugrp1](https://user-images.githubusercontent.com/105374941/192306914-a90ad0b4-c457-4247-a26a-cca221bff4bf.png)


![ugrp2](https://user-images.githubusercontent.com/105374941/192306994-5f81a90c-d0be-43b8-8bb8-6b46e69aba30.png)


![ugrp3](https://user-images.githubusercontent.com/105374941/192307157-86c60f31-1c3a-46de-8ca9-f087dfb14e88.png)


![ugrp4](https://user-images.githubusercontent.com/105374941/192307240-4866ba60-6c57-4ee7-be9b-4c54341b97bb.png)


![ugrp5](https://user-images.githubusercontent.com/105374941/192307331-729cd29a-c0f1-448d-9478-14ef43caa7ff.png)

