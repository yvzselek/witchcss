# [witchCSS](http://www.witchcss.com) - Documentation
## Introduction
**witchCSS** is a utility library for CSS. It is built for easier user interface development. It contains a total of **192** classes and also their **responsive variations** for six media breakpoints to make responsive user interface development easier too. In this documentation, you can find anything about **witchCSS** and learn how to use it.

> This documentation context is released under 

## Table of Contents
- [Overview]()
    - [Install]()
    - [Requirements]()
    - [Responsiveness]()
- [Classes]()
    - [Direction]()
    - [Wrap]()
    - [Width]()
    - [Align]()
    - [Text]()
    - [Color]()
    - [Spacing]()
    - [Cursor]()

## Overview
Learn how to install and use **witchCSS** in your projects.

## Install
Select a method below and get started with **witchCSS**.
### CDN (jsDelivr)
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/witchcss@2">
```
Copy and paste the `link` tag above into the `head` tag in your HTML file. 

### npm
```
npm install witchcss
```

### Yarn
```
yarn add witchcss
```
...or you can [download it]().

## Requirements
There are some stuff you should set before using **witchCSS**.

### HTML5 doctype
**witchCSS** only works in **HTML5**. Don't forget to add the line below at the top of your HTML file.
```
<!DOCTYPE html>
```

### Responsive meta tag
To use all features in **witchCSS**, you should add the line below into the `head` tag in your HTML file.
```
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Starter HTML template
You can easily cop and paste the HTML structure below and start developing.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Title</title>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/witchcss@2">
</head>
<body>

</body>
</html>
```

## Responsiveness
**witchCSS** is mobile-first and offers class variations for six media breakpoints.

### Breakpoints

| Name | Screen Width |
| - | - |
| `xs` (default) | `1px` to `479px` |
| `s` | `480px` to `767px` |
| `m` | `768px` to `1023px` |
| `l` | `1024px` to `1279px` |
| `xl` | `1280px` to `1439px` |
| `2l` | `1440px` and above ` |

## Classes
**witchCSS** contains descriptive and short named classes. It is easy to understand what a class does when you read its name.

### Responsive Classes
To use a class with a media breakpoint, simply add `-$bp` to the end of class name. You can see all media breakpoint names [here]().

## Direction
With direction classes you can make an element's `display` property `flex` and set its direction. There are four direction classes.

`.row` `.row-r` `.column` `.column-r`
> `-r` stands for reverse.

## Wrap
With wrap classes you can set an element's `flex-wrap` property. There are three wrap classes.

`.wrap` `.wrap-r` `.nowrap`
> `-r` stands for reverse.

## Width
In **witchCSS** screen is divided into **12** equal pieces. With width classes you can set an element's `width` property up as these pieces' widths. There are 12 width classes.

| Name | Width |
| - | - |
| `w-1` | `8.3%` |
| `w-2` | `16.6%` |
| `w-3` | `25%` |
| `w-4` | `33.3%` |
| `w-5` | `41.6%` |
| `w-6` | `50%` |
| `w-7` | `58.3%` |
| `w-8` | `66.6%` |
| `w-9` | `75%` |
| `w-10` | `83.3%` |
| `w-11` | `91.6%` |
| `w-12` | `100%` |

## Align
With align classes you can align elements that are flex children. There are three types of align classes.

### justify-content
To set an element's `justify-content` property, use `aj` classes. There are six `aj` classes.

`.aj-start` `.aj-end` `.aj-center` `.aj-between` `.aj-around` `.aj-evenly`

### align-items
To set an element's `align-items` property, use `ai` classes. There are five `ai` classes.

`.ai-start` `.ai-end` `.ai-center` `.ai-stretch` `.ai-baseline`

### align-content
To set an element's `align-content` property, use `ac` classes. There are six `ac` classes.

`.ac-start` `.ac-end` `.ac-center` `.ac-stretch` `.ac-between` `.ac-around`

## Text
With text classes you can set several properties of a text element. There are five types of text classes.

### font-size
In **witchCSS** there are seven font sizes. To set an element's `font-size` property, use font-size classes. There are seven font-size classes.

| Name | Value | Computed (Default) |
| - | - | - |
| `t-1` | `1.2rem` | `12px` |
| `t-2` | `1.4rem` | `14px` |
| `t-3` | `1.6rem` | `16px` |
| `t-4` | `1.8rem` | `18px` |
| `t-5` | `2.4rem` | `24px` |
| `t-6` | `3.6rem` | `36px` |
| `t-7` | `4.8rem` | `48px` |

### font-style
With font-style classes you can set a text's `font-style` property. There are three font-style classes.

`.ts-normal` `.italic` `.oblique`

### font-weight
With font-weight classes you can set a text's `font-weight` property. There are five font-weight classes.

`.thin` `.light` `.regular` `.medium` `.bold`

### text-decoration
With text-decoration classes you can set a text's `text-decoration` property. There are four text-decoration classes.

`.td-normal` `.overline` `.line-through` `.underline`

### text-transform
With text-transform classes you can set a text's `text-transform` property. There are four text-transform classes.

`.tt-normal` `.lowercase` `.uppercase` `.capitalize`

## Color