# frontend-interview-questions

## JS/TS

- What is a promise?
- How to implement a promise yourself? (plain JS, no library, no `new Promise()` no `async`)
- What is rxjs?
- What is the shortest valid JS code?
- Why TypeScript?
- What is decorator?

## Unit testing

- How to unit test JS/TS code?
- Explain the test pyramid?
- What are some drawbacks to TDD?

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
