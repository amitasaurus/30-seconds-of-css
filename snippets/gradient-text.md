---
title: Gradient text
tags: visual,intermediate
---

Gives text a gradient color.

```html
<p class="gradient-text">Gradient text</p>
```

```css
.gradient-text {
  background: linear-gradient(#70D6FF, #00072D);
  -webkit-text-fill-color: transparent;
  -webkit-background-clip: text;
  font-size: 32px;
}
```

#### Explanation

- `background: -webkit-linear-gradient(...)` gives the text element a gradient background.
- `webkit-text-fill-color: transparent` fills the text with a transparent color.
- `webkit-background-clip: text` clips the background with the text, filling the text with the gradient background as the color.

#### Browser support

<span class="snippet__support-note">⚠️ Uses non-standard properties.</span>

- https://caniuse.com/#feat=text-stroke
