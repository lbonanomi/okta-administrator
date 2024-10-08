<table>
<tr><td>First Name</td><td>Last Name</td><td>Username/Email</td><td>Password</td></tr>
<tr><td>Anna</td><td>Wu</td><td>anna.wu@oktacertified.com</td><td>Testme321!</td></tr>
</table>

1. Configure a custom SAML 2.0 integration between Org1 (IdP) and Org2 (SP). Do NOT use the Okta Integration Network (OIN) to perform your integration. Name the integration Engapp.

2. Set up FirstName, LastName, and Email mapping from Org1 to Org2.

3. Use expression language to combine firstName and lastName in Org1 into a new attribute called empName and has the format ‘lastName.firstName’. For example, firstName: Anna and lastName: Wu should become empName: Wu.Anna.

4. Map empName in Org1 to DisplayName in Org2.

5. Assign the Everyone group to the Engapp application. Sign into Org1 as Anna Wu using the credentials in the table. Verify that Anna can access Org2 using the Engapp application.
