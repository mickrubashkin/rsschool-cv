![Mick's avatar picture](https://gravatar.com/avatar/446a0b352935de1566ed9a1d40e271f49a84268cfbc0546e53a1d0ccc06edbd6)

# Mick Rubashkin

### Frontend Developer

---

### Contact Details:

**E-mail**: mikhail.rubashkin@gmail.com  
**Discord, telegram**: @mick_rubashkin  
**Github**: [mickrubashkin](https://github.com/mickrubashkin)

---

### Summary

TBD  
Brief Self-Introduction (your goals and priorities, emphasize your strengths, describe your work experience if applicable, or your desire to learn and acquire new skills)

---

### Skills:

- HTML5, CSS3
- JavaScript
- React, Vue
- Node.js

---

### Code Examples

ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher.

Create a function that takes a string and returns the string ciphered with Rot13. If there are numbers or special characters included in the string, they should be returned as they are. Only letters from the latin/english alphabet should be shifted, like in the original Rot13 "implementation".

```javascript
const alpha = 'abcdefghijklmnopqrstuvwxyz'
const ALPHA = alpha.toUpperCase()

function rot13(message) {
  return message
    .split('')
    .map((ch) => {
      if (alpha.includes(ch)) return alpha.at(alpha.indexOf(ch) - 13)
      if (ALPHA.includes(ch)) return ALPHA.at(ALPHA.indexOf(ch) - 13)
      return ch
    })
    .join('')
}
```

---

### Work Experience

- Vue Map ([Live demo](https://melodious-boba-c1b546.netlify.app/), [GitHub](https://github.com/mickrubashkin/vue-map)). Online map playground. Built with `Vue 3` & `OpenLayers`.
- Vue Note app ([Live demo](https://dashing-chimera-bebf95.netlify.app/#/), [GitHub](https://github.com/mickrubashkin/vue-noteapp)). Notetaking app, built with `Vue 3`.
- Gendiff ([View on GitHub](https://github.com/mickrubashkin/frontend-project-lvl2)). CLI tool to compare `json` or `yaml` files, print diff to the console in different formats.
- Brain Games ([View on GitHub](https://github.com/mickrubashkin/frontend-project-lvl1)). CLI games collection.

---

### Education

[JavaScript.Ninja](https://www.youtube.com/playlist?list=PLvTBThJr861yMBhpKafII3HZLAYujuNWw), Vue.js course  
[Hexlet.io](https://hexlet.io/programs/frontend), Frontend Developer  
[SICP](https://github.com/mickrubashkin/hexlet-sicp-racket), self-paced practice on SICP book  
[CS50](https://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA), Harvard University's introduction to the intellectual enterprises of computer science and the art of programming

---

### English Language:

C1 Advanced
