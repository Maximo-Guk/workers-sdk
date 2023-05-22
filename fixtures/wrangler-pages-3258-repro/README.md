# wrangler performance issues repro

1. run the dev server
  - `npm install`
  - `npm run wrangler`

2. edit `public/_worker.js` (for example, add a space to the end of the file)

3. each time you do this, you should see `Compiled Worker successfully` printed one more time than the previous run, and idle CPU usage increasing progressively.
