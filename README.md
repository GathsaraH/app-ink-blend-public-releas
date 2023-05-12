# Ink Blend By `Gathsara Umesh`💻
## Demo instrunction
 
`My Markdown` is a markdown component for Free.

👉 Changes are re-rendered as you type.

👈 Try writing some markdown on the left.

## Overview

* Follows Me [Gathsara](https://github.com/GathsaraH)
* My Blog  - [Gathsara's Blog](https://blog.gathsaraumesh.com/)
* This is a initial stage of `My Markdown` You can test this now !🤭
* This will Comout with `Free and Paid plans`
* Has a lot of plugins

## Table of contents

Here is an example of a plugin in action
([`remark-toc`](#)).
This section is replaced by an actual table of contents.

## Syntax highlighting

Here is an example of a plugin to highlight code:
[`rehype-highlight`](#).

```js
import React from 'react'
import ReactDOM from 'react-dom'
import ReactMarkdown from 'react-markdown'
import rehypeHighlight from 'rehype-highlight'

ReactDOM.render(
  <ReactMarkdown rehypePlugins={[rehypeHighlight]}>{'# Your markdown here'}</ReactMarkdown>,
  document.querySelector('#content')
)
```

Pretty neat, eh?

## GitHub flavored markdown (GFM)

For GFM, you can *also* use a plugin:
[`remark-gfm`](#).
It adds support for GitHub-specific extensions to the language:
tables, strikethrough, tasklists, and literal URLs.

These features **do not work by default**.
👆 Use the toggle above to add the plugin.

| Feature    | Support              |
| ---------: | :------------------- |
| CommonMark | 100%                 |
| GFM        | 100% w/ `remark-gfm` |

~~strikethrough~~

* [ ] task list
* [x] checked item

https://example.com

## HTML in markdown

⚠️ You can create more pluging for this.

👆 Use the toggle above to add the plugin.


## Components

You can pass components to change things:

```js
import React from 'react'
import ReactDOM from 'react-dom'
import ReactMarkdown from 'ink-blend'
import MyFancyRule from './components/my-fancy-rule.js'

ReactDOM.render(
  <InkBlend
    components={{
      // Use h2s instead of h1s
      h1: 'h2',
      // Use a component instead of hrs
      hr: ({node, ...props}) => <MyFancyRule {...props} />
    }}
  >
    # Your markdown here
  </InkBlend>,
  document.querySelector('#content')
)
```

## More info?

Much more info is available in `future!`
***

A Developed by [Gathsara Umesh](https://blog.gathsaraumesh.com/)
