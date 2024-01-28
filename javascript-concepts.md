# JavaScript Notes

## Advanced JavaScript

### How importing and exporting a module work in JS ES6 ?

The main reason for using modules in any programming language is to just divide the code into smaller chunks or 'modules'. These modules can contain functionality. This is used extensively in frameworks like react. So, need to have a crystal clear understanding of these concepts if you want to go deep into react. I also started watching tutorials of react and then I realised that I need to understand "import" , "export" very clearly. It was not like I was not able to understand react tutorials but I felt a gap in my understanding, so here I am understanding these and making notes. 

I used this [video](https://www.youtube.com/watch?v=Py2fj9_BJXs&t=5) for understanding this. Seems to do the job in a short time.

#### export default function ?
![image](https://github.com/Rupanzil/study-notes/assets/153161192/b02f1d4d-92e8-4ac9-ba06-e32114d2b807)

Let's see what is exporting and importing module.

Modules should have extension .mjs

The first way is to do a default export. This can be done only when there is a single object in a module.
```js module1.mjs
// This module1.mjs
function square (num) {
  return num ** 2;
}

export default square; // This statement makes the function 'square' available outside the module1.mjs file
```
There are other ways to export as well such as named export. This is a named export of a function.
```js
export {square};
```
This is useful when there are multiple functions in a module and we want to export only a few functions

```js

```

#### main.js
```(JavaScript)
import 'fs' from fs
```

