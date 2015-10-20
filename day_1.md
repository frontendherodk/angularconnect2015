# Day 1

## Keynote
*Brad Green, Igor Minar and Jules Kremer*

### Status update

Angular started in 2009 as a framework to help developers.

First focus was development with boilderplate, structure and testing.

Then focus on accessibility, widgets and partnes.

Now focus in platform for angular 2, with simplicity and tooling.

1.1 mill Angular developers based on the people who came the Angular website.

A lot of products in Google are build with Angular eg, the chromecast interface, GA, Google trends etc.

Current numbers:
- Angular 1 **93%**.
- Angular 2 **7%**

Angular has 32 releases for Angular 1

### Features the Angular Team will work on

__Component Router__
- Including nested and parallel routes.

__Internationalization & Localization__
- High performance
- Translation workflows

__ngAnimate__
- Sequence control


### Angular 2 build for speed
__Performance areas__

- Load -> Compile -> Render -> Re-render
- Server-side pre-render with Angular Universal.
- Angular 2 will be 3 times faster to get the initial view than Angular 1.
- Ultra fast change-detection


### Angular 2 compared to other frameworks
[Insert graph here]

Uri Goldshtein working on the Meteor team showed an application build with different frameworks. Angular 1.4, Blase, React and Angular 2.0.
Angular 2 a lot more performant than the other frameworks *(Angular 2 is still alpha)*


### Angular-cli
Angular-cli to init an Angular application (worked with the guys from emebr-cli?)

- It follows a styleguide and you can generate components services etc. and follow the same style throughout the application.
- It will generate templates, css, and spec files for you with all the imports


### Chrome dev tool
Batarang + rangle = Batarangle. New chrome dev tool for debugging angular applications.


### Ionic 2
Ionic 2 - http://ionic.io/2


### Learning resources
- Egghead
- Pluralsight
- Rangle.io
- AngularClass
- Angular Development with Typescript.
- ng-book.com/ngconnect




# What's new in typescript
Goal: Make Javascript development more productive and enjoyable.
Typescript is a superset of javascript that compiles to plain javascript

Features form the future, today.

Static types = Better tooling



# Testing strategies in Angular 2

Use the smallest test type possible. If you can test it with unit test do it. Runs faster gives feedback faster

Test public interfaces. Write readable tests.

Don't mock unless there is a reason to.

Test all the time. Make tests fail.
Make sure they are running, and that you can debug them properly.

## Tools and setup
- TS
- Karma
- Jasmine

Seed repo that shows unit testing
https://github.com/juliemr/ng2-test-seed
