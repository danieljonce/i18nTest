Example app showing error caused by package.js load order of `velocity:html-reporter@0.2.2` and `tap:i18n@1.0.4`.

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
