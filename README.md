# w21BankFrontEnd

Deployment
Deployment For React Standalone 

currently deployed in draft to AWS gigi-chaobankingapplication bucket. authentication required for access. 

done so far: 
Navigation Bar
Includes Create Account, Deposit, Withdraw, All Data, and Home pages

Routing: Each navigation bar item routes the user to the relevant page. For example, by selecting Home the user should be directed to the Home page. 
Styled with Bootstrap

May or may not use Create-React-App for build compiling later... 

More stuff I need to do in coming days: 

Website Functionality
website should include the following functionality. Please review the rubric below for specific information on how each element will be graded. 


Highlighting: Each navigation bar item is highlight when you are on that page. For example, Home is highlighted when you are on the home page. 
Hover effect: When your mouse hovers over a navigation bar item, you see a pop up with a description of that page.
2. Home Page
Includes bank title, image, and a welcome message. 
Styled as a Bootstrap card. 
3. Create Account Page
Includes a Bootstrap card with a form that has:
Name input field
Email address input field
Password input field
Create account button
4. Create Account Page Functionality

Create account page should include the following functionality:
Success message: Upon selecting the create account button the user should see a success message. 
Add Another Account Button: Upon selecting the create account button, the user should see an add another account button. 
Cleared Create Account Form: Upon selecting the create account button, t will open a cleared create account form.
Name validation: The user receives an alert if the name field is left blank. 
Email validation: The user receives an alert if this field is blank 
Password validation: The user receives an alert if the password is less than 8 characters long. 
Disable submit button if nothing is inputted
5. Deposit Page

Includes a Bootstrap card with a form that has:
Deposit input field 
Deposit button 
Balance information displays above deposit form on the card
6. Deposit Page Functionality

Deposit page should include the following functionality:
Updated Balance: When a user deposits, the balance updates. 
Success Message: When a user completes the deposit form, they receive a success message confirming their deposit was received. 
Not A Number Alert: User receives an alert if they add something that is not a number. 
Negative Deposit Alert: User receives an alert if they try to deposit a negative number.
Disable deposit button if nothing is input
7. Withdraw Page

Includes a Bootstrap card with a form that has:
Withdraw input field 
Withdraw button 
Balance information displays above deposit form on the card
8. Withdraw Page Functionality

Withdraw page should include the following functionality:
Updated Balance: When a user completes the withdrawal form, the number submitted is subtracted from the total balance. 
Success Message: When a user completes the withdrawal form, they receive a success message confirming that their withdraw was processed. 
Account Overdraft Feature: When a user withdraws a number higher than the account balance, the user receives an alert message on the withdraw page.
Not A Number Alert: User receives an alert if they add something that is not a number. 
Disable deposit button if nothing is input
9. All Data Page Functionality

All Data page includes the following functionality:
Track User Submissions: All user submissions appear on All Data page.
All Data Displayed On Bootstrap Card: All Data is styled and displayed on a Bootstrap card instead of JSON.
Submission Instructions:

Upload the link to your front end banking application website
The url should include your first name and last name
Note that the site should be deployed on a cloud service, like AWS3
Rubric can be downloaded here  Download here.

