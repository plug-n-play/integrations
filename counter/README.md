# ZEIT Addon: Counter

A simple counter implemented as a ZEIT UiHook.

## Run Locally

Install NPM dependencies with:

```
npm install
```

Then run this UiHook locally with:

```
now dev -p 5005
```

Then [create a ZEIT addon](https://zeit.co/docs/addons) and set the UiHook URI to: `http:///localhost:5005`

## Deploy to Production

Deploy this UiHook to production with:

```
now --target=production
```

Then use the alias of your deployment as the new UiHook URI of your addon.
