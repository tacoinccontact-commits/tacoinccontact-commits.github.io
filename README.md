# tacoinccontact-commits.github.io

The Taco Inc publisher site: privacy policies, terms and `app-ads.txt`.

Google Play requires a live privacy policy URL before a listing can be
completed, and AdMob reads `app-ads.txt` from the root of the developer
website declared in the store listing.

| File | URL once Pages is on | Used by |
|---|---|---|
| `index.html` | `https://tacoinccontact-commits.github.io/` | Play "Developer website" |
| `evenfall-privacy.html` | `.../evenfall-privacy.html` | Play listing, Data Safety |
| `daysworth-privacy.html` | `.../daysworth-privacy.html` | Play listing, Data Safety |
| `terms.html` | `.../terms.html` | Linked from the listings |
| `app-ads.txt` | `.../app-ads.txt` | AdMob, to prove the apps are ours |

To publish: Settings → Pages → Source: deploy from branch `main`, folder `/`.
The repository must be named exactly `tacoinccontact-commits.github.io` and be
public, or the URLs above will not exist.

`app-ads.txt` holds the AdMob publisher ID (pub-1585731276611281). Confirm the
exact line against the one AdMob shows under Apps → app-ads.txt before relying
on it; AdMob will report the file as "not found" until the app is published and
the developer website is set in the Play listing.
