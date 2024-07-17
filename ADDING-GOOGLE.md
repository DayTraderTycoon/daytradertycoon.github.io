I’ve integrated google analytics with papermod theme by doing this:

In hugo_root/hugo.yaml

googleAnalytics: G-XXXXXXXXXX

In hugo_root/layout/partials/google_analytics.html, I put the script.

Then in ./themes/papermod/layouts/partials/head.htmlI’d put this

{{ partial "google_analytics.html" . }}

Next is to put google adsense 