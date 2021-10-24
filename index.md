---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# HSLA Images

### Introduction

Dans le cadre de notre projet nous nous sommes intéressés à la
manipulation IMAGES HSLA (HSLA :(Hue, saturation, luminance)).
A titre d’exemple le niveau de gris et illini de l’image …etc.

## HSL
>HSL is short for Hue, Saturation and Luminance.
>The HSL color space defines colors more naturally: Hue specifies the base color, the other two values then let you specify the saturation of that color and how bright the color should be.
### Hue
As you can see in the image, hue specifies the color. Hue is normally specified as either degrees ranging from 0° to 360° or as numbers from 0 to 6, in the image at the left side both starting at the 3 o'clock position and measured anti-clockwise.

There are 6 base colors:
| Hue           | Degree        |        Color |
| ------------- | ------------- | -------------|
| 0  | 0  | red|
| 1  | 60  |yellow |
| 2  |120  |green |
| 3 | 180  |cyan |           
| 4  | 240  |blue |
| 5  | 300  |magneta |
| 6  | 360 |red |

### Saturartion
After specifying the color using the hue value you can specify the saturation of your color. In the HSL color wheel the saturation specifies the distance from the middle of the wheel. So a saturation value of 0 (0%) means "center of the wheel", i.e. a grey value, whereas a saturation value of 1 (100%) means "at the border of the wheel", where the color is fully saturated.
<p align="center"> <img  src="http://www.chaospro.de/documentation/html/paletteeditor/images/huesat.jpg"> <br></p>

### Luminance

The third parameter in the HSL color space is the luminance. This lets you specify how "bright" the color should be. 0% means, the brightness is 0, and the color is black. 100% means maximum brightness, and the color is white.
If you slowly increase the luminance, you will see the color changing from black at 0% and then through a darker version of your color, to your color in its full brightness at 50%, and then getting brighter until finally it reaches white at 100%.

The following six luminance sliders show you what happens with colors if you change the luminance:
  <p align="center"> <img  src="https://user-images.githubusercontent.com/86808736/138558157-63b1da2c-40ee-4f0c-8c88-0725a4559812.png"> <br></p>



```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
