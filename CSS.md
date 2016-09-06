
#Terminology
The following are some terms used throughout this styleguide.

##Rule declaration

A “rule declaration” is the name given to a selector (or a group of selectors) with an accompanying group of properties. Here's an example:

```css
.title-page {
  font-size: 18px;
  line-height: 1.2;
}
```
##Selectors

In a rule declaration, “selectors” are the bits that determine which elements in the DOM tree will be styled by the defined properties. Selectors can match HTML elements, as well as an element's class, ID, or any of its attributes. Here are some examples of selectors:

```css
.title-page {
  font-size: 20px;
}

#page-contant {
  font-size: 20px;
}
```
##Properties

Finally, properties are what give the selected elements of a rule declaration their style. Properties are key-value pairs, and a rule declaration can contain one or more property declarations. Property declarations look like this:

```css
.avatar {
  background: rgb(255,255,255);
  color: rgb(33,33,33);
}
```

#Formatting

The following are some high level page formatting style rules.

##Spacing

CSS rules should be comma separated and leave on a new line:
```css
/* wrong */
.avatar, .tweet {

}
```
```css
/* right */
.avatar, 
.tweet {
...
}
```
Properties should use a space after : but not before:
```css
/* wrong */
.avatar {
  font-size : 12px;
}

.tweet {
  font-size:12px;
}
```
```css
/* right */
.avatar {
  font-size: 12px;
}
```
Rule declarations should have one property per line:
```css
/* wrong */
.avatar {
  font-size: 12px; letter-spacing: 2px;
}
```
```css
/* right */
.avatar {
  font-size: 12px; 
  letter-spacing: 2px;
}
```
Declaration should be separated by two new lines:
```css
/* wrong */
.avatar {
  font-size: 12px;
}
.tweet {
  letter-spacing: 2px;
}
```

```css
/* right */
.avatar {
  font-size: 12px;
}

.tweet {
  letter-spacing: 2px;
}
```

##Spacing
##Nesting
##Quotes
##Comments

#Syntax
##Components
##Descendants
##Modifiers
##States

#References
- [@grvcoelho](https://github.com/grvcoelho)
