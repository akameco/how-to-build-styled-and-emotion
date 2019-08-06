# How to build with styled-components and emotion
[styled-components/styled-components: Visual primitives for the component age. Use the best bits of ES6 and CSS to style your apps without stress 💅](https://github.com/styled-components/styled-components)
[emotion-js/emotion: 👩‍🎤 CSS-in-JS library designed for high performance style composition](https://github.com/emotion-js/emotion)

[laat/babel-plugin-transform-rename-import: rename imports and requires](https://github.com/laat/babel-plugin-transform-rename-import)

.babelrc

```
plugins: [
  [
    'transform-rename-import',
    {
      original: '^styled-components$',
      replacement: '@emotion/styled',
    },
  ],
],
```

## Related
[sapegin/stack-styled: Stacking layouts for React](https://github.com/sapegin/stack-styled)
[jxnblk/superbox](https://github.com/jxnblk/superbox/tree/master)
[google/easy-grid: easy-grid is a React component factory that provides a declarative layout mechanism for utilizing CSS grid layouts.](https://github.com/google/easy-grid)
