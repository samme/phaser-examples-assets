Mirror of [phaser-examples/examples/assets](https://github.com/photonstorm/phaser-examples/tree/master/examples), minus audio, video, and a few source files.

You can use them via <https://cdn.jsdelivr.net/gh/samme/phaser-examples-assets@v2.0.0/assets/>, which is equivalent to <https://examples.phaser.io/assets/>.

The first load of a fresh asset may be slow.

```javascript
// @preload:
this.load.baseURL = 'https://cdn.jsdelivr.net/gh/samme/phaser-examples-assets@v2.0.0/assets/';
this.load.crossOrigin = 'anonymous';
this.load.image('dude', 'sprites/phaser-dude.png');
// etc.
```
