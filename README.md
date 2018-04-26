# LearnAngular
Learning Angular Notes:


Angular 5 Breakout: Watch Michael’s break out video

* Facebook: maintains React

* Google: maintains Angular

* Even You from Google: maintains Vue



* Angular 5 is an object oriented framework.

* Angular 1 is now known as Angular.js

* Angular goes along with Materialize.css because it’s also part of Google.  Angular Material is just that. Angular Material is Angular 2. 

* Be careful not to mix the versions.  Be aware of Angular.js

* There are a lot of terms in Angular. It helps to have names to match concepts. 

* Angular is a type script language labeled ts


* Added Angular to my cli, along with Augury to Chrome extensions.
* Check out Dan Levy’s video on object oriented programming, part of bucket five.
* RxJs is something you can use alongside Angular or React or Vue

* To create a new project just use ng new (name of directory)
* Cd into the name of that directory
* In the ouster folder we have:
	-  .angular-cli.json
	- .editorconfig
	- .gitignore
	- karma.conf.js
	- package-lock.json
	- package.json
	- protractor.conf.js
	- tsconfig.json
	- tslint.json

	- the src has everything we need in it, where you will find the app folder
	- for our drills, we don’t need any of the test files in app or in the outer folder

* You use ng serve -  - open (those two dashes touch)
* Ng serve -  -port 4300 (those two dashes touch)


** @component is like a flag like selectors
* Type ng generate component components/header to have html
* Now add a footer ng generate component components/foorter -  -spec false
* The -  -spec false keeps the test folder from generating with
* Ng g c job-list -  -spec false 
* All of those commands create a css, ts, and html for each
* Try to keep my components short and sweet
* To copy everything from the drill that we need to the Angular project we are working on, do it in your finder:
* Code .
* Open .
* Directory
* Open .

* When styling the css that affects every part of the site, go outside the src folder to styles.css, because that’s where the body tag should lie.
* Ng g s services/http-service -  -spec false (this is getting data using http service or module)
* Ng g interface models/Job -  -spec false
* To inject a service, put it in the constructor in the job-list-components.ts
* OnInit is how Angular handles lifecycle methods/hooks
* .subscribe() is a higher order method
