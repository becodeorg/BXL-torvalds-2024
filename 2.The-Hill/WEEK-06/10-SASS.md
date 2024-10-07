# SASS !!!!

---

**S**yntatically **A**wesome **S**tyle**S**heet

SASS is a CSS preprocessor.
What does that mean ?
It's some code we write that will then be processed by our machine to transform it to CSS. The browser doesn't read Sass files directly, but it will be converted.

Therefore:

- We write SASS
- The machine transforms it to CSS
- In our HTML we link it to the resulted CSS

---

The good news is : you can just write css inside a Sass file and it will work ! BUT... you can do much more with Sass than with CSS, and your code will be much more efficient with it.

Here is a list of some of the things we can do with Sass :

- **Variables**

Easily use variables inside of your css code :

```css
$main-color: red;
$text-color: white;

.a {
  color: $text-color;
  background-color: $main-color;
}
```

You can reuse this variable as much as you want. And if at one point you want to change the colors of all your website, just change it for the variable.

- **Indentation**

Instead of writing :

```css
.my-class {
  ...;
}

.my-class .nav {
  ...;
}

.my-class .nav ul {
  ...;
}

.my-class .nav ul li {
  ...;
}

.my-class .nav ul li a {
  ...;
}
```

You can just do :

```css
.my-class {
  ... .nav {
    ... ul {
      ... li {
        ... a {
          ...;
        }
      }
    }
  }
}
```

It's exactly the same thing !

---

- **Modules** (includes)

Instead of writing a huge css file (it can have thousands of lines for a big project), you can separate each section in different files and import them into the main sass file that will get converted to one huge css automatically.

- **Mixins** and **Functions**

Do you find yourself writing the same piece of code for several different classes ? Use a mixin : a piece of code that you'll just have to call to use it again.

Example :

I always use pseudo elements like ::before or ::after, and each time I put

```css
.my-class::after {
  content: "";
  display: "block";
  position: "absolute";
}
```

Instead of writing this every time I use a pseudo element, I create a mixin ("pseudo-mixin" for example) with this code and now, each time I use a pseudo element I just put :

```css
.my-class::after {
  @include pseudo-mixin;
}
```

I just saved 3 lines of code that I usually repeat again and again.
(mixins are much more powerful, it's a simple example)

- **Inheritance (extend)**

If a class have all the same properties of another one plus some others, we can extend a class. Example :

```css
.button {
  padding: 10px 20px;
  border-radius: 15px;
  text-transform: uppercase;
  text-align: center;
  display: inline-block;
  font-size: 14px;
  font-weight: 600;
}

.btn-alert {
  @extend .button;
  background-color: red;
  color: white;
}

.btn-success {
  @extend .button;
  background-color: green;
  color: white;
}

.btn-warning {
  @extend .button;
  background-color: orange;
  color: black;
}
```

I just created three different classes that are different but share the same base properties.

- **Operators**

Do Math inside of your CSS !

- **Conditions**

You can transform your CSS in a programming language ! Make conditions on which style will be applied depending on other parameters.

---

Here are some cherry picked video ressources to learn about Sass :

[Brad Traversy Crash Course](https://youtube.com/watch?v=nu5mdN2JIwM&si=i0nJsy_35ViJdQen) (English)
[Graphikart series](https://youtube.com/playlist?list=PLjwdMgw5TTLWVp8WUGheSrGnmEWIMk9H6&si=nS33wFHwfid54mR9) (French)
[École du web series](https://youtube.com/playlist?list=PLpG9MHuD988haohTMs9mJYXnwC115CEOe&si=b2ApJ58eUCYH10_v) (French)

If you'd rather read the doc, here is the [official website](https://sass-lang.com/guide/).

---

Learn the way you prefer, but you could follow along the Brad Traversy course and practice a little bit.

Strenght to you, young padawans !

![](https://media.giphy.com/media/26DN48mfu3uWJ3J7y/giphy-downsized.gif)
