# Basic: Dazzle

::: sandboxrun

```html
<button class="dazzle">
  Dazzle Background
</button>
```

```css
.dazzle {
  position: relative;
  padding: 8px;
  font-size: 20px;
  color: #ffffff;
  cursor: pointer;
  border: none;
  border-radius: 8px;
  background: #2a80eb;
  background-image:
    radial-gradient(farthest-side at bottom left, rgba(255, 0, 255, .5), transparent),
    radial-gradient(farthest-side at bottom right, rgba(255, 255,50,.5), transparent);
}
```

:::
