# About This Project

This whole project is intended to have 50 mini projects and each is supposed to be completed in a day. Along with the projects, the notes for each project will be recorded in this document.

## Notes

### Expanding Cards

- JavaScript:
  You can grab the items with a certain class with `querySelectorAll` and it puts all the elements with that class in `node list`

```JavaScript
const panels = document.querySelectorAll(".panel");

console.log(panels);

```

and it consoles the following

```JavaScript

NodeList(5) [div.panel.active, div.panel, div.panel, div.panel, div.panel]
0: div.panel.active
1: div.panel
2: div.panel
3: div.panel
4: div.panel
length: 5
__proto__: NodeList

```

### Progress Steps

If you would like to use `before` pseudo class, you need to include content:

```css
.progress-container::before {
  content: "";
}
```

```css
.progress {
  transform: translateY(-50%);
}
```

You can target disabled attribute in css and style it

```css
.btn:disabled {
  background-color: var(--line-border-empty);
  cursor: not-allowed;
}
```
