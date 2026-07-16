# The Biomimetic Architecture of Software 4.0 (Spec-Up-T)

Spec-Up-T specification and glossary converted from [arXiv:2606.04025v1](https://arxiv.org/abs/2606.04025).

## Source

- PDF: `source/2606.04025v1.pdf`
- Intermediate markdown: `source/2606.04025v1.md`

## Commands

```bash
npm install
npm run render   # build HTML into docs/
npm run edit     # watch mode
npm run menu     # Spec-Up-T interactive menu
```

## Structure

- `spec/spec-head.md` — title, authors, abstract
- `spec/terms-and-definitions-intro.md` — glossary intro
- `spec/terms-definitions/` — `[[def:]]` term files
- `spec/spec-body.md` — body with `[[ref:]]` links
- `specs.json` — Spec-Up-T configuration

See the [Spec-Up-T documentation](https://trustoverip.github.io/spec-up-t-website/).
