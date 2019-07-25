# [single-spa](https://single-spa.js.org)
* Javascript micro-frontends framework
* Use multiple UI frameworks (React, AngularJS, Angular, Ember, etc)
* Deploy your microfrontends independently.
* Write cod using new framework, without rewriting your existing app
* Lazy load code for imporved initial load time.

single-spa apps consist of 2 factors
1. Application
2. single-spa-config
: 각각의 application이 등록되기 위해서는 아래의 3가지가 필요하다.
	* A name
	* A function to load the application's code
	* A function that determines when the application is active/inactive
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjg1MzU5MzUxLDIwNzU4NDQ2MTldfQ==
-->