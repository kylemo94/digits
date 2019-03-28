<img src="doc/landingPage.png">
<p>The application digits allows users to:</p>
<p>1. Register an account on the webage.</p>
<p>2. Create, edit, and delete contacts.</p>
<p>3. Add notes to the bottom of each contact with a timestamp. </p>
<h3>Installation</h3>
<p> First, install <a href="https://www.meteor.com/install">Meteor</a></p>
<p>Second download a copy of <a href="https://github.com/kylemo94/digits">digits</a> . Digits is a private repo and you will need to request permission from the author.</p>
<p>Third, using the command prompt or terminal, you will cd into the app directory and install the required libraries using $ meteor npm install (for mac users) and meteor npm install (for windows users).</p>
<p>When the libraries are finished installing you can run the app using $ meteor npm run start (for mac users) and meteor npm run start (for windows users).</p>
<p>The first time the app is run, the default users and associated data will be created.</p>
<h3>Bcrypt warning</h3>
<p>A bcrypt warning wil show up when the app is run.</p>
<p>On some operating systems (particularly Windows), installing bcrypt is much more difficult than implied by the above message. Bcrypt is only used in Meteor for password checking, so the performance implications are negligible until your site has very high traffic. You can safely ignore this warning without any problems during initial stages of development.</p>
<p>You can check to see your running application at <a href="http://localhost:3000">http://localhost:3000</a></p>
<p>ESLint can be run on the imports/ directory code using meteor npm run lint.</p>
<h3>User Interface Walkthrough</h3>
<h4>Landing Page</h4>
<p>The first page that is shown will be the landing page, which contains brief information on what the digits application does.</p>
<img src="doc/landingPage.png">
<h4>SignIn/Register</h4>
<p>Pressing the login button will have a Sign In option or a Sign Up option. You can choose the option that applies to you.</p>
<h4>SignIn</h4>
<p>Clicking on the SignIn option will bring you to a login page shown below.</p>
<img src="doc/SignIn.png">
<h4>SingUp</h4>
<p>Clicking on the SignUp option will bring you to a register page shown below.</p>
<img src="doc/SignUp.png">
<h4>Homepage</h4>
<p>Clicking on the digits logo will bring you to the homepage</p>
<img src="doc/landingPage.png">
<h4>ListContacts</h4>
<p>Clicking on the ListContacts button will bring you to the current contacts in the database of the user. Timestamped notes can also be added here.</p>
<img src="doc/ListContacts.png">
<h4>Edit Contacts</h4>
<p>Clicking on the edit button on the ListContacts page will bring you to a page to edit the current contact.</p>
<h4>AddContact</h4>
<p>Clicking on the AddContact button will bring you to a form to add a new contact.</p>
<img src="doc/AddContact.png">
<h4>Admin</h4>
<p>The admin title is currently given to one user located in the settings.development.json file. More admins can be designated in this file. The admin has the ability to see all contacts of all users. </p>
<img src="doc/AdminContact.png">
