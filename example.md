---
title: Example
description: Example of a YAML Front Matter
template: howto-guide-template
redirect_from:
   - docs1
   - docs2 
---

# h1 Heading
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Paragraphs

### h3 Heading
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus consequat ante imperdiet lorem tempus convallis. Fusce bibendum, tortor eget egestas feugiat, elit massa fermentum neque, sed facilisis velit nisl quis leo. Suspendisse mattis nisi sit amet sapien aliquam, eu imperdiet nunc tempor. Maecenas dapibus nunc elit, sit amet lobortis odio lacinia vel. Morbi viverra lorem ac ultrices tincidunt. Donec mollis nisl augue, a tempus eros placerat non. Aenean in sagittis mauris. Vivamus rhoncus lacinia felis, id imperdiet nunc tincidunt sit amet. Nunc finibus justo vitae lorem ultrices, nec dapibus sapien commodo. Nulla ac porttitor velit, vitae tempus eros. Sed sed sem quis eros porta malesuada in quis massa. Phasellus eros urna, malesuada ac interdum eget, tristique hendrerit leo. Ut tristique nibh nunc, eget tempus orci ultrices eget.

#### h4 Heading
Integer congue ipsum vitae metus fringilla accumsan. Mauris sit amet mauris et magna imperdiet lacinia. Suspendisse mollis convallis mauris facilisis blandit. Nunc dapibus sem et lacus facilisis, a molestie nulla gravida. Curabitur at neque in orci laoreet consequat sit amet non lectus. Nullam fermentum nibh dui, ac commodo metus tristique ac. Proin hendrerit luctus enim, in malesuada metus varius sed. Donec consequat ipsum at eleifend tempus. Morbi vulputate augue neque, in vehicula est vehicula ac. Vestibulum maximus risus id elit egestas, ut dictum tortor tempus.


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"

Inline image ![Minion](https://octodex.github.com/images/minion.png) with longer text. And another inline image ![Minion](https://octodex.github.com/images/minion.png) 
