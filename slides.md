# JS Fundamental

## Chapter 1: Your first line of code

---

# Setup

## Common basic setup

- Nodejs
  https://nodejs.org/en/download/current
- VScode
  https://code.visualstudio.com/

---

# VSCode setup

- Prettier
  - https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
- JavaScript and TypeScript Nightly
  - https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next

---

# Running your first line of code

- After you finish installed everything, create a file name index.js
- Right click on the folder -> Open with code
- Copy and paste the below into the file

```js
// Your first line of code
console.log("Hello world!!");
```

- Go into vscode terminal section (or ctrl+\`)
- Type node ./index.js

```bash
> node ./index.js
Hello world!!
```

---

# Learning to use this interactive slide

You can see this example below have a play button

```js {monaco-run} {autorun: false}
console.log("Hello world!!");
```

---

# Explain the function

````md magic-move
```js
// This is what we called a function
// As you can see, a function is a word -> log
// And ended with () -> log()
console.log();
```

```js
// This is what we called a value
// The value here is String
// Easiest way to remember what is String: it's just words!!
"Hello world!!";
```

```ts
// When a value is put in the (), we call them parameters
// Parameters get send to the function
// We will learn more about it when the time come
console.log("Hello world!!");
```
````

---

# Exercise

```js {monaco-run} {autorun: false}
// Make an output like this when we run
// Hello, {your name} <- replace {your name} with your real name
// I love {animal} <- add an animal you like
// My birthday is {your birthday} <- add a birthday here
```

Send me the screenshot of your work!
