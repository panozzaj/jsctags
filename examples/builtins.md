```js
var x = Math.PI; //: number
Math.cos(x); //: number

var a = [1, 2, 3]; //: [number]
a.slice(2); //: [number]
a.pop(); //: number

["x"].concat(["hi"]); //: [string]

[true, false, true].filter(function(x){return x;}); //: [bool]

[].map(function() {return "x";}); //: [string]

[].reduce(function(a, b) { return a - 2; }, 0); //: number

Math.cos.call(null, 10); //: number

(10).toFixed; //: fn(digits: number) -> string

"foo bar baz".split(" "); //: [string]

toString; //: fn() -> string

new Date; //: Date

var num = new Number(1);
num; //: Number

"foo".toString(); //: string

Array.prototype.slice.call([1, 2, 3], 1); //: [number]

Array.prototype.slice.apply([1, 2, 3], [1]); //: [number]

String.prototype.indexOf.bind("abcde", "a"); //: fn(from?: number) -> number
```
```json
[
  {
    "name": "x",
    "addr": "/x/",
    "kind": "v",
    "type": "number",
    "lineno": 1
  },
  {
    "name": "a",
    "addr": "/a/",
    "kind": "v",
    "type": "[number]",
    "lineno": 4
  },
  {
    "name": "num",
    "addr": "/num/",
    "kind": "v",
    "type": "+Number",
    "lineno": 26
  }
]
```
```ctags
x		/x/;"	v	lineno:1	type:number

a		/a/;"	v	lineno:4	type:[number]

num		/num/;"	v	lineno:26	type:+Number
```
