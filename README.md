# Typescript Labs

## Lab 5: Types to Variables

file: `/src/05-assigning-types-to-variables.problem.ts`
Here we have an interface that represents a user within our system:

```ts
interface User {
  id: number;
  firstName: string;
  lastName: string;
  isAdmin: boolean;
}
```

There's a function called getUserId that takes in a user, and returns its id.

Our test is currently failing, because it calls getUserId and passes in a defaultUser that doesn't match the User contract.

Challenge
Reference the [TypeScript docs](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html) and determine how to change defaultUser so that our test will pass.