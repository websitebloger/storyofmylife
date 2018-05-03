Welcome to the
[Story Of My Life][1]
=====================


[![By: Samuel Betio](https://github.com/samuelbetio/storyofmylife/blob/code.svg/logo.svg)][1]
==================================================
Pixel-perfect   Retina-ready   Fast   Consistent   Hackable   No tracking


Update Version
==============
> A Shields.IO with full featured. Now your service just got the customizable badge code.svg.

|NAME Full Version              |[Index Version][2]|:tv: [README.md Version][3]| [LICENSE][4]|[RSS][5] Version|[Full Version][6]|
|-------------------------------|--------------------- |-----------------------|-------------|----------------|-----------------|
|Professional Bootstrap Template|[V0.0.0.3][7]         |[V0.4][8]              |[V0.0.1][9]  |[v01.80.836][10]|[v5.80836][11]   |
|Story Of My Life Full Version  |                      |                       |             |                |[v02.01.0001][12]|
|                               |                      |                       |             |                |                 |









JSONPath Syntax
===============
Here are syntax and examples adapted from [Stefan Goessner's original post][7] introducing JSONPath in 2007.

```js
|**JSONPath**|    **Description**     |
|------------|------------------------|
|$           |The root object/element |
|.	         |Child member operator   |
|..          |Recursive descendant operator; JSONPath borrows this syntax from E4X|
|*	         |Wildcard matching all objects/elements regardless their names|
|[]	         |Subscript operator      |
|[,]	       |Union operator for alternate names or array indices as a set|
|[start:end:step]|Array slice operator borrowed from ES4 / Python|
|?()	       |Applies a filter (script) expression via static evaluation|
|()	         |Script expression via static evaluation|
```

Given this sample data set, see example expressions below:
```js
{
  "store": {
    "book": [ 
      {
        "category": "reference",
        "author": "Nigel Rees",
        "title": "Sayings of the Century",
        "price": 8.95
      }, {
        "category": "fiction",
        "author": "Evelyn Waugh",
        "title": "Sword of Honour",
        "price": 12.99
      }, {
        "category": "fiction",
        "author": "Herman Melville",
        "title": "Moby Dick",
        "isbn": "0-553-21311-3",
        "price": 8.99
      }, {
         "category": "fiction",
        "author": "J. R. R. Tolkien",
        "title": "The Lord of the Rings",
        "isbn": "0-395-19395-8",
        "price": 22.99
      }
    ],
    "bicycle": {
      "color": "red",
      "price": 19.95
    }
  }
}
```

















[1]: https://samuelbetio.github.io/storyofmylife
[2]: #index-version
[3]: #readmemd-version
[4]: #license
[5]: #rss-version
[6]: #full-version
[7]: http://goessner.net/articles/JsonPath/
[8]: https://github.com/samuelbetio/storyofmylife/releases/tag/v0.4
[9]: https://github.com/samuelbetio/storyofmylife/releases/tag/v0.0.1
[10]: https://github.com/samuelbetio/storyofmylife/releases/tag/v01.80.3462.5836
[11]: https://github.com/samuelbetio/storyofmylife/releases/tag/v5.80.3462.5836
[12]: https://github.com/samuelbetio/storyofmylife/releases/tag/v02.04.0001.0001
[som-image]: https://github.com/samuelbetio/storyofmylife/blob/master/assets/img/logo.png
[som-url]: https://github.com/samuelbetio/storyofmylife/releases
