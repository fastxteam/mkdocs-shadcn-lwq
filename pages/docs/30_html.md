---
title: HTML
summary: Styled HTML elements
---

## Buttons

First, the theme styles `button`, `a.button` and `input[type="button"]` the same.
```html
<button>Button</button>
<a class="button" href="#">Link</a>
<input type="button" role="submit" value="Form action" />
```
<button>Button</button>
<a class="button" href="#">Link</a>
<input type="button" role="submit" value="Form action" />





Common shadcn styles can be provided throught the `class` attribute.

```html
<button>Default</button>
<button class="secondary">Secondary</button>
<button class="outline">Outline</button>
<button class="ghost">Ghost</button>
<button class="link">Link</button>
<button class="destructive">Destructive</button>
```
<button>Default</button>
<button class="secondary">Secondary</button>
<button class="outline">Outline</button>
<button class="ghost">Ghost</button>
<button class="link">Link</button>
<button class="destructive">Destructive</button>

The different sizes are also available

```html
<button class="outline xs">Extra Small</button>
<button class="outline sm">Small</button>
<button class="outline">Default</button>
<button class="outline lg">Large</button>
```
<button class="outline xs">Extra Small</button>
<button class="outline sm">Small</button>
<button class="outline">Default</button>
<button class="outline lg">Large</button>

Finally, the `icon` class can be used to have a squared aspect.
```html
<button class="icon xs">+heroicons:bolt-solid+</button>
<button class="outline icon sm">+heroicons:bolt-solid+</button>
<button class="ghost icon">+heroicons:bolt-solid+</button>
<button class="destructive icon lg">+heroicons:bolt-solid+</button>
```
<button class="icon xs">+heroicons:bolt-solid+</button>
<button class="outline icon sm">+heroicons:bolt-solid+</button>
<button class="ghost icon">+heroicons:bolt-solid+</button>
<button class="destructive icon lg">+heroicons:bolt-solid+</button>