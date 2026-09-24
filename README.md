# Education at IndiaFOSS

A directory and network map of people running open source in education initiatives in
India, built for an invite-only gathering at IndiaFOSS 2026.

**Live:** https://siddharth2798.github.io/education-map/

Each person has a profile with their role, organisation and links. Each connection
between two people is a suggested conversation: something specific they could talk
about when they meet. Two views, Directory and Network, over the same data.

This is an unofficial, personal project. It is not published by FOSS United or by any of
the organisations listed in it.

## Running it

No build step. Clone and open `index.html`, or serve the folder:

```bash
python3 -m http.server
```

Deployed via GitHub Pages from the `main` branch, root folder.

## Editing the data

Everything lives in two arrays near the top of the `<script>` block in `index.html`.

`P` is the people. One object each:

```js
{id:"Name", role:"Title", org:"Organisation", li:"linkedin url", web:"project url"}
```

`E` is the connections. One array each, as `[person A, person B, theme key, note]`:

```js
["Name A","Name B","tooling","What the two of them could talk about."]
```

Both names must match an `id` in `P` exactly. The theme key must exist in `THEMES`,
which sets the label and colour. The note accepts inline HTML, so links work.

Everything else derives from these: node sizes, connection counts, theme dots, the
search index and the gaps report.

## Linking to a person

Append their slug, which is their name lowercased with non-alphanumerics hyphenated:

```
.../education-map/#person-A
```

`#directory` and `#network` open a tab with nobody selected.

## Licence

Code is [MIT](LICENSE). Directory content is
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Bundled dependencies keep
their own licences, listed in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md). Tools
used are in [CREDITS.md](CREDITS.md).

If you are listed here and want your entry changed or removed, open an issue or message
me and I will do it.