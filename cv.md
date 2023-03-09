# Yuriy Kurenkov
**Fullstack web developer, Indie game developer**

---

## Contacts
* **Email**: [mr.kurenkov@gmail.com](mailto:mr.kurenkov@gmail.com)
* **Telegram**: [@nigel_riss](https://t.me/nigel_riss)
* **GitHub**: <https://github.com/nigel-riss>
* **LinkedIn**: <https://www.linkedin.com/in/mrkurenkov/>

---

## About
I am a frontend developer with a particular interest in interfaces and visualization. I have experience in web design and leading small developer teams. I try to keep up with best practices, and am always looking for new things to learn.

---

## Skills
### Languages, Frameworks & Libraries
* `HTML`, `CSS`, `JavaScript`*(ES5, ES6+)*, `ActionScript 3`*(ECMA 4)*, `Markdown`
* `React`, `Next.js`, `express`, `Node.js`
* `Sass`, `pug`
* `Wordpress`, `KeystoneJS`

### Tools & Technologies
* `Linux`
* `Webpack`, `gulp`, `Git`, `GitHub`
* `BEM`

### Other skills
* `Photoshop`, `figma`, `UX/UI`
* `Touch typing`
* `Project management`

### Limited experience 
* `PHP`, `Python`, `C`, `C++`, `Bash`, `Unreal Engine`, `Canvas`
* `Vue 3`

---

## Code example

### Task:
> * You get an array of arrays. 
> * If you sort the arrays by their length, you will see, that their length-values are consecutive. But one array is missing! 
> * You have to write a method, that return the length of the missing array. 
>Example:
> ```javascript
>[[1, 2], [4, 5, 1, 1], [1], [5, 6, 7, 8, 9]] --> 3
> ```
> * If the array of arrays is null/nil or empty, the method should return 0. 
> * When an array in the array is null or empty, the method should return 0 too! 
> * There will always be a missing element and its length will be always between the given arrays. 

### My solution:
```javascript
// This is arithmetical solution with O(n)
// Could be also done with sort + reduce but O(n log n)
const getLengthOfMissingArray = arrayOfArrays => {
  if (!arrayOfArrays?.length) return 0

  let [ maxLen, minLen, lenSum ] = [ 0, Number.MAX_VALUE, 0 ]

  for (el of arrayOfArrays) {
    if (!el?.length) return 0
    minLen = Math.min(el.length, minLen)
    maxLen = Math.max(el.length, maxLen)
    lenSum += el.length
  }

  minLen--
  const maxSum = maxLen * (maxLen + 1) / 2
  const minSum = minLen * (minLen + 1) / 2

  return maxSum - lenSum - minSum
}
```

---

## Experience

---

## Education

* 2001-2006 Baltic Fishing Fleet State Academy / Master of Computer Applications - MCA

### Courses
* 2015 HTML Academy / Basic HTML & CSS
* 2015 HTML Academy / Advanced HTML & CSS
* 2018 HTML Academy / Professional JavaScript, level 1
* 2020 HTML Academy / Professional JavaScript, level 2
* 2020 HTML Academy / React. Development of Complex Front-end Applications

### Courses in progress
* Udemy / JTS. Technical skills Senior Web Developers shoud know
* HTML Academy / Algorithms and data structures
* HTML Academy / Vue.js 3. Development of Complex Front-end Applications

## Languages
* **English** - Professional Working (B2)
* **Russian** - Native
* **Ukrainian** - Native / Professional Working
* **Spanish** - Elementary

