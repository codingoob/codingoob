# codingoob

[![NPM](https://nodei.co/npm/codingoob.png)](https://nodei.co/npm/codingoob/)

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fyumetodo%2Fcodingoob.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fyumetodo%2Fcodingoob?ref=badge_shield) [![CircleCI](https://circleci.com/gh/yumetodo/codingoob/tree/master.svg?style=svg)](https://circleci.com/gh/yumetodo/codingoob/tree/master) [![Known Vulnerabilities](https://snyk.io/test/github/{username}/{repo}/badge.svg)](https://snyk.io/test/github/{username}/{repo})

`![alt](I want to edit here!)`

```typescript
import { MarkdownImgUrlEditor } from "codingoob";
const markdownText = `hoge
![img](/path/to/file)
fuga`;
const markdownImgUrlEditor = await MarkdownImgUrlEditor.init(await text2.get(), (a, s) => {
  //a: img
  //s: /path/to/file
  return () => s;
});
// do something
const replaced = markdownImgUrlEditor.replace();
```

We use [pulldown-cmark](https://crates.io/crates/pulldown-cmark)(rust libary) to parse.

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fyumetodo%2Fcodingoob.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fyumetodo%2Fcodingoob?ref=badge_large)
