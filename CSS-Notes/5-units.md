# Absolute Units

1. cm = (1cm = 37.8px) = centimetre
2. mm = (1mm = 3.78px) = milimetre
3. inch = (1inch = 96px)
4. pt = (1inch = 72pt = 96px) = point
5. pc = (1pc = 12pt = 16px) = pica
6. px

Note: px is the most commonly used unit in CSS for screen design, while cm, mm, in, pt, and pc are mostly used for print.

# Relative Units

7. em = em multiplies hit parent
8. rem = rem just like em - follows HTML tag
9. vh = view height = 100vh
10. vw = view width = 100vw
11. % = relative his parent

# Understanding `em` and `rem` 

## `em`

The `em` unit in CSS is a relative unit that depends on the font size of the element’s parent. For example, if a parent element has a font size of `20px`, then `1em` inside its child will equal `20px`, and `2em` will equal `40px`. This unit can be used not only for font sizes but also for other properties like `width`, `height`, `padding`, `margin`, and more. However, if a child element defines its own font size (e.g., `20px`), then `1em` within that element will now equal `20px` instead of the parent’s value. That means the child element's `width` or `padding` set in `em` will now follow its **own font size**, not the parent's. If no font size is defined on any parent, `em` will ultimately rely on the default font size of the `html` element, which is typically `16px` in most browsers. So, everything with `em` is based on the current element’s font size, which may be inherited from the parent unless it’s overridden.

## `rem`

The `rem` unit, short for “root em,” is similar to `em` but with one important difference: it is always relative to the font size of the `html` (root) element, regardless of where it is used. This means that even if a child element has its own font size, `rem` values will still be calculated based on the root font size. For example, if the `html` element has a font size of `16px`, then `1rem` will always equal `16px`, and `2rem` will be `32px`, no matter what font size is set on any parent or child element. This makes `rem` a more stable and predictable unit for consistent scaling across an entire webpage, especially when building responsive layouts.


📌 **Key Difference**:  
`em` = parent-based, override font size from parent
`rem` = root (`html`) based, can not overroide - that's why it is stable and predictable