Rubric
Front End Banking Application Assignment Submission
Front End Banking Application Assignment Submission
Criteria	Ratings	Pts
This criterion is linked to a learning outcomeNavigation
15 Pts
Excellent
The navigation bar meets expectations and includes at least one creative styling, such as: Hover effect: When a user hovers their cursor over a navigation bar element, they see a few words describing that page Highlighting: The navigation bar highlights the element of the current page the user is on
10 Pts
Meets Expectations
1.The navigation bar includes the following pages: Create Account Deposit Withdraw All Data Home Page 2. When selected, each element on the navigation bar displays the correct page 3. Navigation bar is styled with Bootstrap
0 Pts
No Marks
There is no navigation bar The navigation bar contains default styling The navigation bar does not include all the required pages
15 pts
This criterion is linked to a learning outcomeHome Page
5 Pts
Meets Expectations
The Home Page includes a Bootstrap card with the following: Bank title Image Welcome message
0 Pts
Does Not Meet Expectations
There is no Home Page.  The Home Page does not include the following minimum requirements: Bank title Image Welcome message Home Page styled as a Bootstrap card
5 pts
This criterion is linked to a learning outcomeCreate Account Page
5 Pts
Meets Expectations
The Create Account page includes a Bootstrap card with a form that includes the following elements: Name input field Email address input field Password input field Create Account button
0 Pts
Does Not Meet Expectations
There is no Create Account page.  The Create Account page does not include the following minimum requirements:  Styled Bootstrap card with a form Form fields of name, email address, password Create Account button
5 pts
This criterion is linked to a learning outcomeCreate Account Page Functionality
10 Pts
Excellent
The Create Account page meets expectations and includes input validation. You will receive 1 point for each piece of input validation functionality implemented:  Name validation: The user receives an alert if the name field is left blank  Email validation: The user receives an alert if this field is blank  Password validation: The user receives an alert if the password is less than 8 characters long  Disabled Submit button: The Submit button should appear disabled in case of no input
6 Pts
Meets Expectations
The Create Account page includes the following functionality (you will receive 1 point for each piece of functionality implemented):  Success message: Upon selecting the Create Account button, the user should see a success message  Add Another Account button: Upon selecting the Create Account button, the user should see an Add Another Account button Cleared Create Account form: Upon selecting the Create Account button, the use will be able to open a Cleared Create Account form
0 Pts
No Marks
There is no Create Account page.  The Create Account page does not include at least one feature mentioned below:  Success message: Upon selecting the Create Account button, the user should see a success message  Add Another Account button: Upon selecting the Create Account button, the user should see an Add Another Account button  Cleared Create Account form: Upon selecting the Create Account button, the use will be able to open a Cleared Create Account form Submitted Create Account data: Submitted Create Account data appears on the All Data page.
10 pts
This criterion is linked to a learning outcomeDeposit Page
5 Pts
Meets Expectations
The Deposit page contains a Bootstrap card form with the following: Deposit input field  Deposit button  Balance information displayed above the Deposit form on the card
0 Pts
Does Not Meet Expectations
There is no Deposit page.  The Deposit page does not meet the following minimum requirements:  Deposit input field on a Bootstrap card Deposit button on a Bootstrap card Balance information displayed above the Deposit form on a Bootstrap card
5 pts
This criterion is linked to a learning outcomeDeposit Page Functionality
10 Pts
Excellent
The Deposit page meets expectations and includes input validation You will receive 1 point for each input validation functionality implemented:  Not A Number alert: The user receives an alert if they add something that is not a number  Negative Deposit alert: The user receives an alert if they try to deposit a negative number Disabled Deposit button: The Deposit button should appear disabled in case of no input
7 Pts
Meets Expectations
The Deposit page includes the following functionality: (You will receive 1 point for each piece of functionality implemented): Updated balance: When a user deposits, their balance gets updated  Success message: When a user completes the Deposit form, they receive a success message confirming their deposit was received
0 Pts
No Marks
There is no Deposit page. The Deposit page does not include at least one functionality described below:  Updated balance: When a user deposits, their balance gets updated  Success message: When a user completes the Deposit form, they receive a success message confirming their deposit was received
10 pts
This criterion is linked to a learning outcomeWithdraw Page
5 Pts
Meets Expectations
The Withdraw page includes a Bootstrap card with the following: Withdraw input field on a Bootstrap card Submit button on a Bootstrap card Balance information displayed above the Withdrawal form
0 Pts
Does Not Meet Expectations
There is no Withdraw page.  The Withdraw page does not meet the following minimum requirements:  Withdraw input field on a Bootstrap card Submit button on a Bootstrap card Balance information displayed above the Withdrawal form
5 pts
This criterion is linked to a learning outcomeWithdraw Page Functionality
10 Pts
Excellent
The Withdraw page meets expectations and includes input validation. You will receive 1 point for each input validation functionality implemented: Account overdraft feature: When a user withdraws a number higher than the account balance, the user receives an alert message on the Withdraw page Not a Number alert: User receives an alert if they add something that is not a number  Disabled Deposit button: The Deposit button should appear disabled in case of no input
7 Pts
Meets Expectations
The Withdraw page includes the following functionality. (you will receive 1 point for each piece of functionality implemented): Updated balance: When a user completes the Withdrawal form, the number submitted is subtracted from the total balance  Success message: When a user completes the Withdrawal form, they receive a success message confirming that their withdrawal was processed
0 Pts
No Marks
There is no Withdraw page.  The Withdraw page does not include at least one functionality described below: Updated balance: When a user completes the Withdrawal form, the number submitted is subtracted from the total balance  Success message: When a user completes the Withdrawal form, they receive a success message confirming that their withdrawal was processed
10 pts
This criterion is linked to a learning outcomeAll Data Page Functionality
10 Pts
Excellent
The All Data page meets expectations and includes the following feature improvement:  All data displayed on a Bootstrap card: All Data is styled and displayed on a Bootstrap card instead of JSON
8 Pts
Meets Expectations
The All Data page includes the following functionality: Track user submissions: All user submissions appear on the All Data page
0 Pts
No Marks
There is no All Data page.  No data appears on the All Data page.
10 pts
Total points: 75
