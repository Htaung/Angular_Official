Deployed Web site on Firebase 

https://angular-228c0.web.app/portal

Deploy angular on firebase

https://medium.com/@treviergits/how-to-deploy-an-angular-7-app-on-firebase-hosting-30341f3bcb22

https://angular.io/start/start-deployment



0.Create New Project in Firebase
<code> https://console.firebase.google.com/ </code>

1.First Build angular 
<code>ng build --prod</code>

2.copy project-folder under dist folder and paste it into created new directory so called Deployment
<code> Deployment> MyApp </code>

3.Installed Firebase tool
<code> npm install -g firebase-tools </code>

4. Login to firebase
<code>firebase login</code>

5. Fire base init
<code>firebase init</code>

6.Select "Hosting" option

7.Use Existing Project

8.If asked for “What do you want to use as your public directory?”
Type your app folder (eg. MyApp)

9.Select “no” to overwriting your existing index.html (if applicable).

10.firebase deploy
<code> firebase deploy </code>
