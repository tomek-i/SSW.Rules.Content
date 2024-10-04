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

<!--endintro-->

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

~~strikethrough~~

_You **can** combine them_

<mark>These words</mark> are surrounded by a &lt;mark&gt; (HTML needed)

---

### 3. Lists

```markdown
#### Unordered lists

- This is the first item of an unordered list
- This is the second item of an unordered list
  1.  This is the first item of an ordered list inside an unordered list
  2.  This is the second item of an ordered list inside an unordered list
- This is the third item of an unordered list
  - This is the first item of an unordered list inside another
  - This is the second item of an unordered list inside another
    1. This is the first item of an ordered list inside a nested unordered list
    2. This is the second item of an ordered list inside a nested unordered list

#### Ordered lists

1. This is the first item of an ordered list
2. This is the second item of an ordered list
3. This is the third item of an ordered list
   - This is the first item of an unordered list inside an ordered list
   - This is the second item of an unordered list inside an ordered list
     1. This is the first item of an ordered list inside another
     2. This is the second item of an ordered list inside another
```

**Figure: Markdown to generate lists**

#### Unordered lists

* This is the first item of an unordered list
* This is the second item of an unordered list
  1. This is the first item of an ordered list inside an unordered list
  2. This is the second item of an ordered list inside an unordered list
* This is the third item of an unordered list
  * This is the first item of an unordered list inside another
  * This is the second item of an unordered list inside another
    1. This is the first item of an ordered list inside a nested unordered list
    2. This is the second item of an ordered list inside a nested unordered list

#### Ordered lists

1. This is the first item of an ordered list
2. This is the second item of an ordered list
3. This is the third item of an ordered list
   * This is the first item of an unordered list inside an ordered list
   * This is the second item of an unordered list inside an ordered list
     1. This is the first item of an ordered list inside another
     2. This is the second item of an ordered list inside another

---

### 4. Links

```md
[link text](https://www.url.com "link title")
```

**Figure: Markdown to generate links**

This is [an internal link](https://www.ssw.com.au).

This is [an internal link with title](https://www.ssw.com.au "This is a link title") (hover me).

This is [an external link](https://www.google.com).

::: greybox
**Cool link features:**

* We use [icons on files' links](/use-icons-to-not-surprise-users) to not to surprise users
* Our main headings auto-generated [anchor links](/anchor-links) so users can easily access a section of a long page like this one.
   E.g. To go straight to this section of the page, you can access [https://ssw.com.au/rules/rule/#4-links](#4-links)

:::

---

### 5. Boxes

```md
::: greybox  
This is a box using the class "greybox".  
:::
```

**Figure: Markdown to generate boxes**

::: greybox  
This is a box using the class "greybox".  
:::

::: highlight  
This is a box using the class "highlight".
:::

::: highlight  
## This is an example of a heading in a highlight 
:::

::: info  
This is a &lt;div&gt; using the class "info". Works the same as using a &lt;p&gt; . Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation.  
:::

::: info  
## This is an example of a heading in a info 
:::

::: china  
This is a &lt;div&gt; using the class "china". Works the same as using a &lt;p&gt; . Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  
:::

::: china  
## This is an example of a heading in a china 
:::

::: codeauditor
This is a &lt;div&gt; using the class "codeauditor". Works the same as using a &lt;p&gt; . Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.  
:::

::: codeauditor  
## This is an example of a heading in a codeauditor 
:::

::: todo  
This is a &lt;div&gt; using the class "todo". Works the same as using a &lt;p&gt; . Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.  
:::

#### Hiding content

Use the class "hidden" to hide content.

```md
::: hidden  
bfb265e3-644e-4cbe-b17c-4d378b014809-7947936  
:::
```
