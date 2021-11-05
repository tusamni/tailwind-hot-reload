# Tailwind CSS and BrowserSync

I needed a simple way of quickly spooling up a hot reloading server that had Tailwind installed and running from the get-go. This is as simple as it gets. Place any HTML in the /src folder and it'll be picked up by BrowserSync.

To get started, run:

```
npm run watch
```

Then visit:
```
http://localhost:3000/
```

If you need to add any styles, either add the Tailwind classes inline, or add them to the /src/css/tailwind.css file.
