# Fullstack-Banking-Application

PiggyBank
A fullstack MERN Banking App
Description

Interactive banking application that allows you to log in or sign up for a banking profile. From there, you are able to open as many accounts which you can make deposits or withdrawals from. I have created this application to practice how to create a Full Stack application using MERN.

Homepage default
Installation Guidelines

If you would like to copy the application, follow the steps below:

    Select the Fork button in the top right corner of the github repo.
    Click on the green Code button.
        You can either clone the repo via HTTPS or SSH link.
    Open up your terminal and navigation to where you would like to clone the project.
    Enter the command "git clone [HTTPS/SSH link]"
        You should be able to see the project files in the location selected in Step 3.
    Enter the command "npm install" to install the packages in the package.json.
    Enter the command "npm start" to start the project.

How to run

The Application features differ depending on state of user:

    Navigation This is the default homepage navigation upon opening the application. Homepage Navigation and this is the navigation when logged in. Homepage Navigation for logged in users You can see that the previous links have been replaced with icons (profile & logout) as well as the username. Homepage Link PiggyBank title is the link to the homepage. The homepage is available to logged in users and those not logged in. There is no content changes for the homepage.

    Signing up Visitors are welcomed to sign up for a user profile. The user profile will allow users to open bank accounts. There are 2 ways to sign up from the homepage:
        The welcome message card contains a link which will take you to the create profile page. Homepage "get started" Message *as a logged in user this link will take you straight to your profile.
        Then there is the Sign up link in the top navigation. Homepage Navigation Sign Up Link

    Homepage The homepage has cards to fill the application with content.

        First card is the welcome message with the link to "Get started". Homepage - welcome message

        Second card is a inspirational image for content. Homepage - inspo card
            Image changes and quote appears on hover. Profile - inspo card hover

        Third card contains mini cards of some services the bank offers. The mini cards have a hover interaction as well as links to the service page. Homepage - Service minicards
            quote appears on mouseover Profile - Service minicard hover
            LEARN MORE buttons take user to the Services page Service Page

    Profile Page Upon a successful login/signup, you are welcomed at the profile page. Profile Page
        Profile page will have the Total Funds which is the total balance of all accounts.

    There will be section where all the accounts are shown on cards. New users will just have a card to create an account. Profile - Create Account card The create account card is always present no matter how many accounts are opened. This is the only link to the create account page. Profile - Account cards Account cards have the Account Name, Balance and the Deposit, Withdraw, CLOSE Account buttons. Profile - Account card CLOSE Account will take you to the close account page. Users will asked to confirm whether they want to close the account or to go back to their profile page. Profile - Close Account Page At the bottom of the profile are buttons for the user benefits. Profile - End Content

    Create Account Form Add Another Account this is the only link you can return to the Create Account page after becoming a user. Create Account Form
        Creating an account starts with defining the account name.
        Then you must open that account with a starting balance.
        You can click the Create Account button to complete the create account process.
        Upon a successful account creation, user will be taken back to their profile page, where they will now be able to see the account they created.
        Clicking the x in the top right corner will close the Create Account form and return user to their profile page.

Account Activity: Profile - Account card

    Making a Deposit Deposit button will take the user to the deposit page. These buttons are the only path to the Deposit page. Deposit form
    Making a Withdrawal Withdraw button will take the user to the withdraw page. Like the Deposit buttons, these buttons are the only path to the Withdraw page. Withdrawal form
    Targeting Account for Deposit/Withdraw Account Card Logic - IDs The Account cards contain the account ids so which is being used to target which account is being passed into the URL path. Account Card Logic - urls

Services Page:

    The services page is just to create content for the banking application. The services are shown on individual cards. Services page - content

    Each card will have a link. Since this page is strictly for content, the links just open up a "Benefits Information" modal. Services page - content links Benefits Information Modal

    REVIEWS At the bottom of the homepage, there is a card which contains reviews made by users. Homepage - reviews Only logged in users can make reviews. Link to Review page is located under the user benefits buttons at the bottom of the profile page. This is the only link to the review page.

    Review link

    Review form input fields: Review form
        Title of review
        Review body
        Name
        top right x will close review page and return user back to their profile.

    Leaving Review Review will immediately populate in the homepage reviews card: Review populated

Logout: Logout button is only available to users who are logged in. Clicking the logout button will log the user out of their profile and redirect them to the homepage. 
