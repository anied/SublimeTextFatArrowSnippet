# Sublime Text ES6 Fat Arrow Snippet

## Overview

Quick and dirty snippet and instructions for inserting a [fat arrow function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions) (`() => {}`) in your code.  I _think_ I created this myself, but honestly it could be copy/pasted or otherwise inspired by some other author-- I just wanted the ability to write "`fat`" in my editor, hit `TAB` and see a nice juicy fat arrow function inserted with tab completion into the args and then function body.

## Instructions

In Sublime Text 3:

1. Menubar: **Tools > Developer > New Snippet...**
2. Clear out the template provided, and replace it with the code below:

```xml
<snippet>
  <content><![CDATA[
(${1}) => {${2}}
]]></content>
  <tabTrigger>fat</tabTrigger>
  <scope>source.js</scope>
  <description>fat arrow</description>
</snippet>
```

3. That's it!  Open a file with **JavaScript** or **JavaScript (Babel)** and type "`fat`" -- you should see the autocomplete pane open and show the snippet-- if you hit `ENTER` or `TAB` it will insert a fat arrow function with the cursor placed in the args parens-- once you hit `TAB` again it will jump the cursor to the function body.

## What is this?  This sucks!  There's so many better ways to do this!

Yeah, probably.  I mostly created this repo because I had gotten used to this snippet on one of my other machines and wanted the ability to quickly add it to any other machine I was using.  Feel free to suggest improvements or look for better options.
