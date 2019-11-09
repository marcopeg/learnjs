# Javascript » Data » Remove items from an Array
[LearnJS](../../../ README.md) » [CodePen.io](../../README.md)

## 👉 User Story:

```
As a user
Given an Array that renders into an HTML list
When I click on a particular item
  That item should be removed from the array
```

The architecture of the "render" function from the previous
step should change into something like this:

1. clear existing DOM items
2. for each item in the array
  1. create the new item
  2. associate the event to handle the delete
  3. add the item to the list

You can try things out directly on this pen:  
https://codepen.io/marcopeg/pen/ExxROxe

---

## ✅ Proposed Solution:

> Don't run this unless you gave a very good effort to solve it yourself!

{% codepen id = "NWWzEqp", defaultTab = "js,result" %} {% endcodepen %}

An alternative solution:

{% codepen id = "ExxROKO", defaultTab = "js,result" %} {% endcodepen %}

And another:

{% codepen id = "ZEERmOo", defaultTab = "js,result" %} {% endcodepen %}


---

## 🤓 Resources:

- [MDN: Array.splice()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/splice)
- [MDN: Array.indexOf()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/indexOf)
- [MDN: Array.filter()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)

---
