# flexstyl
###### simpler flex syntax
###### stylus simple-flex implementation

## installation
#### cdn - [flex.styl](https://npmcdn.com/flexstyl/flex.styl)
#### npm
```sh
npm i flexstyl # --save
```
## @import
```js
@import 'path_to_flex.styl'
// or
@import '../node_modules/flexstyl/flex'
// or
@import '~flexstyl/flex' // webpack

// just import flex.styl regardless whence
```

```styl
flex styl
// display: flex;

flex line
// display: inline-flex;

flex center
/*
  align-items: center;
  align-content: center;
  justify-content: center;
*/

flex wrap
// flex-wrap: wrap;

flex column
// flex-direction: column;

justify end
// justify-content: flex-end;

justify around
// justify-content: space-around;

align start
// align-items: flex-start;

self auto
// align-self: auto;

flex grow
// flex-grow: 1;

```

