# latex-hoon

> **Archived.** This repository is no longer maintained. The Hoon `listings`
> definition lives on, with inline and block listing styles, in `ustj.sty` in the
> [USTJ Template](https://github.com/Urbit-Systems-Technical-Journal/USTJ-Template).
> Use that copy instead.

Hoon definition for the LaTeX `listings` syntax highlighter and code formatting package.

```sh
pdflatex example.tex
```

Known quirks:

- `listings` is fairly limited in terms of operator and string highlighting.
- Not all runes highlight properly, in particular the `!,` and `;,` runes which have commas in them.
- Partial matches adjacent to rune characters don't highlight, such as the `@` in `a=@`.
