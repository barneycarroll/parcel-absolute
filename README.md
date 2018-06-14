# parcel-absolute

Can Parcel resolve absolute paths?

### Steps to reproduce
```
git clone git@github.com:barneycarroll/parcel-absolute.git
npm i && npm start
```

### Expected

[/src/index.js](https://github.com/barneycarroll/parcel-absolute/blob/master/src/index.js) is able to resolve [/src/app.js](https://github.com/barneycarroll/parcel-absolute/blob/master/src/app.js).

### Actual

```
🚨  ~/parcel-absolute/src/index.js:1:16: Cannot resolve dependency '/src/app/js' at '/src/app/js'
> 1 | import app from '/src/app.js'
```
