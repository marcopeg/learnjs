# Javascript » The Chat Input
[LearnJS](../../../ README.md) » [CodePen.io](../README.md)

## 👉 User Story:

```
As a user
Given a text input element
  And a "post" button
When clicking on the button
  If the input is empty
    Then alert an error message
  Else
    Alert the input text
    Then clear the input element
    And keep focus on the input element
```

You can try things out directly on this pen:  
https://codepen.io/marcopeg/pen/PoYyZJY

> **NOTE:** In this exercise you need to put together all the concepts that you
> have learned so far. 

This is not an easy exercise and it will probably give you a decent challenge.  
**But you can do it**, and in the end you will have build a fundamental UI component!

---

## ✅ Proposed Solution:

> Don't run this unless you gave a very good effort to solve it yourself!

{% codepen id = "wvwYMxM", defaultTab = "js,result" %} {% endcodepen %}

In this second solution, we leverage on _functions_ to split the codebase
into smaller and simpler blocks, then we glue pieces together to build the main logic.

{% codepen id = "yLBROZG", defaultTab = "js,result" %} {% endcodepen %}

In this third solution, we keep building on features. This time we want
the "POST" button to be visible only if the message can be sent.

Messing up with different UI states (how it looks) based on some kind of
logic are very common features. Just think of the "b" and "i" buttons in
a classic word processor. They change constantly based on the cursor's
position.

{% codepen id = "BaBqzjx", defaultTab = "js,result" %} {% endcodepen %}

---

## 🤓 Resources:

- [MDN: CSS Attribute Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors)
- [MDN: CSS Selectors Specificity](https://developer.mozilla.org/en-US/docs/Web/CSS/Specificity)
- [What is a pure function?](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)
- [MDN: preventDefault](https://developer.mozilla.org/en-US/docs/Web/API/Event/preventDefault)
- [MDN: stopPropagation](https://developer.mozilla.org/en-US/docs/Web/API/Event/stopPropagation)

---
