- `npm install`
- open workspace in vs code
- open src/app/app.component.spec.ts
- click typescript version number in status bar and switch to use the workspace version of typescript
- notice the new strict property initialization of typescript 2.7:
  ```
  foo!: Foo;
  ```
- now open app.component.html and notice the error with the `{{ foo.name }}` binding
