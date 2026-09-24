# Credits

This map is an unofficial, personal project. It is not published by FOSS United or by
any of the organisations listed in it. Details are as shared by the people themselves.

## Open source tools used

| Tool | What it does here | Licence |
| --- | --- | --- |
| [D3.js](https://d3js.org/) 7.8.5 | Force-directed layout, zoom, pan and node dragging in the network view | [ISC](https://github.com/d3/d3/blob/main/LICENSE) |
| [quickselect](https://github.com/mourner/quickselect) | Bundled inside D3, used by its selection algorithms | ISC |

Full licence texts are in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md), as the ISC
licence requires.

D3 is vendored into this repository as `d3.min.js` rather than loaded from a CDN, so the
page works offline and makes no third-party requests.

## Everything else

No framework, no build step, no package manager, no analytics, no cookies. The whole
thing is one `index.html` file plus the D3 bundle. Colours, layout and interaction are
plain CSS and vanilla JavaScript. Typography uses the reader's own system font stack.

Hosted on [GitHub Pages](https://pages.github.com/).

## Assistance

Structure, styling and interaction code were written with the help of
[Claude](https://claude.ai) by Anthropic. The data, the people, the framing and every
editorial decision are mine.

## Licence

Code is [MIT](LICENSE). Directory content is
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

The directory describes real people who agreed to be listed for this gathering. A licence
governs copying, not privacy. If you are listed here and want your entry changed or
removed, open an issue or message me and I will do it.