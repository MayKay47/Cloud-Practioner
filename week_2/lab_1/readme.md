# Working with AWS Billing

## Tasks

1. Attach the required IAM policy to an IAM identity
2. Review your bills and usage
3. Email your Invoice
4. Download or print your bill


Guide: 
https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-what-is.html
https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/billing-getting-started.html







## My LAB Experience

## 1. Attach the required IAM policy to an IAM identity

AWS account owners can delegate access to specific IAM users who need to view or manage the billing data for an AWS account. I activated the billing console and AWS cost management console by following these steps;

Firstly, I logged in to the root user --- then clicked on the top-right corner and then clicked on "Account" 
afterwards, i scrolled down to get the IAM user billing information and then click on "edit" and then selected the checkbox to activate IAM Access then i clicked on "update"

Then i created a user with the name "FinanceManager" .. In the navigation pane, i choose policies and the i clicked on "create policy"..... 

After the page opened up on the visual editor tab, i clicked on "choose a service" to get started. Then i choose "Billing console"

I followed these steps to create two policies:

Full access

Select the check box next to All Billing Console actions (aws-portal:*)

Then choose Next: (i.e. Tags)

Then choose Next: (i.e. review)

On the Review policy page, next to Name, type BillingFullAccess, and then choose Create policy to save it.

For View Acccess 

I choose "Select actions" and the select the check box next to "Read".
Then choose Next: Tags , Then choose Next: Review

On the "review policy" page, i named it "BillingViewAccess"---- then choose "Create Policy" to save it 

Now that i have the custon billing policies available i attached them to the corresponding User that i have created earlier.


## 2. Review your bills and usage


![rvwB1](https://user-images.githubusercontent.com/105374941/193826938-2047265e-654c-4f45-a13f-de4f79e6058a.png)



![rvwB2](https://user-images.githubusercontent.com/105374941/193826968-7af85b3b-7095-4f45-af5e-af3d7c57ccc4.png)



![rvwB3](https://user-images.githubusercontent.com/105374941/193827387-e04eab47-49d3-449e-a9a2-a17a6295cb84.png)


![rvwB4](https://user-images.githubusercontent.com/105374941/193827436-66515754-ee0d-404a-8ebf-8c939473ab57.png)


## 3.  Email your Invoice.

![invoice](https://user-images.githubusercontent.com/105374941/193827813-61c082a0-39da-4ba9-beec-72649cd2d189.png)


## 4. . Download or print your bill


![invoice](https://user-images.githubusercontent.com/105374941/193827935-3f74fc7c-50fe-4ad7-91a2-7bbb6f9d5ec1.png)


![Invce2](https://user-images.githubusercontent.com/105374941/193827998-a7811e6a-b10a-42fb-98df-a2f6040f78c6.png)

