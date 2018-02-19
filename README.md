Forked from [https://github.com/baku89/ui-study](https://github.com/baku89/ui-study)

**[Demo](http://kevindoughty.github.io/ui-study/index.html)**

The purpose of this fork was to change knob dragging behavior. Instead of jumping to mouse click location, the knob value changes relative to dragging. I had to remove the arrows/zingers and feel that this was mostly a failure. This behavior would be more desirable if the knob had a larger diameter.

I like knob UI elements because one can get much higher precision than with a linear slider. With a small radius precision is poor, but if you drag perpendicular to the tanget (so the angle doesn’t change) very far from the knob, the precision improves dramatically and is only limited by the screen size.

You can see the original verison with what I feel is less than desirable jump-to-click-location behavior but beautiful zingers and ulitmately a better experience [here](http://s.baku89.com/ui/).

# UI Study

Study of patameter controls UI for creative-purpose softwares. (Such as AfterEffects, Cinema4D)

The motivation of this project is described here: [Study of UI](http://baku89.com/ui)

## Development Environment

### Transpiler languages

 - JavaScript: [TypeScript](https://www.typescriptlang.org/) + [JSX](https://reactjs.org/docs/introducing-jsx.html)
 - HTML: [Pug](https://pugjs.org)
 - CSS: [Stylus](http://stylus-lang.com/)

### Build tools

 - Yarn
 - Gulp
 - Webpack (for only JS)

### To transpile and debug:

```
yarn install
gulp -o
```

## Relating Documents

 - [Classified Table of Parameter Controls](https://docs.google.com/spreadsheets/d/1iyjMUTgJAZhPu4Rg2aV1QPgwSUWBAfuuRCwx0Yki4XM/edit#gid=0)

## License

This repository is published under a MIT License. See the included [LISENCE file](/LICENSE).
