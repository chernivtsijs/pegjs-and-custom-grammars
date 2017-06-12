Tested on node 7.9.0
`npm i`
Running recursive descend
`node descend.js`
Running pegjs grammars - either copy to [online sandbox](https://pegjs.org/online) or run node_modules/.bin/pegjs (or add it to package.json's scripts section) and provide file you want to compile, then require it and invoke `parse` method.
For antlr4, follow [instructions](https://github.com/antlr/antlr4/blob/master/doc/javascript-target.md) on installation and run `antlr4 -Dlanguage=JavaScript -o s s.antlr4` (although it's not very intreseting as it's simplest grammar and I wasn't able to get parser to wowk with my version of Node).

