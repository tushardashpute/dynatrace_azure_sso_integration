# Dynatrace_azure_sso_integration


**Prerequisites**

To get started, you need the following items:

An Azure AD subscription. If you don't have a subscription, you can get a free account.
Dynatrace single sign-on (SSO) enabled subscription.

Steps:
======
1. Add Dynatrace from the gallery to Azure
2. Configure Azure AD SSO
3. Configure Dynatrace SSO
4. Test SSO

**1. Add Dynatrace from the gallery**

To configure the integration of Dynatrace into Azure AD, you need to add Dynatrace from the gallery to your list of managed SaaS apps.

- Sign in to the Azure portal using either a work or school account, or a personal Microsoft account.
- On the left navigation pane, select the Azure Active Directory service.

<img width="1550" alt="image" src="https://user-images.githubusercontent.com/74225291/211815104-df956c6b-bdeb-48c8-b915-c2baf3c2d0c8.png">

- Navigate to Enterprise Applications, and then select All Applications.
- To add new application, select New application.

<img width="1693" alt="image" src="https://user-images.githubusercontent.com/74225291/211815412-0b26a326-dc70-48ca-ae4f-933c6ccb6927.png">

- In the Add from the gallery section, type Dynatrace in the search box.
- Select Dynatrace from results panel and then add the app. Wait a few seconds while the app is added to your tenant.

<img width="1744" alt="image" src="https://user-images.githubusercontent.com/74225291/211815497-46aba4f1-60e1-403b-becc-c15bb8ddeb8e.png">

**Configure and test Azure AD SSO for Dynatrace**

Configure and test Azure AD SSO with Dynatrace using a test user called Vihan.D. For SSO to work, you need to establish a link relationship between an Azure AD user and the related user in Dynatrace.

To configure and test Azure AD SSO with Dynatrace, complete the following building blocks:

- Configure Azure AD SSO - to enable your users to use this feature.
- Create an Azure AD test user - to test Azure AD single sign-on with tushar.
- Assign the Azure AD test user - to enable tushar to use Azure AD single sign-on.
- Configure Dynatrace SSO - to configure the single sign-on settings on application side.
- Create Dynatrace test user - to have a counterpart of tushar in Dynatrace that is linked to the Azure AD representation of user.
- Test SSO - to verify whether the configuration works.


**2. Configure Azure AD SSO**

Follow these steps to enable Azure AD SSO in the Azure portal.

- In the Azure portal on the Dynatrace application integration page, find the Manage section and select single sign-on.
- On the Select a single sign-on method page, select SAML.

<img width="1544" alt="image" src="https://user-images.githubusercontent.com/74225291/211816424-72b63a14-f10b-4e0d-9457-2393920c6fdf.png">

- On the Set up single sign-on with SAML page, click the pencil icon for Basic SAML Configuration to edit the settings.

<img width="921" alt="image" src="https://user-images.githubusercontent.com/74225291/211964871-3923ef2e-b3d2-491f-8277-7174d8296e3c.png">


- In the Basic SAML Configuration section, the application is pre-configured in IDP initiated mode and the necessary URLs are already pre-populated with Azure. The user needs to save the configuration by clicking the Save button.
- Click Set additional URLs and complete the following step to configure the application in SP initiated mode:
- In the Sign-on URL text box, type the URL: https://sso.dynatrace.com/

On the Set up single sign-on with SAML page, in the SAML Signing Certificate section, find **Federation Metadata XML**. Select Download to download the certificate and save it on your computer.

<img width="825" alt="image" src="https://user-images.githubusercontent.com/74225291/211965656-54a6809f-5aa8-413e-92d5-986caa2a09ab.png">

- In the SAML Signing Certificate section, select the Edit button to open the SAML Signing Certificate dialog box. Complete the following steps:

a. The Signing Option setting is pre-populated. Please review the settings as per your organization.

b. Click Save.

