# harp-url-dots
Metadata for jade files are not working in Harp. This is a repo to repro this issue.

You can run the code by doing
```
npm install
npm run harp
```

Then
* visit http://localhost:9000/ -> metadata is displayed
* visit http://localhost:9000/url.with.dots -> metadata is **not** displayed
