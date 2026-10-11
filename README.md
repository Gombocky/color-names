# Color Names: what Wikipedia and Wiktionary say about each name

One file per color name, `names/<first letter>/<slug>.json`:

```json
{ "name": "Red-Handed", "hex": "#dd2233", "fetched": "2026-10-11",
  "looked": { "definitions": [], "entries": [], "images": [], "sounds": {} } }
```

Copied by `website/scripts/collect.mjs` on the `project-website` branch, and
renewed a few names a night so each is about six months old at most. Read by
the website's build, so its color pages don't ask Wikimedia on every view.

Requests follow Wikimedia's rate limits, API etiquette and User-Agent policy.
Images are not copied, only their addresses.

Text from Wikipedia and Wiktionary is available under the
[Creative Commons Attribution-ShareAlike 4.0 License](https://creativecommons.org/licenses/by-sa/4.0/);
each entry keeps the link to the page it comes from.
