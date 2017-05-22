# simple pie samples  

Some samples of running a pie item, One just a pie by itself and one using the `pie-player`.

## dependencies 

`pie@7.4.0-prerelease`

## install 

```bash
pie pack --addPlayerAndControlPanel
```

## pie-only.html 

```bash
npm install -g node-static 
static . # go to http://localhost:8080/pie-only.html
```

## pie-with-player.html

For this we need to build a bundle for the browser. This build is in `controller-build`.

```bash
cd controller-build
npm install 
npm run build
cd ..
static . # go to http://localhost:8080/pie-with-player.html
```
