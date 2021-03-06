# Photo Blog
An exercise to learn Angular from TreeHouse.

###To Start

1. Clone the repository
2. Run `npm install`
3. Start the server `npm run serve`

`npm run serve` traspiles the code and starts a webserver on port `8080`. Access the page 
via: `http://localhost:8080`.


###Development Notes

- [Angular Documentation](https://angular.io/docs/ts/latest)
- [TypeScript Documentation](http://www.typescriptlang.org/docs/tutorial.html)
- [Angular Components]()
An Angular application is made up of series of Components. A component has a template, styles, and handles business
logic.
- [Angular Style Guide](https://angular.io/docs/ts/latest/guide/style-guide.html)
- [Resources](https://angular.io/resources/)

**Component Decorator**
Components are the backbone of an Angular application. The Component Decorator is for defining a component and
registering it with Angular. Each component must have a selector and a template to be valid. Read the [Component 
Decorator](https://angular.io/docs/ts/latest/api/core/index/Component-decorator.html) documentation for more details.

**[Showing component properties with interpolation](https://angular.io/docs/ts/latest/guide/displaying-data.html#!#interpolation)**
The easiest way to display a component property is to bind the property name through interpolation. With interpolation,
you put the property name in the view template, enclosed in double curly braces: `{{myHero}}`.

**[Type Guard](https://basarat.gitbooks.io/typescript/content/docs/types/typeGuard.html)**
Type Guards allow you to narrow down the type of an object within a conditional block. TypeScript is aware of the usage
of the JavaScript instanceof and typeof operators. If you use these in a conditional block, TypeScript will understand
the type of the variable to be different within that conditional block.

**[String Literal Types](http://www.typescriptlang.org/docs/handbook/advanced-types.html#string-literal-types)**
String literal types allow you to specify the exact value a string must have. In practice string literal types combine
nicely with union types, type guards, and type aliases. You can use these features together to get enum-like behavior
with strings.

**[Barrel](https://angular.io/docs/ts/latest/guide/glossary.html#!#barrel)**
A way to roll up exports from several ES2015 modules into a single convenient ES2015 module. The barrel itself is an
ES2015 module file that re-exports selected exports of other ES2015 modules.

**[:host selector specification](https://www.w3.org/TR/css-scoping-1/#host-selector)**
Selecting Into the Light: the :host, :host(), and :host-context() pseudo-classes.

**[Angular Documentation for using :host selector](https://angular.io/docs/ts/latest/guide/component-styles.html#!#sts=:host)**
Angular can bundle component styles with components, enabling a more modular design than regular stylesheets.

**[Selecting Into the Light: the :host, :host(), and :host-context() pseudo-classes](https://www.w3.org/TR/css-scoping-1/#host-selector)**

**[Structural Directive (NgIf, NgFor) Documentation](https://angular.io/docs/ts/latest/guide/structural-directives.html)**
Angular has a powerful template engine that lets us easily manipulate the DOM structure of our elements. How Angular
manipulates the DOM with structural directives and how you can write your own structural directives to do the same
thing.

**[Attribute Directive (NgClass, NgStyle) Documentation](https://angular.io/docs/ts/latest/guide/attribute-directives.html)**
An Attribute directive changes the appearance or behavior of a DOM element.

**[Template Syntax](https://angular.io/docs/ts/latest/guide/template-syntax.html)**
The Angular application manages what the user sees and can do, achieving this through the interaction of a component
class instance (the component) and its user-facing template.

Consider the component/template duality based on model-view-controller (MVC) or model-view-viewmodel (MVVM). In Angular,
the component plays the part of the controller/viewmodel, and the template represents the view.

**[Modules](https://angular.io/docs/ts/latest/api/#!?query=module)**
Index of Angular modules available for addition to an Angual application to add functionality.

**[Observables](https://angular.io/docs/ts/latest/tutorial/toh-pt6.html#!#observables)**
An Observable is a stream of events that you can process with array-like operators. Angular core has basic support for
observables. Developers augment that support with operators and extensions from the RxJS library. Each Http service
method returns an Observable of HTTP Response objects. The HeroService converts that Observable into a Promise and
returns the promise to the caller.

**[Public, Private and Protected Modifiers](http://www.typescriptlang.org/docs/handbook/classes.html#public-private-and-protected-modifiers)**

**[Generics](https://www.typescriptlang.org/docs/handbook/generics.html)**

**[Angular In Memory Web API](https://github.com/angular/in-memory-web-api)**
An in-memory web api for Angular demos and tests. It intercepts Angular Http requests that would otherwise go to the 
remote server via the Angular XHRBackend service.

**[Life Cycle Hooks](https://angular.io/docs/ts/latest/guide/lifecycle-hooks.html)**
Angular calls lifecycle hook methods on directives and components as it creates, changes, and destroys them.

**[Angular Forms](https://angular.io/docs/ts/latest/guide/forms.html)**
An Angular form coordinates a set of data-bound user controls, tracks changes, validates input, and presents errors.

**[Augury Chrome Developer Tools Extension](https://chrome.google.com/webstore/detail/augury/elgalmkoelokbchhkhacckoklkejnhcd)**
Extends the Developer Tools, adding tools for debugging and profiling Angular applications.

**[TypeScript Generics](https://www.typescriptlang.org/docs/handbook/generics.html)**
A component that can work over a variety of types rather than a single one.

**[HTML5 Form Validation](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)**

**[NgIf Case Study and Documentation](https://angular.io/guide/structural-directives#!#ngIf)**
A  guide looks at how Angular manipulates the DOM with structural directives and how you can write your own structural 
directives to do the same thing.

**[Angular Documentation](https://angular.io/docs)**
Angular is a platform that makes it easy to build applications with the web. Angular combines declarative templates,
dependency injection, end to end tooling, and integrated best practices to solve development challenges. Angular
empowers developers to build applications that live on the web, mobile, or the desktop.

**[Angular CLI](https://cli.angular.io/)**
The Angular CLI makes it easy to create an application that already works, right out of the box. A generator of a
basic structure of an Angular application that follows best practices.

The Angular team has put a lot of thought into how best to build an Angular application. Angular's command line
interface is a tool to help you quickly build out components and a testing framework with your application.

**[TypeScript Configuration](https://angular.io/guide/typescript-configuration)**
A guide to some aspects of TypeScript configuration and the TypeScript environment that are important to Angular
developers, including details about the following files:

- tsconfig.json—TypeScript compiler configuration.
- typings—TypesScript declaration files.

**[Angular Style Guide](https://angular.io/guide/styleguide)**
The Angular style guide presents preferred conventions including explainations of why.

**[Angular Cheat Sheet](https://angular.io/guide/cheatsheet)**
**[Angular GitHub Repository](https://github.com/angular/angular)**
