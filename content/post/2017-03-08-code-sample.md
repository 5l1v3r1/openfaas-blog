---
title: Code Sample
subtitle: Using Hugo or Pygments
date: 2017-03-08
image: "https://cdn.pixabay.com/photo/2017/12/31/14/44/rope-3052477_960_720.jpg"
image: "https://images.unsplash.com/photo-1512248805576-c1b31f6fcab1?dpr=1&auto=format&fit=crop&w=1000&q=80&cs=tinysrgb"
author: "Will Hall"
authorbio: "Open Source tinkerer. Digital Architect - whatever that means."
authorlocation: "Cambridge, UK"
authorwebsite: "https://www.willhallonline.co.uk"
tags: ["example", "code"]
---

The following are two code samples using syntax highlighting.

<!--more-->

The following is a code sample using triple backticks ( ``` ) code fencing provided in Hugo. This is client side highlighting and does not require any special installation.

```javascript
    var num1, num2, sum
    num1 = prompt("Enter first number")
    num2 = prompt("Enter second number")
    sum = parseInt(num1) + parseInt(num2) // "+" means "add"
    alert("Sum = " + sum)  // "+" means combine into a string
```


The following is a code sample using the "highlight" shortcode provided in Hugo. This is server side highlighting and requires Python and Pygments to be installed.

{{< highlight javascript >}}
    var num1, num2, sum
    num1 = prompt("Enter first number")
    num2 = prompt("Enter second number")
    sum = parseInt(num1) + parseInt(num2) // "+" means "add"
    alert("Sum = " + sum)  // "+" means combine into a string
{{</ highlight >}}


And here is the same code with line numbers:

{{< highlight javascript "linenos=inline">}}
    var num1, num2, sum
    num1 = prompt("Enter first number")
    num2 = prompt("Enter second number")
    sum = parseInt(num1) + parseInt(num2) // "+" means "add"
    alert("Sum = " + sum)  // "+" means combine into a string
{{</ highlight >}}
