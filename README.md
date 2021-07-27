Better Cue Parser
=======

Based on [justlaputa/cue-parser](https://github.com/justlaputa/cue-parser), add some enhancements to make cue parser better, in browser and node.

## Original

cue-parser is a cue-sheet parser library written for nodejs.

Most of the code is inspired by [cue-go](https://github.com/vchimishuk/cue-go)

How to use
=======
Add cue-parser as a dependency to your project using npm:

```shell
npm install better-cue-parser
```

or yarn:

```shell
yarn add better-cue-parser
```

Use it in your node source code

```javascript
const parser = require('better-cue-parser');

const cuesheet = parser.parse(data, encoding);

console.log(cuesheet.performer);
console.log(cuesheet.files);
console.log(cuesheet.files[0].tracks);
```

References
==========

- [Cue sheet format kodi.wiki](http://kodi.wiki/view/Cue_sheets)
- [Cue sheet format from wiki.hydrogenaud.io](http://wiki.hydrogenaud.io/index.php?title=Cue_sheet)
