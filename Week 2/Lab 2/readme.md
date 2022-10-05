# AWS Free Tier usage alerts using AWS Budgets

## Task:

1. Create a cost budget
2. Create a usage budget

NB: Include Budget alarm at your preferred threshold.


Guide:
https://docs.aws.amazon.com/cost-management/latest/userguide/budgets-create.html







## My LAB Experience 

## Short Notes on AWS budgets
It is a service that helps you plan service usuage, service costs, and instance reservation. It also give you the ability to set up alerts if you exceed or are approaching your defined budget. This budget can be tracked Monthly , quaterly or yearly.
 
 You can create and set up a budget in two ways:
   - Using a budget template (simplified)
   - Customizing a budget (advanced)

## 1. Create a cost budget

Here are the steps i took to creating a cost budget as written in the AWS documentation for cost budget 

I clicked on budget then at the top of the page i choose "create budget" under Budget setup, i chose  customize (advanced) afterwards, under Budget types, i chose "cost budget".. then , i clicked on "Next"

Theb under Details, i enter the name of my budget and then set my budget amount for the customized period which could be daily, weekly, monthly and annually.

For the Budget renewal type, i chose recurring budget.. which enables my budget to reset after my budget period.

For my Budgeting method i selected a fixed way that i want my budget amount to be determined at each budget period
Then i clicked on "Next"
After the page open up, i clicked on add an alert threshold, Under "Set alert threshold" ... And i set my alert threshold to 80% of my budget.

Then i clicked on "Next" to review my budget setting then i clicked on "Choose Budget"





## 2. Create a usage budget.



## Screenshots.


![awsbgt01](https://user-images.githubusercontent.com/105374941/194050696-c6f74433-4400-4cc3-ba36-8ba939cb0e6a.png)


![awsbgt2](https://user-images.githubusercontent.com/105374941/194050713-8e5a83a0-27fc-4fa3-9297-a75af429771b.png)


![awsbgt2](https://user-images.githubusercontent.com/105374941/194050722-30380391-cc8b-49e9-8193-7e694c9c1578.png)


![awsbgt3](https://user-images.githubusercontent.com/105374941/194050727-6af48718-0f1f-4435-b731-2eab43d71dfa.png)


![awsbgt4](https://user-images.githubusercontent.com/105374941/194050827-f0c81052-bfe3-4da0-8dc9-70e975f7a56c.png)


![awsbgt5](https://user-images.githubusercontent.com/105374941/194050856-0fc76ff8-a9c1-42c3-bc17-6a0cba666e1c.png)




