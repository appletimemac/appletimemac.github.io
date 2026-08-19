# appletimemac.github.io

GitHub Pages user site. Hosts:

- `/.well-known/apple-app-site-association`: universal-link association for Gryffindor (`9QH3QR8RS5.com.RRGS.Project77`). Served to devices via Apple's CDN; changes can take up to a day to propagate.
- `/pair/`: the invite fallback page. Pairing links carry the invite code in the URL fragment, so the code never reaches GitHub's servers; the page reads `location.hash` client-side to display it.
- `.nojekyll`: required so Pages serves the dot-prefixed `.well-known` directory.

The privacy policy lives in the separate `gryffindor-privacy` project-page repo.
