# Denis Politsarnov
## Junior Fronend Developer
## Contact info:
**Phone:** +7 (905) 274-75-55
**E-mail:** todayz@yandex.ru
**LinkedIn:** https://www.linkedin.com/in/denpolitsarnov/
**GitHub:** https://github.com/Gibr
## Skills
 - Front-End:  **React** + **Redux**, **HTML, CSS**, **adaptive layout**
- Back-End: **Node.js** + **Express**
- DB: **MongoDB**
- Misc.: **Git,** **npm/yarn**
## Code example
_Given a list of integers and a single sum value, return the first two values (parse from the left please) in order of appearance that add up to form the sum._
```javascript
var sum_pairs=function(ints, s){
  let hash = {};
  for (let i = 0; i < ints.length; i++) {
    let add = s - ints[i];
    if (hash[add] >= 0) {
      return [add, ints[i]];
    }
    if (!hash[ints[i]]) {
      hash[ints[i]] = i;
    }
  }
}
```