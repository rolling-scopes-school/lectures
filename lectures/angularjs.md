## Curriculum
* AngularJS Intro
* Modules, Scopes, Controllers
* Directives, Components, Filters
* Services
* Routing
* Forms
* ngRedux
* Unit testing, E2E testing
## Slides
* [AngularJS Intro](https://slides.com/dzianisreznik/deck-6)
* [AngularJS Filters, Directives, Components](https://slides.com/dzianisreznik/deck-4d4335ab-a6b1-4043-a26c-ca2170d4599e#/)
* [AngularJS Services](https://slides.com/dzianisreznik/deck-7#/)
* [AngularJS Forms, ngRedux](https://slides.com/dzianisreznik/deck-8#/)
## Useful links
* [AngularJS Dev Guide](https://docs.angularjs.org/guide)
* [AngularJS Styleguide](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md)
* [Make Your Own  Scope and Digest](http://teropa.info/blog/2013/11/03/make-your-own-angular-part-1-scopes-and-digest.html)
* [Make Your Own  Scope and Digest (перевод)](https://habr.com/post/201832/)
* [Custom filters](https://toddmotto.com/everything-about-custom-filters-in-angular-js/)
* [Components/Directives good practice](https://gist.github.com/toddmotto/5b4de6c777d3e446e6410fdadb824522)
* [Bindings in AngularJS](http://blog.krawaller.se/posts/dissecting-bindings-in-angularjs/)
* [Understanding service types](http://angular-tips.com/blog/2013/08/understanding-service-types/)
* [$http vs $resource](http://ngninja.com/posts/angularjs-http-vs-resource)
* [Validation and error handling](https://steelkiwi.com/blog/validation-error-handling-angularjs-applicatios/)
* [ngRedux](https://github.com/angular-redux/ng-redux)
* [Why using Redux?](https://tech.webinterpret.com/why-we-decided-to-use-redux-in-our-angularjs-application/)
## Tasks
Final result is the AngularJS application with 3 pages:
1) Items list
2) Adding new item page with form
3) Page for each item
P.S. Styles for your app are optional.
### Task 1
* Initialize AngularJS project and set Webpack for it.
* Create one page application using controllers, binding and built-in directives and filters.
* The functionality of the project may be senseless, just try to use controllers, binding and built-in directives and filters.
### Task 2
* Create page with items list bult on components. Use ng-repeat and filter to search items.
* [More details](https://docs.google.com/document/d/1MqHzTH9ro9R8KRnRK1_x4AFexXDdB1UrmUtEt_Uy3ns/edit?usp=sharing)
### Task 3
* Create service, handling requests and storing data.
* Implement component routing. Create page template for item in list and implement the ability to go to the page of each item (/items/:id).
### Task 4
* Create page for adding a new item.
* Create simple form with validation.
* Store form's data in redux store.
* Handle submit event with function calling POST request from your service if the form is valid.
