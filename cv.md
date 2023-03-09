# Yuriy Kurenkov
**Web developer, Indie game developer**

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
* `VS Code`, `nano`
* `Touch typing`
* `Project management`

### Limited experience 
* `PHP`, `Python`, `C`, `C++`, `Bash`, `Unreal Engine`, `Canvas`
* `Vue 3`
* `Vim` *(Esc -> :q! ;)*

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

### Freelance Web Developer
*(April 2021 - present)* 

#### European House
* **Main project:** [ikea-39.ru](https://ikea-39.ru/)
* **Tasks:** development of a product catalog, integration with services; full stack: planning, frontend, backend, deploy.
* **Technologies:** React, Redux, Sass, pug, wordpress, nodejs, express, gulp, webpack, linux, ssh.

#### "ЭКСКО" - an independent expert organization
* **Main project:** [excopro.ru](https://excopro.ru/)
* **Tasks:** development of company websites and internal tools, consulting.
* **Technologies:** HTML, CSS, JavaScript, wordpress, React, Redux, SCSS, pug, gulp, webpack.

#### JAST Holding
* **Tasks:** development of sites and landing pages for company projects, development of company catalogs, consulting.
* **Technologies:** HTML, CSS, JavaScript, wordpress, React, SCSS, pug, gulp, webpack.


### JAST Holding / Web Developer, Team Lead
*(September 2019 — March 2021)* 
<!-- * **Main project:** -->
* **Tasks:** development of sites and landing pages for company projects, development of an internal CRM, coordinating the work of designers, copywriters and contractors.
* **Technologies:** HTML, CSS, JavaScript, wordpress, SCSS, pug, gulp, webpack
* **Planning:** Scrum, Kanban.


### OldBoy Barbershop Franchise / Web developer, CTO
*(November 2016 — August 2019)* 

* **Main project:** [oldboybarbershop.com](https://oldboybarbershop.com/)
* **Tasks:** development of websites and landing pages for company projects, development of internal company tools, coordinated the work of junior developers, designers, copywriters, marketers and contractors.
* **Achievements:** created a development department from scratch, under my leadership and direct participation (frontend) developed we launched the 3rd version of the franchise portal, which more than doubled the rates of online entries in franchise branches.
* **Technologies:** HTML, CSS, JavaScript, wordpress, SCSS, pug, gulp, webpack, PHP.
* **Planning:** Scrum, Kanban.


### Freelance Web developer
*(August 2015 — November 2016)*

* **Tasks:** development of wordpress sites with custom themes, development of landing pages
* **Technologies:** HTML, CSS, JavaScript, wordpress, SCSS, gulp, Photoshop
* **Planning:** Kanban
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

