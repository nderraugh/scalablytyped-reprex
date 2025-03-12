## Reprex

```
npm install -D @types/chart.js@2.9.29 typescript@4.9.5
npm install -S chart.js@2.9.4
echo "0.12.8" >> .mill-version
mill app.compile
```

## Repo for https://github.com/lolgab/mill-scalablytyped/issues/38