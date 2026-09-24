# Credits

This map is an unofficial, personal project. It is not published by FOSS United or by
any of the organisations listed in it.

## Open source tools used

| Tool | What it does here | Licence |
| --- | --- | --- |
| [D3.js](https://d3js.org/) | Force-directed layout, zoom and pan for the network view | [ISC](https://github.com/d3/d3/blob/main/LICENSE) |
| [d3-force](https://github.com/d3/d3-force) | The physics simulation that positions the nodes | ISC |
| [d3-zoom](https://github.com/d3/d3-zoom) | Pinch-to-zoom and drag-to-pan, fenced to the canvas | ISC |
| [d3-drag](https://github.com/d3/d3-drag) | Dragging individual nodes | ISC |

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

Code in this repository is MIT licensed. The directory data describes real people and is
shared with their knowledge for the purposes of this gathering. Please do not scrape it
or reuse it elsewhere without asking.