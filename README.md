# OAuth2.0InSpringBoot
1) What Software/Technologies would you need?

STS (Spring Tool Suite) 
Dependent Starters : Spring Security, Spring Web, Cloud OAuth2, Spring Boot DevTools
JDK8 or later versions

2) Step 1 : Create App in Facebook

Before fallow step , you have to create account on meta for Developers.

Go to developers.facebook.com

Click on ‘My Apps’

Click on Create App, then ‘continue’

Set the Display Name of your application.

Enter the Contact Email.


Navigate to Facebook Login and press the Set up button.

Select Web from the displayed platforms.

Go to the Settings section and choose Basic.

Select the Website from the list.

Set the website URL address in the Site URL field and press the Save Changes button.

Navigate to Facebook Login section and press Settings.

Enter you Valid OAuth Redirect URLs. It differs depending on the software you are using it for. Usually, you can get  OAuth Redirect URL in the software settings info.

Make sure Enforce HTTPS option is enabled due to the Facebook Enforce HTTPS default setting.

Press the Save Changes button.

Once you've saved all the changes  Switch your Facebook APP to Live Mode.

Go to Settings > Basic. Here you can find the App ID and App Secret that you will need for software that uses Facebook APP.
