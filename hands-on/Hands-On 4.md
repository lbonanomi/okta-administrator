<table>
<tr><td>First Name</td><td>Last Name</td><td></td>Username/Email</td><td>Password</td></tr>
<tr><td>Jeremy</td><td>Steel</td><td>jeremy.steel@oktacertified.com</td><td>Testme321!</td></tr>
</table>

1. Set Password and Email as Required and the only available enrollment options in the Default Enrollment Policy for Authenticators.

2. In the Global Session Policy, add a new rule to the Default Policy. Name the new rule Session Rule and enable "Establish the user session" with a password. Set the ‘Maximum Okta global session lifetime’ to 7 days.

3. Define an authentication policy that requires Password and Email if the user is a user type of Intern and is trying to access the Engapp application. Name the policy `Intern Policy` and the rule `Intern Rule`. Enable the following settings in the Intern Rule:  
  
And Prompt for password authentication: When an Okta global session doesn’t exist  
And Prompt for all other factors: Every time user signs in to resource  
  
4. If you can, use a personal email address to receive the Email verification code. Otherwise, if you are taking this exam on a device that is locked down, you may have to use a work email address. Edit Jeremy Steele’s Okta Profile and set his primary email to the email address that you are using for this step.

5. Log in as Jeremy Steel to verify that you are prompted for Email verification upon clicking the Engapp tile from the Okta dashboard in Org1.

6. Complete the login by accessing the email with Jeremy’s verification code.
