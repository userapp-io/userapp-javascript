UserApp API JavaScript Client
================================

Use this client library to gain full access to the UserApp API from your JavaScript application.

## How do I start?

1. Sign up for an account at https://www.userapp.io/
2. Include `userapp.client.js` on your site.
3. Initialize UserApp by running `UserApp.initialize({appId:'YOUR APP ID'});`.
4. Try it out!
	1. Add a user to your app: `UserApp.User.save({login:'epicme',email:'epic@testing123.cmo',password:'epiq'}, function(e,r){});`
	2. Login the user you just added: `UserApp.User.login({login:'epicme',password:'epiq'}, function(e,r){});`
	3. Print the logged-in user: `UserApp.User.get({user_id:'self'}, function(error, user){console.log(user);});`.
5. Enjoy!

## Having any problems?

* Read the API documentation (http://localhost:8085/webapp/#/docs/libs/javascript/)
* Check our support center (https://help.userapp.io/) to see if we've already answered your question.
* Ask a question. Either at https://help.userapp.io/customer/portal/emails/new or email us at support@userapp.io.

## Want to show some love?

Tweet us @userapp_io


//Live long and prosper!