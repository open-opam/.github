# AGENTS.md

The front page of open-opam's GitHub organisation: GitHub shows
`profile/README.md` of the public repository `open-opam/.github` on
`github.com/open-opam`. This file is for anyone changing it, human or
agent.

## Layout

```
profile/README.md    the page: the banner, the add command, the repositories, the catalogue
profile/banner.jpg   the banner, a 1200 by 630 screenshot of banner.html at twice its size
banner.html          the banner's source, in the catalogue's colours
```

A `CONTRIBUTING.md`, `SECURITY.md` or issue template at this repository's
root would become the default of every repository in the organisation that
has none of its own; there are none today.

## Rules that must hold

- **The page says what the catalogue says.** Its words are the catalogue's
  heading and lead, `Self-service opam repository. Open OCaml publishing
  for humans and agents.`, and nothing else is claimed. Why: a pitch told
  several ways is told wrong in all but one. Symptom: a sentence on the
  page that the catalogue does not carry.
- **A repository's row is its GitHub description, word for word.** Why:
  the description is what GitHub shows beside it everywhere else.
  Symptom: a row that differs from `gh repo view`'s description.
- **The banner is rendered from `banner.html`, never edited as an image.**
  Why: its text must stay the catalogue's, and only the source can be
  read and changed. Symptom: a `banner.jpg` that differs from a fresh
  screenshot of `banner.html`.
