## HTML + CSS + JS

#### Q1. In HTML5, which tag or tags embed a webpage inside of a webpage?

- [ ] `<iframe>, <frame>, and <frameset>`
- [ ] `<frame>`
- [x] `<iframe>`
- [ ] `<frame> and <frameset>`

#### Q2. With which tags is the `<source>` element associated?

- [ ] `<svg>, <picture>, <audio>, and <video>`
- [x] `<picture>, <audio>, and <video>`
- [ ] It is interchangeable with the `src` attribute, so any element which uses `src` may use `<source>`
- [ ] `<audio> and <video>`

#### Q3. What is NOT a valid attribute for the `<textarea>` element?

- [ ] readonly
- [x] max
- [ ] form
- [ ] spellcheck

#### Q4. When should you use `<ol>` and `<ul>` elements?

- [x] Use `<ul>` when you want a bulleted list and `<ol>` when you want a numbered list.
- [ ] Use `<ul>` when you have a list of items in which the order of the items matters. Use `<ol>` when you have a list of items that could go in any order.
- [ ] Use `<ol>` when you want a bulleted list and `<ul>` when you want a numbered list.
- [ ] Use `<ol>` when you have a list of items in which the order of the items matters. Use `<ul>` when you have a list of items that could go in any order.

#### Q5. What is the difference between the `<div>` and `<span>` tags?

- [x] `<div>` is used where a generic block-level tag is needed, while `<span>` is used where a generic inline tag is needed.
- [ ] `<div>` is used for major divisions on a page, while `<span>` is used to span across columns.
- [ ] `<div>` is the industry-standard default tag, but you could use `<span>` if you prefer.
- [ ] `<div>` is used where a generic inline tag is needed, while `<span>` is used where a generic block-level tag is needed.

#### Q6. What is the CSS selector for an `<a>` tag containing the title attribute?

- [x] `a[title]`
- [ ] `a > title`
- [ ] `a=title`
- [ ] `a.title`

#### Q7. What element(s) do the following selectors match to?

```css
1) .nav {
  ...;
}
2) nav {
  ...;
}
3) #nav {
  ...;
}
```

- [ ] A

```
  1. An element with an ID of "nav"
  2. A nav element
  3. An element with a class of "nav"
```

- [ ] B `They all target the same nav element.`
- [x] C

```
  1. An element with a class of "nav"
  2. A nav element
  3. An element with an id of "nav"
```

- [ ] D

```
  1. An element with a class of "nav"
  2. A nav element
  3. A div with an id of "nav"
```

#### Q8. When adding transparency styles, what is the difference between using the opacity property versus the background property with an `rgba()` value?

- [ ] Opacity specifies the level of transparency of the child elements. Background with an `rgba()` value applies transparency to the background color only.
- [ ] Opacity applies transparency to the background color only. Background with an `rgba()` value specifies the level of transparency of an element, as a whole, including its content.
- [x] Opacity specifies the level of transparency of an element, including its content. Background with an `rgba()` value applies transparency to the background color only.
- [ ] Opacity applies transparency to the parent and child elements. Background with an `rgba()` value specifies the level of transparency of the parent element only.

#### Q9. What is the line-height property primarily used for?

- [x] to control the height of the space between two lines of content
- [ ] to control the height of the space between heading elements
- [ ] to control the height of the character size
- [ ] to control the width of the space between characters

#### Q10. There are many properties that can be used to align elements and create page layouts such as float, position, flexbox and grid. Of these four properties, which one should be used to align a global navigation bar which stays fixed at the top of the page?

- [x] position
- [ ] flexbox
- [ ] grid
- [ ] float

#### Q11. Which operator returns true if the two compared values are not equal?

- [ ] `<>`
- [ ] `~`
- [ ] `==!`
- [x] `!==`

#### Q12. How is a forEach statement different from a for statement?

- [ ] Only a for statement uses a callback function.
- [x] A for statement is generic, but a forEach statement can be used only with an array.
- [ ] Only a forEach statement lets you specify your own iterator.
- [ ] A forEach statement is generic, but a for statement can be used only with an array.

#### Q13. Review the code below. Which statement calls the addTax function and passes 50 as an argument?

```js
function addTax(total) {
  return total * 1.05;
}
```

- [ ] `addTax = 50;`
- [ ] `return addTax 50;`
- [x] `addTax(50);`
- [ ] `addTax 50;`

#### Q14. Which statement is the correct way to create a variable called rate and assign it the value 100?

- [ ] `let 100 = rate;`
- [ ] `100 = let rate;`
- [ ] `rate; = 100;`
- [x] `let rate = 100;`

#### Q15. When would 'Results shown' text be logged to the console?

```js
let modal = document.querySelector('#result');
setTimeout(function () {
  modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

- [ ] after 10 second
- [ ] after results are received from the HTTP request
- [ ] after 10000 seconds
- [x] immediately