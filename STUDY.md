# My study sheet

Here I will add comments about the course.

## Components

Split your code to more than one component, like one for Navbar, one for Main page etc..
Each component has its own css, code and files.

Components can be used also by class or attributes by manipulating with `selector`.
Like for class we use `'selector: .app-servers'`, for attribute `'selector: [app-servers]`.

`.spec` files are for testing.

## Decorator

Decorator are a TypeScript feature which allow you to enhance your component, enhance elements you use in your code.

### Using CLI to create a new component

`ng create component servers` or `ng g c servers`, after creating, CLI updates app.module for its imports and includes.

## Databinding

Databiding=Communication, communication between your TypeScript code of your component, your business logic, and the template.

## Directives

Directives are instructions in the DOM, and we actually already use directives without knowing it.
Components are kind for such instructions in the DOM
"Angular, please add our component in this place!".

```
@Directive({
    selector:'[appTurnGreen]'
})
```

`*ngFor` For loop, `*ngIf` for if/else.
