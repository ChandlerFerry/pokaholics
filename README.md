# Pokaholics

Placeholder site for [pokaholics.net](https://pokaholics.net).

Support for TCG pack-opening compulsion - weeb aesthetic, recovery pitch.
Visitors enter by “opening” a free pack; the pull is the recovery message.
Refresh always resets to the sealed pack.

Original branding only - no franchise art, names, or product lookalikes.

## Instagram handle

Edit `index.html` and set:

```js
const INSTAGRAM_HANDLE = "yourhandle";
```

Leave empty until the account exists - the CTA stays disabled.

## Deploy

```bash
npx vercel --prod --scope chandlerferrys-projects
```
