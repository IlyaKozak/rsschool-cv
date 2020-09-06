# Ilya Kozak

_Minsk, Belarus  
+375 29 2578–508  
Email: [kozak@tut.by](mailto:kozak@tut.by)
LinkedIn: [linkedin.com/in/ilya-kozak](https://www.linkedin.com/in/ilya-kozak/)
GitHub: [github.com/IlyaKozak](https://github.com/IlyaKozak)
CodeWars: [codewars.com/users/IlyaKozak](https://www.codewars.com/users/IlyaKozak)_

## Summary

Web Developer (build is in progress :))

## Skills

◾◾◾◾◽ JavaScript
◾◾◾◾◽ HTML/CSS  
◾◾◾◽◽ SCSS, SASS, LESS  
◾◾◾◽◽ GIT
◾◾◾◾◽ Vusial Studio Code
◾◾◾◽◽ React
◾◾◽◽◽ Node.js
◾◾◽◽◽ Python

## Code samples

**JavaScript:**

```javascript
function yack(fn, ...args) {
  if (args.length >= fn.length) {
    return fn(...args);
  } else {
    return function (...addArgs) {
      return yack(fn, ...args, ...addArgs);
    };
  }
}
```
