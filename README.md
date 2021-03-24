Login and Authentication in Firebase
Firebase authentication is used to authenticate the users of applications in a very easy manner. Not only for the users but for the developers also, it provides a very easy flow for the authentication and login process that is present in almost every application.

Firebase supports authentication using email and password, phone numbers or even you can use facebook, google, twitter, github, etc.
To authenticate your users, all you need to do is get the authentication credentials from the user and then pass this credential to the Firebase Authentication SDK. These credentials can be email-password or mobile number or any token from identity providers like facebook, google, twitter, github, etc. After passing the credentials, Firebase will verify the credentials and in return, you will get a response that tells you if the authentication is successful or not.

Note: By default, the authenticated users can read/write the data from the realtime database or cloud storage.
Now, let's see how we can use Firebase login or authentication in our application.

Example - Email login and registration
In this section of the blog, we will learn how to login and register using Email and Password with the help of Firebase. In this example, we will be having four activities i.e. one for Login, one for Registration, one for password reset and one will be our MainActivity. The following image will describe the flow of activities:
