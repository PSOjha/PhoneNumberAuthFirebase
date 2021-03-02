# PhoneNumberAuthFirebase
Phone authentication is one of its features, which provides authentication using mobile numbers along with the country code.

#### Why Phone Number Authentication?

There are a few benefits to using phone number-based authentication:

- Avoid duplicate accounts: When you create an account based on a unique phone number, it’ll be hard to create multiple accounts.
- Security: With phone number verification, users won’t have any passwords, so every time they log in, it can be done with a dynamic verification code sent directly to their mobile.
- User experience: Phone number verification reduces the friction for the users to log in, as they don’t have to remember any password.

 #### Why Firebase?

- Implementing phone number authentication involves sending an SMS to a user’s mobile. To do so, we need to pay for SMS services. But via Firebase, we can send an SMS without any cost. Firebase offers 10,000 verifications per month under the free plan.
