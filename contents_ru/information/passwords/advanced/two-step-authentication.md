[Title]: # (Двухэтапная аутентификация)
[Order]: # (2)

# Two-step authentication

Many services and software tools let you use two-step authentication. Here the idea is that in order to log in, you need to be in possession of a certain physical object: usually a mobile phone, but, in some versions, a special device called a security token. Using two-step authentication ensures that even if your password for the service is hacked or stolen, the thief won't be able to log in unless they also have control of a second device, such as your phone, and the special codes that only it can create.
![image](password_adv2.png)

Two-step authentication using a mobile phone can be done in two ways: your phone can run an authenticator application, such as [Google Authenticator](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2), which generates security codes that you need to provide when you try to log in, or alternatively the service can send you an SMS text message to your phone. This will help protect your account in situations where an attacker has your password but does not have physical access to your mobile phone. SMS text messages with two step codes can be intercepted so where possible it is better to use security codes created by an authenticator application.