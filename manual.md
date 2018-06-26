---
layout: default
---

## AGORA TV Manual

This app requires a Salesforce Org and an AGORA subscription. https://agora.pasonatquila.com/users/sign_up

> Only for testing purposes you will be able to use test credentials and account.
> Thank you for your understanding.
> Any other feedback please contact us: jamaral@pasonatquila.com

Authentication through Agora and Salesforce using the provided 8 character code by Agora TV App.

You can use test credentials:

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

AGORA

Username: (Provided in TestFlight)

Password: (Provided in TestFlight)

Salesforce Login (Test Org)

Username: (Provided in TestFlight)

Password: (Provided in TestFlight)

Salesforce Consumer Key (needed for Login - related to TestFlight provided credentials)

3MVG9YDQS5WtC11qETBIbp9M2AllFRItqKW4DbaWEIQpCOKKpSId_6_v8_Byl2Ap9aQm4amW4C7QAoaGdT2yX

Or, you can use your own Salesforce Org if you do the following:

❶ Installation of AGORA TV Salesforce Package on your Salesforce Org

https://login.salesforce.com/packaging/installPackage.apexp?p0=04t41000002utFi

Install for all users.

❷ Import Demo Template Data to your Salesforce Org

Use Salesforce Data Import Wizard and the following CSV file.

https://agoratv.herokuapp.com/AgoraCorporateTVDemoTemplate.csv

❸ Create a connected app for OAuth in your Salesforce Org

Connected App Name: AgoraCorporateTV

API Name: AgoraCorporateTV

Contact Email: 

Logo Image URL: https://agoratv.herokuapp.com/img/agoratvlogoconnectedapp.png


API (Enable OAuth Settings)

Check Enable OAuth Settings

Callback URL: https://agoratv.herokuapp.com/salesforce

Select OAuth Scopes:

Full Access (full)

Perform requests on your behalf at any time (refresh_token, offline_access)

Uncheck Require Secret for Web Server Flow


Manage your Connected App Policies (Edit Policies)

Permitted Users > All Users may Self-Authorize

IP Relaxation > Relax IP Restrictions

Refresh Token Policy > Expire refresh token after 1 Month


TEST 2:
Change information on Salesforce Org according to information provided in https://agoratv.herokuapp.com/manual
to create your own Template and Corporate TV.

Thank you.
        

