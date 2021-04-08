# latex-hoon

Hoon definition for the LaTeX listings package.

```sh
pdflatex example.tex
```

Known quirks:

- `listings` is fairly limited in terms of operator and string highlighting.
- Not all runes highlight properly, in particular the `!,` and `;,` runes which have commas in them.
