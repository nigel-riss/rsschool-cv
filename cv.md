# Yuriy Kurenkov

## Contacts
* **Email**: [mr.kurenkov@gmail.com](mailto:mr.kurenkov@gmail.com)
* **Telegram**: [@nigel_riss](https://t.me/nigel_riss)
* **GitHub**: <https://github.com/nigel-riss>
* **LinkedIn**: <https://www.linkedin.com/in/mrkurenkov/>

## About

## Skills

## Code example
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

## Experience

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

