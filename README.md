# frontend-interview-questions

## JS/TS

- What is truthiness and falsiness in JS?
- Why use the `===` operator over the `==` operator?
- What is the difference between `null`, `undefined`?
- What is the difference between `Object.create(null)` and `{}`?
- What is a promise?
- Of what type is `somePromise.then(someFn)`?
- How to implement a promise yourself? (plain JS, no library, no `new Promise()` no `async`)
- When would one want to use `var`, when to use `let`, when to use `const`?
- What is rxjs?
- What is decorator?
- Why TypeScript?
- What are generics in TypeScript?
- How to move from a JS codebase to a TS codebase?
- How to test JS/TS code?

### JS fun questions

- What is the shortest valid JS code?
- Why is there ECMAScript? Where did JavaScript come from?
- Name some JS runtimes? Elaborate!
- How to separate code in JS?
- What are callbacks? When to use them? What are some drawbacks to callbacks?

## Unit testing

- How to unit test JS/TS code?
- Explain the test pyramid?
- What are some drawbacks to TDD?
- What is a mock, a stub, a spy, a test double?
- Name some of the types of libraries one might use in unit testing!

## Design patterns

- What is functional programming?
- What is a factory? 
- Name some design patterns!

## Angular

- What is Angular?
- What is a component?
- What are the basic elements of an Angular app?
- Name common design patterns in an Angular app!
- How to approach routing?
- Explain template-driven and reactive (dynamic) forms!
- Name some common approaches to state management!
- How do you unit test in Angular?

## CSS

- What is grid, what is flexbox?
- What are container queries?
- How to test CSS?

### CSS fun questions

- Is CSS a programming language?
- How to prevent a CSS codebase from degenerating?

## Tricky questions

Is `Math.random` a pure function? Elaborate!

Is `myRandom` a pure function? Elaborate!

```ts
function myRandom(numbers: Number[], pickRandomValueFn: (numbers: Number[]) => Number): Number {
    return pickRandomValueFn(numbers);
}
```

## Example tasks

- What would you do, if you were tasked with writing unit tests for the `+` operator?
- Simple unit test https://stackblitz.com/edit/node-1plthi?file=test.js,trim-response.js
