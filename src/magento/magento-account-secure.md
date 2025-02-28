---
title: Securing Your Magento Account
group: getting-started
---

Two-factor Authentication (TFA or 2FA) is an added layer of security to better protect your Magento.com account from unauthorized users who might want to use your account in ways you do not want. TFA achieves this by requiring a _second factor_ (beyond your standard username and password combination) in order to complete the login process. This second factor takes the form of special, temporary verification codes that are continuously generated by a TFA application (on your mobile phone, for example) that is synced to your Magento.com user account. With TFA enabled, an unauthorized user must have your username and password combination (first factor) as well as access to the TFA application on your personal device (second factor) in order to log in to your Magento.com account --- much more difficult and, therefore, more secure.

## Before you begin

In order to use TFA, you must have a TFA application installed on your personal device (such as your smartphone, tablet, computer). There are many available, but some popular free options include:

- Google Authenticator (iOS, Android, Blackberry)

- Authy (iOS, Android)

- Microsoft Authenticator (iOS, Android, Windows Phone)

## Enable two-factor authentication

1. Go to the Commerce account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. In the left navigation pane, click **Account Settings** and click **Two-factor Authentication** underneath.

   ![]({% link images/images/magento-account-2fa-enable.png %}){: .zoom}
   _Enable TFA_

1. Click <span class="btn">Enable</span> to begin the two-factor authentication setup process.

1. Re-enter your **Password** and click <span class="btn">Verify Password</span> to continue.

   ![]({% link images/images/magento-account-2fa-enable-verify-password.png %}){: .zoom}
   _Verify password_

1. Open the two-factor authentication application you downloaded and installed on your personal device.

1. Enter the **Setup Code** into your two-factor authentication application.

   You can either scan the QR code using the TFA application or manually enter the code into your TFA application. This will sync your TFA application with your Magento.com account and allow your TFA application to generate verification codes that Magento.com will accept.

   {:.bs-callout-info}
   Verification Codes are constantly expiring and re-generated by your TFA application for security purposes, so **_always_** use the one that is currently displayed.

1. With your two-factor authentication application now synced to your Magento.com account, enter the **Verification Code** displayed in your two-factor authentication application and click <span class="btn">Verify Code</span> to continue.

   ![]({% link images/images/magento-account-2fa-setup-app.png %}){: .zoom}
   _Setup 2FA app_

1. Save the **Recovery Codes** presented in a safe and accessible place.

   In the event that you cannot provide a Verification Code to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a Recovery Code is the only way to regain access to your Magento.com account.

   Each Recovery Code is one-time use only, so do not try to re-use a Recovery Code you have already used previously (but you can always generate more---see the following for details). Recovery Codes are case-sensitive.

1. Select the confirmation checkbox and click <span class="btn">Submit</span> to continue.

   ![]({% link images/images/magento-account-2fa-store-recovery-codes.png %}){: .zoom}
   _Store recovery codes_

1. Enter a **Recovery Email** to help ensure that you can recover access to your account.

   This is needed in the event that you cannot generate a Verification Code from your two-factor authentication application and you do not have access to an unused pre-generated Recovery Code.

   Once every 24 hours, you will be able to generate and send a temporary Recovery Code to your designated Recovery email address that you can use to regain access to your account.

   {:.bs-callout-warning}
   It is imperative that you maintain access to the email account of your Recovery Email; otherwise, you will not be able to access any temporary Recovery Codes sent to that account.

   ![]({% link images/images/magento-account-2fa-set-recovery-email.png %}){: .zoom}
   _Set recovery email_

1. Select the confirmation checkbox and click <span class="btn">Submit</span> to complete the two-factor authentication setup process.

   - An email notification will be sent to the email address associated with your Magento.com to confirm that you have successfully enabled two-factor authentication.

   - An email notification will be sent to the Recovery Email you designated to confirm that particular email address is on file as your Recovery Email for receiving a temporary Recovery Code.

## Log in using a verification code

1. Go to the Magento account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Enter the **Verification Code** displayed in your two-factor authentication application when prompted.

   ![]({% link images/images/magento-account-2fa-login-verification-code.png %}){: .zoom}
   _Enter verification code_

1. Click <span class="btn">Submit</span> to complete the login process.

## Log in using a recovery code

