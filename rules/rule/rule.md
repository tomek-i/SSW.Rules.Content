---
seoDescription: I'd be happy to help you generate an SEO description. Please provide the Markdown or MDX content, "and" I'll do my best to create a concise, keyword-rich, and user-intent-matching description. 😊
type: rule
title: Do you know all the cool stuff you can do on SSW Rules?
uri: rule
authors:
  - title: Christian Morford-Waite
    url: https://ssw.com.au/people/christian-morford-waite
  - title: Sebastien Boissiere
    url: https://ssw.com.au/people/sebastien-boissiere
  - title: Tiago Araujo
    url: https://ssw.com.au/people/tiago-araujo
  - title: Brady Stroud
    url: https://ssw.com.au/people/brady-stroud
  - title: Adam Cogan
    url: https://ssw.com.au/people/adam-cogan
related:
  - do-you-understand-the-value-of-consistency
  - add-useful-and-concise-figure-captions
created: 2021-01-20T05:06:33.000Z
archivedreason: null
guid: 55db32aa-0718-4868-995c-673d8dd69f62
---

This is an example rule + Markdown cheatsheet to give you some guidance around how to write rules and show you the things you can use to format an SSW rule.

## Concepts to write rules

There are a few concepts that are applied to structure most SSW Rules:

1. **Show the pain** - Usually in the intro, explain the problem and context around why that rule exists
2. **Give good and bad examples** - Include practical examples for people to better understand the concepts. [Using images is usually the best way to go](/use-images-to-replace-words)
3. **Explain the why, not the how** - A rule isn't a place to document how to use a 3rd party product. You should focus on the reasons **why** we do something, and then link to external documentation on **how** to do something

See a few examples of SSW Rules that follow the structure of good and bad examples, then link off to external documentation for more information:

* [GitHub Issues - Do you use Issue Templates?](/github-issue-templates)
* [Bicep - Do you use User-defined Data Types?](/bicep-user-defined-data-types)
* [Do you know how to backup data on SQL Azure?](/do-you-know-how-to-backup-data-on-sql-azure)

### 1. Headings, paragraphs, and blockquotes

```markdown
## This is a heading 2 (We never use heading 1 in SSW Rules Content to improve SEO, that's because the title is already a heading 1)

### This is a heading 3

#### This is a heading 4

##### This is a heading 5

###### This is a heading 6 and below is a blockquote

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.  
> Someone famous in Source Title
```

**Figure: Markdown to generate headings and blockquotes**

::: info
Do **not** use heading 1 content - the title is already a heading 1, and we should [avoid using multiple `<h1>` elements on one page](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Heading_Elements#avoid_using_multiple_h1_elements_on_one_page).
:::

## This is a heading 2

Lorem ipsum dolor sit amet. Ut enim ad minim veniam, quis nostrud exercitation. qui officia deserunt mollit anim id est laboru.

## This is a heading 2 with some **emphasized text** by making it bold

**Tip:** See [text decoration section](#2-text-decorations) for more details on making the text bold.

### This is a heading 3

Lorem ipsum dolor sit amet. Ut enim ad minim veniam, quis nostrud exercitation. qui officia deserunt mollit anim id est laboru.

#### This is a heading 4

Lorem ipsum dolor sit amet. Ut enim ad minim veniam, quis nostrud exercitation. qui officia deserunt mollit anim id est laboru.

##### This is a heading 5

Lorem ipsum dolor sit amet. Ut enim ad minim veniam, quis nostrud exercitation. qui officia deserunt mollit anim id est laboru.

###### This is a heading 6

Lorem ipsum dolor sit amet. Ut enim ad minim veniam, quis nostrud exercitation. qui officia deserunt mollit anim id est laboru.

...and this is a blockquote:

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer posuere erat a ante.
>
> Someone famous in Source Title

---

### 2. Text decorations

```markdown
_This text will be italic_
_This will also be italic_

**This text will be bold**
**This will also be bold**

_You **can** combine them_

~~strikethrough~~

<mark>These words</mark> are surrounded by a &lt;mark&gt; (HTML needed)
```

**Figure: Markdown to generate different text styles**

_This text will be italic_  
_This will also be italic_

**This text will be bold**  
**This will also be bold**

_You **can** combine them_
