---
layout: default
---

# AGORA TV Manual

This app requires a Salesforce Org and an AGORA subscription. https://agora.pasonatquila.com/users/sign_up

```
Only for testing purposes you will be able to use test credentials and account.
Thank you for your understanding.
Any other feedback please contact us: jamaral@pasonatquila.com
```

Authentication through Agora and Salesforce using the provided 8 character code by Agora TV App.

You can use the following test credentials:

### AGORA
```
Username: (Provided in TestFlight)

Password: (Provided in TestFlight)
```

### Salesforce Login (Test Org)

```
Username: (Provided in TestFlight)

Password: (Provided in TestFlight)

Salesforce Consumer Key (needed for Login - related to TestFlight provided credentials)

3MVG9YDQS5WtC11qETBIbp9M2AllFRItqKW4DbaWEIQpCOKKpSId_6_v8_Byl2Ap9aQm4amW4C7QAoaGdT2yX
```


Or, you can use your own Salesforce Org if you do the following:
# How to setup your own Salesforce Org


## ❶ Installation of AGORA TV Salesforce Package on your Salesforce Org

https://login.salesforce.com/packaging/installPackage.apexp?p0=04t41000002utFi

Install for all users.

## ❷ Import Demo Template Data to your Salesforce Org

Use Salesforce Data Import Wizard and the following CSV file.

https://agoratv.herokuapp.com/AgoraCorporateTVDemoTemplate.csv

## ❸ Create a connected app for OAuth in your Salesforce Org

<dl>
<dt>Connected App Name</dt>
<dd>AgoraCorporateTV</dd>
<dt>API Name</dt>
<dd>AgoraCorporateTV</dd>
<dt>Contact Email</dt>
<dd> -- your own email -- </dd>
<dt>Logo Image URL</dt>
<dd>https://agoratv.herokuapp.com/img/agoratvlogoconnectedapp.png</dd>
</dl>
### API (Enable OAuth Settings)
<dl>
<dt>Enable OAuth Settings</dt>
<dd>☑ (Check)</dd>
<dt>Callback URL</dt>
<dd>https://agoratv.herokuapp.com/salesforce</dd>
<dt>Select OAuth Scopes</dt>
<dd>Full Access (full)<br/>Perform requests on your behalf at any time (refresh_token, offline_access)</dd>
<dt>Require Secret for Web Server Flow</dt>
<dd>☐ (Uncheck)</dd>
</dl>


### Manage your Connected App Policies (Edit Policies)

<dl>
<dt>Permitted Users</dt>
<dd>All Users may Self-Authorize</dd>
<dt>IP Relaxation</dt>
<dd> Relax IP Restrictions</dd>
<dt>Refresh Token Policy</dt>
<dd>Expire refresh token after 1 Month</dd>
</dl>

# How to configure your own AGORA TV Template

Change information on Salesforce Org according to information provided in https://agoratv.herokuapp.com/manual
to create your own Template and Corporate TV.


