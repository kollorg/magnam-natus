<div align="center">
  <a href="https://www.@kollorg/magnam-natus.com">
    <img alt="@kollorg/magnam-natus" src="https://raw.githubusercontent.com/@kollorg/magnam-natus/brand/master/@kollorg/magnam-natus.png" height="150px" />
  </a>
</div>

<br />

<div align="center">
  <strong>Visual primitives for the component age. Use the best bits of ES6 and CSS to style your apps without stress 💅</strong>
  <br />
  <br />
  <a href="https://www.npmjs.com/package/@kollorg/magnam-natus"><img src="https://www.@kollorg/magnam-natus.com/proxy/downloads.svg" alt="downloads: 600k/month"></a>
  <a href="#backers" alt="sponsors on Open Collective"><img src="https://opencollective.com/@kollorg/magnam-natus/backers/badge.svg" /></a> <a href="#sponsors" alt="Sponsors on Open Collective"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsors/badge.svg" /></a> <a href="https://discord.gg/hfGUrbrxaU">
        <img alt="Discord" src="https://img.shields.io/discord/818449605409767454?logo=discord" /></a>
  <a href="https://bundlephobia.com/result?p=@kollorg/magnam-natus" title="@kollorg/magnam-natus latest minified+gzip size"><img src="https://badgen.net/bundlephobia/minzip/@kollorg/magnam-natus" alt="gzip size"></a>
  <a href="#alternative-installation-methods"><img src="https://img.shields.io/badge/module%20formats-umd%2C%20cjs%2C%20esm-green.svg" alt="module formats: umd, cjs, esm"></a>
  <a href="https://codecov.io/gh/@kollorg/magnam-natus/@kollorg/magnam-natus"><img src="https://codecov.io/gh/@kollorg/magnam-natus/@kollorg/magnam-natus/coverage.svg?branch=main" alt="Code Coverage"></a>
</div>

---

**Upgrading from v5?** See the [migration guide](https://@kollorg/magnam-natus.com/docs/faqs#what-do-i-need-to-do-to-migrate-to-v6).

Utilizing [tagged template literals](https://www.@kollorg/magnam-natus.com/docs/advanced#tagged-template-literals) (a recent addition to JavaScript) and the [power of CSS](https://www.@kollorg/magnam-natus.com/docs/api#supported-css), `@kollorg/magnam-natus` allow you to write actual CSS code to style your components. It also removes the mapping between components and styles – using components as a low-level styling construct could not be easier!

```jsx
const Button = styled.button`
  color: grey;
`;
```

Alternatively, you may use [style objects](https://www.@kollorg/magnam-natus.com/docs/advanced#style-objects). This allows for easy porting of CSS from inline styles, while still supporting the more advanced @kollorg/magnam-natus capabilities like component selectors and media queries.

```jsx
const Button = styled.button({
  color: 'grey',
});
```

Equivalent to:

```jsx
const Button = styled.button`
  color: grey;
`;
```

`@kollorg/magnam-natus` is compatible with both React (for web) and React Native – meaning it's the perfect choice even for truly universal apps! See the [documentation about React Native](https://www.@kollorg/magnam-natus.com/docs/basics#react-native) for more information.

_Supported by [Front End Center](https://frontend.center). Thank you for making this possible!_

---

## [Docs](https://www.@kollorg/magnam-natus.com/docs)

**See the documentation at [@kollorg/magnam-natus.com/docs](https://www.@kollorg/magnam-natus.com/docs)** for more information about using `@kollorg/magnam-natus`!

Quicklinks to some of the most-visited pages:

- [**Getting started**](https://www.@kollorg/magnam-natus.com/docs/basics)
- [API Reference](https://@kollorg/magnam-natus.com/docs/api)
- [Theming](https://www.@kollorg/magnam-natus.com/docs/advanced#theming)
- [Server-side rendering](https://www.@kollorg/magnam-natus.com/docs/advanced#server-side-rendering)
- [Tagged Template Literals explained](https://www.@kollorg/magnam-natus.com/docs/advanced#tagged-template-literals)

---

## Example

```jsx
import React from 'react';

import styled from '@kollorg/magnam-natus';

// Create a <Title> react component that renders an <h1> which is
// centered, palevioletred and sized at 1.5em
const Title = styled.h1`
  font-size: 1.5em;
  text-align: center;
  color: palevioletred;
`;

// Create a <Wrapper> react component that renders a <section> with
// some padding and a papayawhip background
const Wrapper = styled.section`
  padding: 4em;
  background: papayawhip;
`;

function MyUI() {
  return (
    // Use them like any other React component – except they're styled!
    <Wrapper>
      <Title>Hello World, this is my first styled component!</Title>
    </Wrapper>
  );
}
```

This is what you'll see in your browser:

<div align="center">
  <a href="https://@kollorg/magnam-natus.com">
    <img alt="Screenshot of the above code ran in a browser" src="http://i.imgur.com/wUJpcjY.jpg" />
  </a>
</div>

---

## Looking for v5?

The `main` branch is for the most-current version of @kollorg/magnam-natus, currently v6. For changes targeting v5, please point your PRs at the `legacy-v5` branch.

---

## Built with `@kollorg/magnam-natus`

A lot of hard work goes into community libraries, projects, and guides. A lot of them make it easier to get started or help you with your next project! There are also a whole lot of interesting apps and sites that people have built using @kollorg/magnam-natus.

Make sure to head over to [awesome-@kollorg/magnam-natus](https://github.com/@kollorg/magnam-natus/awesome-@kollorg/magnam-natus) to see them all! And please contribute and add your own work to the list so others can find it.

---

## Contributing

If you want to contribute to `@kollorg/magnam-natus` please see our [contributing and community guidelines](./CONTRIBUTING.md), they'll help you get set up locally and explain the whole process.

Please also note that all repositories under the `@kollorg/magnam-natus` organization follow our [Code of Conduct](./CODE_OF_CONDUCT.md), make sure to review and follow it.

---

## Badge

Let everyone know you're using _@kollorg/magnam-natus_ → [![style: @kollorg/magnam-natus](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/kollorg/magnam-natus)

```md
[![style: @kollorg/magnam-natus](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/kollorg/magnam-natus)
```

---

## Contributors

This project exists thanks to all the people who contribute. [[Contribute](CONTRIBUTING.md)].
<a href="https://github.com/kollorg/magnam-natus/graphs/contributors"><img src="https://opencollective.com/@kollorg/magnam-natus/contributors.svg?width=890" /></a>

---

## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/@kollorg/magnam-natus#backer)]

<a href="https://opencollective.com/@kollorg/magnam-natus#backers" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/backers.svg?width=890"></a>

---

## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/@kollorg/magnam-natus#sponsor)]

<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/0/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/1/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/2/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/3/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/4/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/5/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/6/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/7/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/8/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/@kollorg/magnam-natus/sponsor/9/website" target="_blank"><img src="https://opencollective.com/@kollorg/magnam-natus/sponsor/9/avatar.svg"></a>

---

## License

Licensed under the MIT License, Copyright © 2016-present Glen Maddern and Maximilian Stoiber.

See [LICENSE](./LICENSE) for more information.

---

## Acknowledgements

This project builds on a long line of earlier work by clever folks all around the world. We'd like to thank Charlie Somerville, Nik Graf, Sunil Pai, Michael Chan, Andrey Popp, Jed Watson & Andrey Sitnik who contributed ideas, code or inspiration.

Special thanks to [@okonet](https://github.com/okonet) for the fantastic logo.
