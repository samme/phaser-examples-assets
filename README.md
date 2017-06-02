Mirror of [phaser-examples/examples/assets](https://github.com/photonstorm/phaser-examples/tree/master/examples/assets), minus audio, video, and a few source files.

You can use them via <https://cdn.jsdelivr.net/gh/samme/phaser-examples-assets@v1.0.0/>.

The first load of a fresh asset may be slow.

```javascript
// @preload:
this.load.baseURL = 'https://cdn.jsdelivr.net/gh/samme/phaser-examples-assets@v1.0.0/';
this.load.crossOrigin = 'anonymous';
this.load.image('dude', 'sprites/phaser-dude.png');
// etc.
```
