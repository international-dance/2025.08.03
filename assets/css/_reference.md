# CSS REFERENCE

> “I soon learned to scent out what was able to lead to fundamentals and to turn aside from everything else, from the multitude of things that clutter up the mind.”. <br>
> ~ Albert Einstein<br>
> [Sifting the Essential from the Non-Essential](https://fs.blog/albert-einstein-simplicity/)


## Logical Properties
DESCRIPTION:<br>
Logical properties and values control layout through logical rather than physical direction and dimension mappings.<br>

PURPOSE:<br>
Logical properties define direction-relative equivalents to their corresponding physical properties.

USE-CASE: <br>
Different writing systems operate in various directions. For example:

- English and Portuguese are written from left to right with new lines added below the previous ones.
- Hebrew and Arabic are right-to-left languages with new lines again being added below the previous ones.
- In some writing modes, the text lines are vertical, written from top to bottom. Chinese, Vietnamese, Korean, and Japanese are traditionally written vertically, from top to bottom, with each new vertical line added to the left of the previous one.
- Traditional Mongolian is also a top-to-bottom language, but new lines are to the right of previous ones.

Properties that once only accepted physical values (`top`, `bottom`, `left`, `right`) now also accept flow-relative logical values (`block-start`, `block-end`, `inline-start`, `inline-end`).

MDN:<br>
[CSS logical properties and values](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_logical_properties_and_values)

CODE EXAMPLE:

```

```
