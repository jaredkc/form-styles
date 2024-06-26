# Sensible Form Styles

Default form styles that are attractive, easy, and accessible.

- Name spaced to avoid conflicts and easy to override with search and replace
- Simple class names 
- Focus and active states
- "Field-stack" variation to have the label appear as placeholder text and transition when the input is focused or has content
- Optional validation styles without any JavaScript

## Example markup

Markup the form fields as desired. Both of these approaches will look the same.

Label wrapping the input:

```html
<label class="field-block">
  <span class="field-label">Input (text)*</span>
  <input type="text" id="text-1" class="field-input" />
  <small class="field-help">Add you description here</small>
</label>
```

Non-wrapping label:

```html
<div class="field-block">
  <label class="field-label" for="text-2">Input (text 2)*</label>
  <input type="text" id="text-2" class="field-input" />
  <small class="field-help">Add you description here</small>
</div>
```

---

## Credits

- [TailwindCSS](https://tailwindcss.com/) and [TailwindCSS Forms](https://github.com/tailwindlabs/tailwindcss-forms)
