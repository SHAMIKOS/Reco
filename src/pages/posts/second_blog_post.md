---
layout: ../../layouts/post.astro
title: "This is the second post of my new Astro blog."
pubDate: 2023-12-24
description: "This is the second post of my new Astro blog."
author: "nicdun"
excerpt: Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et
image:
  src:
  alt:
tags: ["tag5", "tag1", "tag2", "tag3", "tag4"]

---

This is a paragraph. Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

$$
E=m \cdot c^2
$$

## Headings

# H1 For example

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

## H2 For example

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

### H3 For example

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

#### H4 For example

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

##### H5 For example

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

###### H6 For example

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

## Emphasis

Emphasis, aka italics, with _asterisks_ or _underscores_.

Strong emphasis, aka bold, with **asterisks** or **underscores**.

Strikethrough uses two tildes. ~~Scratch this.~~

## Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

## Horizontal separator

This is a horizontal separator:

---

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

---

## List types

### Ordered list

1. List item 1
2. List item 2
   1. Nested list item A
   2. Nested list item B
3. List item 3

### Unordered list

- List item
- List item
  - Nested list item
  - Nested list item
    - Double nested list item
    - Double nested list item
- List item

### Mixed list

1. First ordered list item
2. Another item
   - Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
   1. Ordered sub-list
4. And another item.

## Links

[Inline-style link](https://www.google.com)

[Inline-style link with title](https://www.google.com "Google's Homepage")

[Reference-style link][arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com

## Images

Images included in _\_posts_ folder are lazy loaded.

Inline-style:
![alt text](/images/random.jpg "Logo Title Text 1")

## Table

| Tables        |      Are      | Cool |
| ------------- | :-----------: | ---: |
| col 3 is      | right-aligned | 1600 |
| col 2 is      |   centered    |   12 |
| zebra stripes |   are neat    |    1 |

| Markdown | Less      | Pretty     |
| -------- | --------- | ---------- |
| _Still_  | `renders` | **nicely** |
| 1        | 2         | 3          |

## Syntax highlight

```ts title="astro.config.mjs" showLineNumbers {1-2,5-6}
import { defineConfig } from "astro/config";
import vercelStatic from "@astrojs/vercel/static";

export default defineConfig({
  output: "static",
  adapter: vercelStatic({
    webAnalytics: {
      enabled: true,
    },
  }),
});
```

Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.
Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.
Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur vero esse non molestias eos excepturi, inventore atque cupiditate. Sed voluptatem quas omnis culpa, et odit.

```python showLineNumbers
s = "Python syntax highlighting"
print s
```
