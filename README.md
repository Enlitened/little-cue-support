# Little Cues — site, support and privacy

The public pages for Little Cues, a baby feed, sleep and nappy log for iPhone and Apple Watch. Published with
GitHub Pages from `main`.

- Landing page — <https://enlitened.github.io/little-cue-support/> (the App Store listing's Marketing URL)
- Support — <https://enlitened.github.io/little-cue-support/support.html>
- Privacy policy — <https://enlitened.github.io/little-cue-support/privacy.html>

All three URLs are the ones filed in App Store Connect. The source of truth for the text is the app repository:
`docs/privacy-policy.md`, `metadata/support.md` and `metadata/en-AU/description.txt`; edit there first, then bring
the change across. Once the listing is live, replace the "Coming to the App Store" span in `index.html` with the
store link.

`assets/` holds the icon, the social card and two captioned screenshots, resized from the app repository's
`build/store-screenshots/6.9/` (made by `tools/CaptionScreenshots.py`).

Contact: csergay@gmail.com
