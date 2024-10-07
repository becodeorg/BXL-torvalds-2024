# CSS - Usefull tips

---

### Containers

Many ways of doing it. But trust me the simpler and most handy one is :

```css
.container {
  max-width: 1110px;
  padding: 0 10px;
  margin: 0 auto;
}
```

(The values here are arbitrary).

This container can be just a block, or you can make it a flex container (for navbars for example) or even a grid.

---

### Images

- Include on your reset :

```css
img {
  width: 100%;
}
```

The explanation is simple. An img will always try to be the actual size of the image file. By giving all images a width of 100%, you'll force them to adequate itself to its container parent. Now it's up to you to give the right measures to their container.

- Streched images :

Have you tried to set a width and a height to an image just to realize the image is streched ? Use this handy declaration :

```css
object-fit: cover; // or contain
```

Try for yourself !

---
