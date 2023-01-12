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



Azure SAML configuration for Dynatrace

