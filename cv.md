# Denis Politsarnov
![Photo](https://i.ibb.co/RCCBBz6/Gray-Scale.jpg)
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
## Projects
Tools for MMO game “Eve online”:
https://eve-check.space/poly-react
Interactive diagram, visualization of production reactions chain
https://eve-check.space/moon-parser
Game text data parser. Parsed data is displayed in a convenient table.
Tool provides export to Google Sheets
(default example allows to evaluate the functionality without entering data)
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
## Employment history
<ins>  04.2016-current time:</ins> freelance, APCS design
<ins>12.2004-03.2016:</ins> Open Joint Stock Company «North West Power Engineering Center» ОАО «СевЗап НТЦ» ПЦ «Севзапэнергосетьпроект»
Started as an engineer of the 3rd category, grew to the head of the group (department of design of industrial control systems).
Design of automated process control systems, dispatching, telemechanics and  ASCME  for high-voltage electrical substations

## Education
2000-2006 гг: Saint Petersburg State University of Aerospace Instrumentation (SUAI). Engineer of “Automated Systems of Information Processing and Management” specialty