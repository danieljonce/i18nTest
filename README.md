Example app showing error caused by package.js load order of velocity:html-reporter and tap:i18n.

#Working load order
```
tap:i18n
velocity:html-reporter
```

#Breaking load order
```
velocity:html-reporter
tap:i18n
```
