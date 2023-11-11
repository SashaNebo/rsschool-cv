# Ilya Pribitkov
### Junior Frontend Developer
---
### Contact information:

Telegram: alexander_nebov

github: github.com/SashaNebo

E-mail: sasha1.nebo@gmail.com

Phone: +375 33 393-53-80

---
### Briefly About Myself:

The beginning of my first code was in the winter of 2021. Then my friend from the Internet started learning Python. Even earlier, I was thinking about programming, but I thought that only people with special knowledge could do this.

So I decided to start by myself. I immediately opened YouTube and started watching programming languages that are worth learning. So I chose html and css, because you can make money quickly. Later I realized that I would like more than just layout layout, and so I moved on to frontend development.

---

### Skills and Proficiency:
* HTML5, CSS3, SASS
* JavaScript ES6
* Yarn, Webpack Package manager
* React JS basic
* Adobe Photoshop, Figma

---

### Code example

__*6 kyu. _Find the odd int [Cata link](https://www.codewars.com/kata/54da5a58ea159efa38000836/train/javascript)*__

```
function findOdd(array) {
  let odd = null
  let obj = {}

  array.forEach(n => (obj[n] ? obj[n]++ : (obj[n] = 1)))
  Object.entries(obj).forEach(a => (a[1] % 2 !== 0 ? (odd = +a[0]) : 0))

  return odd
}
```
