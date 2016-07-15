# goodmodule.com
JavaScript tips for everybody. (One new tip every day)

## Be a better web developer and follow
- [Github](https://github.com/seeden/goodmodule.com)
- [Instagram](https://www.instagram.com/goodmodule/)

## Content
  - [Javascript](#javascript)
    1. [Measuring Execution Times](#measuring-execution-time)

  - [ECMAScript 6](#es6)
    1. [Template Strings](#template-strings)
    2. [Destructuring Assignment](#destructuring-assignment)

## <a name="javascript"></a>JavaScript

### 1. <a name="measuring-execution-time"></a>Measuring Execution Times
```js
console.time('1000-iterations');

for( var i = 0; i < 1000; i++) {
  // your code
}

console.timeEnd('1000-iterations');
// Prints 1000-iterations: 25.438ms
```

Compatibility

| Chrome | Firefox | Internet Explorer | Opera | Safari | Node |
|--------|---------|-------------------|-------|--------|------|
| 2      | 10      | 11                | 9     | 4      | 0.1  |


## <a name="es6"></a>ECMAScript 6

### 1. <a name="template-strings"></a>Template Strings
```js
var first = 'Zlatko';
var last = 'Fedor';

// ECMAScript 5
var msg = 'Hi ' + first + ' ' + last;
msg === 'Hi Zlatko Fedor'; // true

// ECMAScript 6
var msg = `Hi ${first} ${last}`;
msg === 'Hi Zlatko Fedor'; // true
```

Compatibility

| Chrome | Firefox | Edge | Opera | Node | Babel  | Safari |
|--------|---------|------|-------|------|--------|-------|
| 41     | 34      | 12   | 28    | 4    | 5      | 9     |

### 2. <a name="destructuring-assignment"></a>Destructuring Assignment
```js
var user = {
  first: 'Zlatko',
  last: 'Fedor',
};

// ECMAScript 5
var first = user.first; // first === 'Zlatko'
var last = user.last; // last === 'Fedor'

// ECMAScript 6
var { first, last } = user;
first === 'Zlatko'; // true
last === 'Fedor'; // true
```

Compatibility

| Chrome | Firefox | Edge | Node | Babel | Safari |
|--------|---------|------|------|--------|-------|
| 49     | 2       | 14   | 6    | 5      | 7.1   |


## Be a better web developer and follow
- [Github](https://github.com/seeden/goodmodule.com)
- [Instagram](https://www.instagram.com/goodmodule/)
 
