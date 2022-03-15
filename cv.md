# Svetlana Ivanova

### Contact information:

**E-mail:** isvetlanaivanova@yandex.com  
**Telegram:** @climbingirl  
**Discord:** @Svetlana Ivanova#9601  

---

### Briefly about myself:

I’m a 30-year-old beginner web developer. I have a law degree and experience in this field. Wanting to try a new comparison of activities, I started to self-learn programming in my off-hours. At one point, I realized that I was very interested in programming, and I decided to change my profession. Plus, my experience as a lawyer helps me with the technical development documentation. I like to improve my programming skills and I see in this field unlimited possibilities for developing myself as a professional.

---

### Skills:

* HTML5, BEM
* CSS3, SCSS
* JavaScript
* Git, GitHub
* Figma, Adobe Photoshop

---

### Code example:

***Codewars kata [Base Conversion](https://www.codewars.com/kata/526a569ca578d7e6e300034e):*** *In this kata I had to implement a base converter, which converts positive integers between arbitrary bases / alphabets.*

```
function convert(input, source, target) {
  const sourseSystem = source.length;
  const targetSystem = target.length;
  const indexSourceArr = [];
  
  for (const i of input) {
    indexSourceArr.push(source.indexOf(i));
  } 

  let decimal = 0;

  for (let index = 0; index < indexSourceArr.length; index++) {
    const el = indexSourceArr[index];
    const num = el * sourseSystem**(indexSourceArr.length - (index + 1));
    
    decimal += num;
  }

  const targetArr = [];
  let mod = decimal;

  while(mod >= targetSystem) {
    targetArr.unshift(mod % targetSystem);
    mod = (Math.trunc(mod / targetSystem));
  }

  if(mod < targetSystem) {
    targetArr.unshift(mod)
  }

  return targetArr.map(n => target[n]).join("");
}
```

---

### Experience:

* Training project landingpage [Portfolio](https://rolling-scopes-school.github.io/climbingirl-JSFEPRESCHOOL/portfolio/)
* Training project landingpage [Limpon](https://climbingirl.github.io/)

---

### Education:

**University:** Kutafin Moscow State Law University (MSAL)

**Courses:**
* [Course HTML for beginners](https://ru.code-basics.com/languages/html)
* [Course CSS for beginners](https://ru.code-basics.com/languages/css)
* [JavaScript Tutorial on learnjavascript.ru](https://learn.javascript.ru/) (in progress)
* [RS Schools Course «JavaScript/Front-end. Stage 0»](https://rs.school/js-stage0/)
* [RS Schools Course «JavaScript/Front-end»](https://rs.school/js/) (in progress)

---

### Languages:

* **Russian** - native speaker
* **English** - В1 (I took a foreign language course at Cambridge University. I practice English by communicating with friends from different countries)