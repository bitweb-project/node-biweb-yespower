# node-biweb-yespower
Yespower + Yescrypt time switch node lib. Return block hash not reversed as is!

install

```
npm i bitweb-yespower
```

Test
```
var bitweb_yespower = require('bitweb-yespower');
var data = new Buffer.from("010000000000000000000000000000000000000000000000000000000000000000000000e0aac344bf218bbb5eee3d1d5ca00757a786598583781c60c55e8ff03033360474ce8e60ffff1f1f8b0200000101000000010000000000000000000000000000000000000000000000000000000000000000ffffffff2e04ffff001d010426626974776562332e30203d204254452d2d796573706f7765722d2d2d323032312f30352f3033ffffffff0100f2052a01000000434104678afdb0fe5548271967f1a67130b7105cd6a828e03909a67962e0ea1f61deb649f6bc3f4cef38c4f35504e51ec112de5c384df7ba0b8d578a4c702b6bf11d5fac00000000", "hex");


console.log(bitweb_yespower(data).toString('hex'));
```
