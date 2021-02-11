# Aliaksandr Torkhau
### Contacts
- email: **torkhau@gmail.com**;
- skype: **torhoff-**;
- telegram: **@tor4koff**;
- discord: **Tor4koff#1281**.
### About me
I believe that a person develops only when he is not “sitting on the ground”, when he receives new knowledge, is learning something.
### Skills
- **HTML/CSS/JS**;
- **C#** (*basic knowledge*);
- **Python** (*basic knowledge*);
- Declared programming language **SQL** (*basic knowledge*);
- Technology platform **1С Предприятие**.
### Code examples
Task **Recursive depth calculator** from Basic-js
```
calculateDepth(arr) {
  if (arr.filter(elem => Array.isArray(elem)).length){
    return 1 + this.calculateDepth(arr.reduce((newArr, elem) => [...newArr, ...Array.isArray(elem) ? elem : [elem]], []))
  } else {
    return 1
  }
}
```

Task **Count cats!** from Basic-js
```
function countCats(matrix) {
  return matrix.map(elem => elem.filter(elem => elem==='^^')).reduce((summ, elem) => summ + elem.length, 0)
};
```
### Experience ;)
- Microsoft as a Bill;
- Tesla as a Ilon
### Education
Graduated from the Brest State A.S. Pushkin University with a degree in applied mathematics with qualification of a mathematician programmer.
### English level
Most of the tests on various sites pass on level A2