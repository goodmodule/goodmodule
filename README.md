# goodmodule
Be a better web developer. JavaScript tips for everybody. (One new tip every day)

## Be a better web developer and follow
- [www.goodmodule.com](http://www.goodmodule.com)
- [Github](https://github.com/seeden/goodmodule.com)
- [Instagram](https://www.instagram.com/goodmodule/)
- [Facebook](https://www.facebook.com/goodmodule/)

## Content
  
<img width="30" height="30" align="right" src="http://happykiwis.co.nz/public/goodmodule/logo-js.jpg"/>
### [JavaScript](#javascript) 
1. [Measuring Execution Times](#measuring-execution-time)
2. [Be careful with typeof](#typeof) (16 Jun 2016)

<img width="30" height="30" align="right" src="http://happykiwis.co.nz/public/goodmodule/logo-es6.png"/>
###[ECMAScript 6](#es6) 
1. [Template Strings](#template-strings)
2. [Destructuring Assignment](#destructuring-assignment)



## <a name="javascript"></a>JavaScript

<img width="30" height="30" align="right" src="http://happykiwis.co.nz/public/goodmodule/logo-js.jpg"/>
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



<img width="30" height="30" align="right" src="http://happykiwis.co.nz/public/goodmodule/logo-js.jpg"/>
### 2. <a name="typeof"></a>Be careful with typeof
```js
typeof null === 'object'; // true
typeof [1, 2] === 'object'; // true
typeof class C {} === 'function'; // true
typeof NaN === 'number'; // true
// NaN means "Not-A-Number"
```

Compatibility

| Chrome | Firefox | Internet Explorer | Opera | Safari | Node |
|--------|---------|-------------------|-------|--------|------|
| Yes    | Yes     | Yes               | Yes   | Yes    | Yes  |


## <a name="es6"></a>ECMAScript 6

<img width="30" height="30" align="right" src="http://happykiwis.co.nz/public/goodmodule/logo-es6.png"/>
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

<img width="30" height="30" align="right" src="http://happykiwis.co.nz/public/goodmodule/logo-es6.png"/>
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
- [www.goodmodule.com](http://www.goodmodule.com)
- [Github](https://github.com/seeden/goodmodule.com)
- [Instagram](https://www.instagram.com/goodmodule/)
- [Facebook](https://www.facebook.com/goodmodule/)
 
