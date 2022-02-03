<img src="src/assets/images/libredirect.svg" width="150" align="right" />
  
# LibRedirect
A web extension that redirects YouTube, Twitter, Instagram... requests to alternative privacy friendly frontends and backends.

- Youtube => [Invidious](https://github.com/iv-org/invidious), [FreeTube](https://github.com/FreeTubeApp/FreeTube)
- Twitter => [Nitter](https://github.com/zedeus/nitter)
- Instagram => [Bibliogram](https://sr.ht/~cadence/bibliogram/)
- Reddit => [Libreddit](https://github.com/spikecodes/libreddit#instances), [Teddit](https://codeberg.org/teddit/teddit#instances), [Old Reddit](https://old.reddit.com), [Mobile Reddit](https://i.reddit.com)
- Google Search => [SearX](https://searx.github.io/searx/), [Whoogle](https://benbusby.com/projects/whoogle-search/)
- Translate => [SimplyTranslate](https://git.sr.ht/~metalune/simplytranslate_web), [Lingva](https://github.com/TheDavidDelta/lingva-translate)
- Google Maps => [OpenStreetMap](https://www.openstreetmap.org/)
- Medium => [Scribe](https://sr.ht/~edwardloveall/scribe/)

**Note**: It will default to using random instances if none are selected. You can also set custom instances.

[![Matrix Badge](https://badges.alefvanoon.xyz/matrix/libredirect:matrix.org?label=Matrix)](https://matrix.to/#/#libredirect:tokhmi.xyz)
[![PrivacyPolicy](https://badges.alefvanoon.xyz/badge/-PrivacyPolicy-orange
)](Privacy-Policy.md)
## Get
[![Firefox Add-on](src/assets/images/badge-amo.png)](https://addons.mozilla.org/firefox/addon/libredirect/)

## Donate
**BTC:** `bc1qrhue0frps6p2vkg978u9ayethnwprtmfug827q`

## Development
### Install Dependencies
- [Node.js](https://nodejs.org/) >=10.0.0 installed
- `npm install`

### Build
- `npm run build`
- `open web-ext-artifacts/`

### Test
- `npm run test`

## Credits
- [privacy-redirect](https://github.com/SimonBrazell/privacy-redirect)