![image](https://user-images.githubusercontent.com/74225291/211966019-e384cb9b-32c8-480b-bfa3-54db490ca7c2.png)

In the Set up Dynatrace section, copy the appropriate URL(s) based on your requirement.

<img width="789" alt="image" src="https://user-images.githubusercontent.com/74225291/211966257-232687ea-a1df-4e6f-aebd-a2e369b253f1.png">

<img width="810" alt="image" src="https://user-images.githubusercontent.com/74225291/211819483-53028b3f-bf81-4ac6-a45f-f1062db1b031.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/74225291/211819575-6b6271b1-f613-4f69-94d3-b73ce72cf0da.png">

**Create an Azure AD test user**

- From the left pane in the Azure portal, select Azure Active Directory, select Users, and then select All users.
- Select New user at the top of the screen.
- In the User properties, follow these steps:
- In the Name field, enter tushar.
- In the User name field, enter the username@companydomain.extension. For example, tushar@tushar10pute.click
- Select the Show password check box, and then write down the value that's displayed in the Password box.
- Click Create.

<img width="1254" alt="image" src="https://user-images.githubusercontent.com/74225291/212028421-d974eea4-59e1-41dd-8df8-7b4a186dde00.png">

**Assign the Azure AD test user**

In this section, you'll enable vihan to use Azure single sign-on by granting access to Dynatrace.

- In the Azure portal, select Enterprise Applications, and then select All applications.
- In the applications list, select Dynatrace.
- In the app's overview page, find the Manage section and select Users and groups.

<img width="1754" alt="image" src="https://user-images.githubusercontent.com/74225291/212031308-ef66a7c4-0268-496e-9ff3-96194d73bcef.png">

- Select Add user, then select Users and groups in the Add Assignment dialog.

<img width="1640" alt="image" src="https://user-images.githubusercontent.com/74225291/212031578-448fc993-b0cc-4610-89ec-d0986c347c1b.png">

- In the Users and groups dialog, select vihan from the Users list, then click the Select button at the bottom of the screen.

<img width="1792" alt="image" src="https://user-images.githubusercontent.com/74225291/212031812-4474852f-c1fa-44dd-8095-9170333e00c1.png">

- If you are expecting a role to be assigned to the users, you can select it from the Select a role dropdown. If no role has been set up for this app, you see "Default Access" role selected.
- In the Add Assignment dialog, click the Assign button.

<img width="1619" alt="image" src="https://user-images.githubusercontent.com/74225291/212031923-60b5b2f6-b48b-4bc1-8046-d47d3c5dab23.png">

**3. Configure Dynatrace SSO**

- Goto Account Settings (below the account details in top right corner).
- Choose Identity management from the application’s left-hand navigation to configure user access to the Dynatrace application.

<img width="1758" alt="image" src="https://user-images.githubusercontent.com/74225291/212033969-1257d87a-ec85-4992-95c1-ece24c2c6661.png">

- Click on Single sign-on 
- Enter domain name and verify it

<img width="1212" alt="image" src="https://user-images.githubusercontent.com/74225291/212035766-890220c2-9fa2-4788-9922-5f8c10881af1.png">

- Copy the value and create TXT record in your route 53 to verify it.

<img width="1386" alt="image" src="https://user-images.githubusercontent.com/74225291/212035554-684a54ff-b440-45ab-ac55-1c479a8e3cc5.png">

- After verification you will see it added in the verified domain.

<img width="1512" alt="image" src="https://user-images.githubusercontent.com/74225291/212036218-8203b0fb-641e-4e73-8ff5-802d0b19f478.png">

- click on the edit configuration
- In Upload XML, provide the metadata you downloaded as Federated Metadata XML and set the following attributes:

    First name attribute http://schemas.xmlsoap.org/ws/2005/05/identity/claims/givenname
    Last name attribute http://schemas.xmlsoap.org/ws/2005/05/identity/claims/surname
    Security group claim attribute http://schemas.microsoft.com/ws/2008/06/identity/claims/groups

<img width="1761" alt="image" src="https://user-images.githubusercontent.com/74225291/212036447-44c73a9a-5979-4c53-b0c2-26810a4fcc6b.png">

- Click on validate configuration 

**4. Test SSO**

- Click on Test this application in Azure portal. This will redirect to Dynatrace Sign on URL where you can initiate the login flow.

- Go to Dynatrace Sign-on URL directly and initiate the login flow from there.

Logged in with the new user "vihan@tushar10pute.click"

<img width="1792" alt="image" src="https://user-images.githubusercontent.com/74225291/212039933-4413d3eb-ddf1-4a1d-be14-00be4f71fe6e.png">

Enter the mail id of user which you created.

<img width="1785" alt="image" src="https://user-images.githubusercontent.com/74225291/212040084-fc8b92e6-c533-4db7-8cb9-8772452f7199.png">

<img width="1791" alt="image" src="https://user-images.githubusercontent.com/74225291/212040365-fab7bbe4-ca62-4766-b0d1-99c63e0348a5.png">

You will be able to login to dynatrace using username only.


**References:**

- https://learn.microsoft.com/en-us/azure/active-directory/saas-apps/dynatrace-tutorial
- https://www.dynatrace.com/support/help/how-to-use-dynatrace/user-management-and-sso/manage-users-and-groups-with-saml/saml-azure
- https://www.dynatrace.com/support/help/how-to-use-dynatrace/user-management-and-sso/manage-users-and-groups-with-saml/saml-azure#expand--example-search-for-dynatrace-application
- https://aws.amazon.com/blogs/apn/aws-single-sign-on-integration-guide-for-dynatrace/
