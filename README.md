# Github Markdown Hacks

Showing some undocumented things you can do with Github Markdown to aid in README design.

## Why?

The readme is probably the most important file in a github repository if you're trying
to convey the value of your project's ideas to readers.

And of course, good design can influence a reader's comprehension and enjoyment of the content.
For us to work on the design of a github readme, it would help to know what it's capable of.

## Official

- [Github Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)
- [Emoji cheat sheet](http://www.emoji-cheat-sheet.com/) :grin:
- [More details from the official markdown renderer repo](https://github.com/github/markup)

## Unofficial

### Previewing locally

- [Grip - Github Readme Instant Preview](https://github.com/joeyespo/grip) - indispensable tool

### Commonly used features

- [Shields](http://shields.io/)

  ```
  <img valign="middle" src="https://img.shields.io/badge/for-example-brightgreen.svg">
  ```
  
  <img valign="middle" src="https://img.shields.io/badge/for-example-brightgreen.svg">

### Not so common

- space before first html tag to allow inner markdown parsing

```
<pre>
Monospace block *without* markdown parsing.
</pre>
```

<pre>
Monospace block *without* markdown parsing.
</pre>

```
 <pre>
Monospace block *with* markdown parsing.
</pre>
```

 <pre>
Monospace block *with* markdown parsing.
</pre>

### Tags with style implications

These may break in the future since they are undocumented:

```
<samp>Monospaced text</samp>
```

<samp>Monospaced text</samp>

```
<ins>Underlined text</ins>
```

<ins>Underlined text</ins>

```
<table><tr><td>Boxed text</td></tr></table>
```

<table><tr><td>Boxed text</td></tr></table>

[You can search here for tags with other style implications](https://github.com/bryanbraun/poor-mans-styleguide)