1. Go to the Magento account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click <span class="btn">Use recovery code</span> to bypass the verification code prompt.

   ![]({% link images/images/magento-account-2fa-login-verification-code.png %}){: .zoom}
   _Enter verification code_

1. Enter an unused **Recovery Code** when prompted.

   ![]({% link images/images/magento-account-2fa-login-recovery-code.png %}){: .zoom}
   _Enter recovery code_

1. Click <span class="btn">Submit</span> to complete the login process.

## Log in using your recovery email

1. Log in to your Magento.com account at [https://account.magento.com/customer/account/login][1]{:target="_blank"}.

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Click <span class="btn">Use recovery code</span> to bypass the verification code prompt.

   ![]({% link images/images/magento-account-2fa-login-verification-code.png %}){: .zoom}
   _Use recovery code_

1. Click the **recovery email** link to have a temporary Recovery Code sent to the Recovery Email address on file for your Magento.com account.

   ![]({% link images/images/magento-account-2fa-login-recovery-email.png %}){: .zoom}
   _Use recovery email_

1. Access the email account of your Recovery Email to retrieve the temporary Recovery Code and enter it into the designated fields.

1. Click <span class="btn">Submit</span> to complete the login process.

   - Because the Recovery Email capability is only available once every 24 hours, it is strongly recommended that you generate new Recovery Codes and securely store them to avoid any future issues with accessing your Magento.com account.

   - It is also strongly recommended that you change your two-factor authentication application (if you have a device available) to able to generate Verification Codes again and use them to access your Magento.com account.

## View your recovery codes

1. Go to the Magento account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Complete the login process using one of the two-factor authentication methods described earlier.

1. In the left navigation pane, click **Account Settings** and click **Two-factor Authentication** underneath.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _2FA settings_

1. Click <span class="btn">View Recovery Codes</span> to view your pre-generated Recovery Codes.

1. Re-enter your **Password** and click <span class="btn">Verify Password</span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Save the **Recovery Codes** presented in a safe and accessible place.

   In the event that you cannot provide a Verification Code to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a Recovery Code is the only way to regain access to your Magento.com account.

   Each Recovery Code is one-time use only, so do not try to re-use a Recovery Code you have already used previously (but you can always generate more---see the following for details). Recovery Codes are case-sensitive.

   ![]({% link images/images/magento-account-2fa-view-recovery-codes.png %}){: .zoom}
   _View recovery codes_

1. Select the confirmation checkbox and click <span class="btn">Submit</span> to close the dialog.

## Generate new recovery codes

1. Go to the Magento account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Complete the login process using one of the two-factor authentication methods described earlier.

1. In the left navigation pane, click **Account Settings** and click **Two-factor Authentication** underneath.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _TFA settings_

1. Click <span class="btn">Generate New Recovery Codes</span> to generate new pre-generated Recovery Codes.

1. Re-enter your **Password** and click <span class="btn">Verify Password</span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Save the **Recovery Codes** presented in a safe and accessible place.

   In the event that you cannot provide a Verification Code to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a Recovery Code is the only way to regain access to your Magento.com account.

   All previously generated Recovery Codes are now rendered invalid and should be discarded (only the current set of generated Recovery Codes will work). Recovery Codes are case-sensitive.

   ![]({% link images/images/magento-account-2fa-generate-recovery-codes.png %}){: .zoom}
   _Generate recovery codes_

1. Select the confirmation checkbox and click <span class="btn">Submit</span> to close the dialog.

## Change your recovery email

1. Go to the Magento account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Complete the login process using one of the two-factor authentication methods described earlier.

1. In the left navigation pane, click **Account Settings** and click **Two-factor Authentication** underneath.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _TFA settings_

1. Click <span class="btn">Change Recovery Email</span> to change the Recovery Email on file for your account.

1. Re-enter your **Password** and click <span class="btn">Verify Password</span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Enter a **Recovery Email** to help ensure that you can recover access to your account.

   This is needed in the event that you cannot generate a Verification Code from your two-factor authentication application and you do not have access to an unused pre-generated Recovery Code.

   Once every 24 hours, you will be able to generate and send a temporary Recovery Code to your designated Recovery email address that you can use to regain access to your account.

   {:.bs-callout-warning}
   It is imperative that you maintain access to the email account of your Recovery Email; otherwise, you will not be able to access any temporary Recovery Codes sent to that account.

   ![]({% link images/images/magento-account-2fa-set-recovery-email.png %}){: .zoom}
   _Set recovery email_

1. Select the confirmation checkbox and click <span class="btn">Submit</span> to close the dialog.

   This sends an email notification to the Recovery Email you designated to confirm that particular email address is on file as your Recovery Email for receiving temporary Recovery Codes.

## Change your two-factor authentication application

1. Go to the Magento account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Complete the login process using one of the two-factor authentication methods described earlier.

1. In the left navigation pane, click **Account Settings** and click **Two-factor Authentication** underneath.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _TFA settings_

1. Click <span class="btn">Change TFA Application</span> to use a different TFA application with your Magento.com account.

1. Re-enter your **Password** and click <span class="btn">Verify Password</span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Open the two-factor authentication application you downloaded and installed on your personal device.

1. Enter the **Setup Code** into your two-factor authentication application.

   You can either scan the QR code using the two-factor authentication application or manually enter the code into your two-factor authentication application. This will sync your two-factor authentication application with your Magento.com account and allow your two-factor authentication application to generate verification codes that Magento.com will accept.

   {:.bs-callout-info}
   Verification Codes are constantly expiring and re-generated by your two-factor authentication application for security purposes, so **always** use the one that is currently displayed.

1. With your TFA application now synced to your Magento.com account, enter the **Verification Code** displayed in your TFA application and click <span class="btn">Verify Code</span> to continue.

   ![]({% link images/images/magento-account-2fa-setup-app.png %}){: .zoom}
   _Setup TFA app_

1. Save the **Recovery Codes** presented in a safe and accessible place.

   In the event that you cannot provide a Verification Code to log into your Magento.com account (due a variety of reasons like uninstalling your two-factor authentication application, performing a factory reset on your personal device, losing your personal device, forgetting the password to your personal device, etc.), using a Recovery Code is the only way to regain access to your Magento.com account.

   Each Recovery Code is one-time use only, so do not try to re-use a Recovery Code you have already used previously (but you can always generate more---see the previous for details). Recovery Codes are case-sensitive.

1. Select the checkbox to confirm and click <span class="btn">Submit</span> to continue.

   ![]({% link images/images/magento-account-2fa-store-recovery-codes.png %}){: .zoom}
   _Store recovery codes_

1. Enter a **Recovery Email** to help ensure that you can recover access to your account.

   This is needed in the event that you cannot generate a Verification Code from your two-factor authentication application and you do not have access to an unused pre-generated Recovery Code.

   Once every 24 hours, you will be able to generate and send a temporary Recovery Code to your designated Recovery email address that you can use to regain access to your account.

   {:.bs-callout-warning}
   It is imperative that you maintain access to the email account of your Recovery Email; otherwise, you will not be able to access any temporary Recovery Codes sent to that account.

   ![]({% link images/images/magento-account-2fa-set-recovery-email.png %}){: .zoom}
   _Set recovery email_

1. Select the confirmation checkbox and click <span class="btn">Submit</span> to complete the two-factor authentication setup process.

   An email notification will be sent to the Recovery Email you designated to confirm that particular email address is on file as your Recovery Email for receiving a temporary Recovery Code.

## Disable two-factor authentication

1. Go to the Magento account login: [https://account.magento.com/customer/account/login][1]{:target="_blank"}

1. Enter your username and password combination, and then click <span class="btn">Login</span> to log into My Account.

   ![]({% link images/images/magento-account-login.png %}){: .zoom}
   _Account log in_

1. Complete the login process using one of the two-factor authentication methods described earlier.

1. In the left navigation pane, click **Account Settings** and click **Two-factor Authentication** underneath.

   ![]({% link images/images/magento-account-2fa-manage.png %}){: .zoom}
   _TFA settings_

1. Click <span class="btn">Disable</span> to begin the TFA deactivation process.

1. Re-enter your password and click <span class="btn">Verify Password</span> to continue.

   ![]({% link images/images/magento-account-2fa-manage-verify-password.png %}){: .zoom}
   _Verify password_

1. Select the confirmation checkbox and click <span class="btn">Submit</span> to complete the deactivation for two-factor authentication.

   You will also receive an email confirmation indicating that TFA has been disabled on your Magento.com account.

   ![]({% link images/images/magento-account-2fa-disable-confirmation.png %}){: .zoom}
   _Disable TFA_

[1]: https://account.magento.com/customer/account/login
[2]: https://community.magento.com/
