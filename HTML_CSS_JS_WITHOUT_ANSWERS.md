## HTML + CSS + JS

#### Q1. In HTML5, which tag or tags embed a webpage inside of a webpage?

**A)** `<iframe>, <frame>, and <frameset>`  
**B)** `<frame>`  
**C)** `<iframe>`  
**D)** `<frame> and <frameset>`  

<br>

#### Q2. With which tags is the `<source>` element associated?

**A)** `<svg>, <picture>, <audio>, and <video>`  
**B)** `<picture>, <audio>, and <video>`  
**C)** It is interchangeable with the `src` attribute, so any element which uses `src` may use `<source>`  
**D)** `<audio> and <video>`  

<br>

#### Q3. What is NOT a valid attribute for the `<textarea>` element?

**A)** readonly  
**B)** max  
**C)** form  
**D)** spellcheck  

<br>

#### Q4. When should you use `<ol>` and `<ul>` elements?

**A)** Use `<ul>` when you want a bulleted list and `<ol>` when you want a numbered list.  
**B)** Use `<ul>` when you have a list of items in which the order of the items matters. Use `<ol>` when you have a list of items that could go in any order.  
**C)** Use `<ol>` when you want a bulleted list and `<ul>` when you want a numbered list.  
**D)** Use `<ol>` when you have a list of items in which the order of the items matters. Use `<ul>` when you have a list of items that could go in any order.  

<br>

#### Q5. What is the difference between the `<div>` and `<span>` tags?

**A)** `<div>` is used where a generic block-level tag is needed, while `<span>` is used where a generic inline tag is needed.  
**B)** `<div>` is used for major divisions on a page, while `<span>` is used to span across columns.  
**C)** `<div>` is the industry-standard default tag, but you could use `<span>` if you prefer.  
**D)** `<div>` is used where a generic inline tag is needed, while `<span>` is used where a generic block-level tag is needed.  

<br>

#### Q6. What is the CSS selector for an `<a>` tag containing the title attribute?

**A)** `a[title]`  
**B)** `a > title`  
**C)** `a=title`  
**D)** `a.title`  

<br>

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

**A)**

```
  1. An element with an ID of "nav"
  2. A nav element
  3. An element with a class of "nav"
```

**B)** `They all target the same nav element.`  
**C)**

```
  1. An element with a class of "nav"
  2. A nav element
  3. An element with an id of "nav"
```

**D)**

```
  1. An element with a class of "nav"
  2. A nav element
  3. A div with an id of "nav"
```

<br>

#### Q8. When adding transparency styles, what is the difference between using the opacity property versus the background property with an `rgba()` value?

**A)** Opacity specifies the level of transparency of the child elements. Background with an `rgba()` value applies transparency to the background color only.  
**B)** Opacity applies transparency to the background color only. Background with an `rgba()` value specifies the level of transparency of an element, as a whole, including its content.  
**C)** Opacity specifies the level of transparency of an element, including its content. Background with an `rgba()` value applies transparency to the background color only.  
**D)** Opacity applies transparency to the parent and child elements. Background with an `rgba()` value specifies the level of transparency of the parent element only.  

<br>

#### Q9. What is the line-height property primarily used for?

**A)** to control the height of the space between two lines of content  
**B)** to control the height of the space between heading elements  
**C)** to control the height of the character size  
**D)** to control the width of the space between characters  

<br>

#### Q10. There are many properties that can be used to align elements and create page layouts such as float, position, flexbox and grid. Of these four properties, which one should be used to align a global navigation bar which stays fixed at the top of the page?

**A)** position  
**B)** flexbox  
**C)** grid  
**D)** float  

<br>

#### Q11. Which operator returns true if the two compared values are not equal?

**A)** `<>`  
**B)** `~`  
**C)** `==!`  
**D)** `!==`  

<br>

#### Q12. How is a forEach statement different from a for statement?

**A)** Only a for statement uses a callback function.  
**B)** A for statement is generic, but a forEach statement can be used only with an array.  
**C)** Only a forEach statement lets you specify your own iterator.  
**D)** A forEach statement is generic, but a for statement can be used only with an array.  

<br>

#### Q13. Review the code below. Which statement calls the addTax function and passes 50 as an argument?

```js
function addTax(total) {
    return total * 1.05;
}
```

**A)** `addTax = 50;`  
**B)** `return addTax 50;`  
**C)** `addTax(50);`  
**D)** `addTax 50;`  

<br>

#### Q14. Which statement is the correct way to create a variable called rate and assign it the value 100?

**A)** `let 100 = rate;`  
**B)** `100 = let rate;`  
**C)** `rate; = 100;`  
**D)** `let rate = 100;`  


<br>

#### Q15. When would 'Results shown' text be logged to the console?

```js
let modal = document.querySelector('#result');
setTimeout(function () {
    modal.classList.remove('hidden');
}, 10000);
console.log('Results shown');
```

**A)** after 10 second  
**B)** after results are received from the HTTP request  
**C)** after 10000 seconds  
**D)** immediately  