# Block, Element, Modifier - BEM CSS
It is a kind of methodology that is used to maintain writing CSS in our code. BEM is a naming 'syntax' for class-name in our CSS. This methodology is useful to manage a large and complex project, and also can be applied in a small project which makes the project easy to maintain.
### Historical
Began in 2005 from Yandex as their first project was to make a static HTML, they splitted up their HTML file in a separate file like the following structure:
```
about.html
index.html
...
project.css
project.js
i/
    yandex.png
```
In the following year (2006) they started a first large project with dozens of pages and made them to create a set of rules. Adding prefixes to a large independent page element and called them as 'blocks'. Moreover, they also start to called inner nodes of block as 'block-elements' or 'elements' with these following key difference between block:

- Element can not exist outside block
- Element can not detached from the block
- Detaching elements become blocks.

The addition of block modifications came later in 2007. They realized that while using blocks, it is possible to put several states in a block. For example in a block called button, they can use these states: `Small`; `Normal`; and `Large`. After a long journey, they refined their project structure and become nowadays BEM which is adaptive and applicable in diverse projects.

### Naming Pattern
In general, there are 3 parts of naming system: Body, Element, and Modifier. You can see the details here:

| Naming Rules    | Definition        | Example           | Customized-example |
| --------------- | ----------------- | ----------------- | ------------------ |
| Block           | The root of component which is standalone and meaningful on its own.   | .car | .car |
| Element         | Part of Block, component which is tied to its Block and can not stand by it self.   | .car__rear-view-mirror | .car__rearViewMirror |
| Modifier        | An extension or variant of Block or Element who modify them.   | .car--color-red | .car_colorRed |

As you can see, those examples show that this methodology is quite flexible. It should not strictly bind your coding style since you can modify them as long as you achieved the core of BEM.

### Example
### Trade Offs
### Tips and Tricks
Beware of your component starting context! Do not create a Block with a huge context
### References

- [Introduction to BEM]
- [The History of BEM] 
- [CSS Guidelines]


[//]: Links

[Introduction to BEM]: http://getbem.com/introduction/
[The History of BEM]: https://en.bem.info/methodology/history/
[CSS Guidelines]: https://cssguidelin.es/#bem-like-naming

