# Pavel Bal

![Pavels avatar](./avatar255.jpg)

## Junior Front End Developer

---

### Contacts

* **Phone:** +375 44 477-70-07
* **E-mail:** balpoi000@gmail.com
* **Telegram:** [@balpoi](https://t.me/balpoi)
* **Discord RSS:** Pavel Bal (@balpoi)
* **[LinkedIn](https://www.linkedin.com/in/balpoi/)**
* **[Skype](https://join.skype.com/invite/CC3fiVvLcLeg)**

---

### About Me

I'm 20 years old, a third-year student, and have experience with the HTML/CSS/JS technology stack and a bit with others: SQL, C, Java, Python, etc.

Worked under short deadlines, tutored underachieving mates, and participated in the social life of the university.

Full of drive to learn new things and develop myself as a Front end developer.

---

### Skills and Proficiency

#### Programming languages

* JavaScript    (Intermediate)
* HTML5 & CSS3  (Intermediate)
* SQL           (Pre-intermediate)
* C             (Pre-intermediate)
* C#            (Basic)
* Java          (Basic)

#### Frameworks and Library

* Vue.js        (Basic)

#### DBMS

* MySQL Server  (Pre-intermediate)
* PostgreSQL    (Basic)

#### IDE

* VS Code           (Intermediate)
* WebStorm          (Pre-intermediate)
* IntelliJ IDEA     (Basic)
* Dev-C++           (Basic)

#### Tools and Abilities

* Git CLI, GitHub, BitBucket
* Command Prompt
* Vim
* Touch typing

#### OS

* Windows Family    (Intermediate)
* Linux             (Pre-intermediate)

---

### Code example

**["Human readable duration format"](https://www.codewars.com/kata/52742f58faf5485cae000b9a) KATA from CODEWARS:**
*The number of seconds is set. The function translates seconds into a human-readable string.
For example, seconds = 3662, the function returns "1 hour, 1 minute and 2 seconds".
If seconds is zero, just "now" is returned. Otherwise, the duration is expressed as a combination of years, days, hours, minutes and seconds.*

```javascript
function formatDuration (s) {
  if (s === 0) return "now";
  const sArr = [31536000, 86400, 3600, 60, 1];
  const words = ["year", "day", "hour", "minute", "second"];
  let resArr = [];
  for (const i in sArr) {
    let n = s / sArr[i] | 0;
    s -= n * sArr[i];
    if (n) resArr.push(`${n} ${words[i]}${n > 1 ? 's' : ''}`);
  }
  return resArr.join(", ").replace(/(, )(\d* \w*$)/, (match, p1, p2) => ` and ${p2}`);
}
```

---

### Work experience

* Small training project using Vue.js: [https://github.com/BalPoi/vue](https://github.com/BalPoi/vue)
* Small Cure landing page, made from a template: [https://github.com/BalPoi/pet-landing-page](https://github.com/BalPoi/pet-landing-page)

---

### Education

* JavaScript Manual on [learnjavascript.ru](https://learn.javascript.ru/) (in progress)
* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
* Francisk Skorina Gomel State University

---

### Languages

* English - Intermediate
* Russian - Native
