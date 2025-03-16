# markdown tutorial
## basics
Markdown is a text based format, based on html. it's often used for quickly documenting and widely used in github.
you can freely use both html and markdown sytnax.
for example to show bold text you may use either `**` between the text you want to show as bold, or use `<b>` tag.

### Italic and bold text
Italic text is made either *using stars* (`*like this*`), or _using underscores_ (`_like this_`).
likewise, bold text is made with **TWO stars**, or __TWO underscores__.

### Monospace text
#### Inline
Inline monospacing can be done using `backticks`.

#### paragraph
You can make monospaced paragraphs using three backsticks, like:
```
#include <stdio.h>

int
main(void){
	printf("hello\n");
	return 0;
}
```

### Lists
#### unordered lists
That can be done like folllowing:
```
* apple
* banana
* carrot
```
* apple
* banana
* carrot

#### ordered list
An ordered list is done by just numbering them:
```
1. apple
2. banana
3. carrot
```

1. apple
2. banana
3. carrot

### Links
To link a text `[text](link)`, the text between brackets will be linked, [like this!](https://github.com/)

### Inline images
inline images are like links, but with a `!` in front of them
![git logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)
First the alt text, then the link.
please always include the alt text, it's very useful for visually impared pepole.

