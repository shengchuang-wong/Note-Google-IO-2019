# Note-Google-IO-2019

## Table of Contents
- What's new on chrome or the web
- WebAssembly
- Javascript Feaatures

## What's new on chrome or the web
- Lazy loading
- Lighthouse budget
- Portals
- Perception toolkit

### Lazy Loading
<img width="1331" alt="Screenshot 2020-03-15 at 5 12 30 PM" src="https://user-images.githubusercontent.com/24192488/76698639-864b2300-66e0-11ea-8521-c1154489d019.png">

### Lighthouse budget
<img width="1350" alt="Screenshot 2020-03-15 at 5 15 58 PM" src="https://user-images.githubusercontent.com/24192488/76698654-a975d280-66e0-11ea-9c9f-bab1f2c4759e.png">

### Portals - web page transition
<img width="1356" alt="Screenshot 2020-03-15 at 5 16 56 PM" src="https://user-images.githubusercontent.com/24192488/76698667-c90cfb00-66e0-11ea-8719-418b20c097d2.png">

### Perception toolkit
<img width="1344" alt="Screenshot 2020-03-15 at 5 30 42 PM" src="https://user-images.githubusercontent.com/24192488/76698901-babfde80-66e2-11ea-9b3a-c33313ec351c.png">

## WebAssembly
- WebAssembly

## Javascript Features
- v8 engines is used in chrome, node.js, electron, and soon in microsoft edge
- Node.js v7 - Node.js v12 (Speed improve by x11)
- Class method (value instantiator and private value)
```js
class IncreasingCounter {
  _counter = 0
  #counter = 0 <<< private (mean it can't be direct access, but we can create a getter)
}
```
- string.matchAll
- 1_000 is equal to 1000, 1_000_000 = 1000000
