<div align="center">

# 🌘 `@ricardojrmcom/use-string-capitalize`

<b>Capitalize strings with React</b>

![build](https://img.shields.io/github/workflow/status/ricardojrmcom/use-string-capitalize/Continuous%20Integration?style=for-the-badge)
![license](https://img.shields.io/github/license/ricardojrmcom/use-string-capitalize?style=for-the-badge)

![author](<https://img.shields.io/badge/Author-Ricardo%20%3Cl1b3r__--%3E%20Mota%20(%40ricardojrmcom)-orange?style=for-the-badge>)

![lang](https://img.shields.io/github/languages/top/ricardojrmcom/use-string-capitalize?style=for-the-badge)
![version](https://img.shields.io/npm/v/@ricardojrmcom/use-string-capitalize?style=for-the-badge)
![size](https://img.shields.io/bundlephobia/min/@ricardojrmcom/use-string-capitalize?style=for-the-badge)

</div>

<br />

---

<br />

### <b>Install</b>

```ts
npm install @ricardojrmcom/use-string-capitalize

yarn add @ricardojrmcom/use-string-capitalize
```

<br />

### <b>Usage</b>

Capitalizes the first character of a given string. Option to capitalize all words.

```ts
import { useStringCapitalize } from '@ricardojrmcom/nova';

export const StringCapitalize = ({ str: string, allWords?: boolean }) => (
  <span>{useStringCapitalize(str, allWords)}</span>
);

<StringCapitalize str="lorem ipsum dolor sit amet" />
-> <span>Lorem ipsum dolor sit amet</span>

<StringCapitalize str="lorem ipsum dolor sit amet" allWords />
-> <span>Lorem Ipsum Dolor Sit Amet</span>
```

<br />

---

<br />

### <b>License</b>

[MIT](https://github.com/ricardojrmcom/use-string-capitalize/blob/main/LICENSE) © Ricardo <l1b3r\_-> Mota ([@ricardojrmcom](https://github.com/ricardojrmcom))

Bootstrapped with 🟣[@ricardojrmcom/supernova](https://github.com/ricardojrmcom/supernova)

<br />
