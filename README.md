# $BOKI

Nobody knows where BOKI came from. He just appeared on the internet one day.
BOKI was sent to Earth to study humanity. After three minutes, he gave up.

Static landing page + meme generator. No build step.

## Edit links / CA
Open `index.html` and edit the `CONFIG` block near the top of the `<script>`:

```js
const CONFIG = {
  CA: "COMING SOON",
  BUY_URL: "#buy",
  CHART_URL: "#",
  X_URL: "#",
  TG_URL: "#"
};
```

## Deploy
Hosted on Vercel as a static site (framework: Other, no build command, output = repo root).
