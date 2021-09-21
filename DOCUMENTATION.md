# [witchCSS](http://www.witchcss.com) - Documentation
## Introduction
**witchCSS** is a utility library for **CSS**. It is built for easier user interface development. It contains a total of **192** classes and also their **responsive variations** for six media breakpoints to make responsive user interface development easier too. In this documentation, you can find anything about **witchCSS** and learn how to use it.

## Table of Contents
- [Overview](#overview)
    - [Install](#install)
    - [Requirements](#requirements)
    - [Responsiveness](#responsiveness)
- [Classes](#classes)
    - [Direction](#direction)
    - [Wrap](#wrap)
    - [Width](#width)
    - [Align](#align)
    - [Text](#text)
    - [Color](#color)
    - [Spacing](#spacing)
    - [Cursor](#cursor)

## Overview
Learn how to install and use **witchCSS** in your projects.

## Install
Select a method below and get started with **witchCSS**!

### CDN ([jsDelivr](https://www.jsdelivr.com/package/npm/witchcss))
```
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/witchcss@2">
```
Copy and paste the `link` tag above into the `head` tag in your HTML file. 

### [npm](https://www.npmjs.com/package/witchcss)
```
npm install witchcss
```

### [Yarn](https://www.yarnpkg.com/package/witchcss)
```
yarn add witchcss
```

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
You can easily copy and paste the **HTML5** structure below and start developing.
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

| Name | Min-Width |
| - | - |
| `xs` (default) | `1px` |
| `s` | `480px` |
| `m` | `768px` |
| `l` | `1024px` |
| `xl` | `1280px` |
| `2l` | `1440px` |

## Classes
**witchCSS** contains descriptive and short named classes. It is easy to understand what a class does when you read its name.

### Responsive Classes
To use a class with a media breakpoint, simply add `-$bp` to the end of class name. You can see all media breakpoint names [here](#breakpoints).

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
With color classes you can set an element's `color` property. There are 10 color classes.

`.primary` `.secondary` `.red` `.orange` `.yellow` `.green` `.blue` `.violet` `.white` `.light` `.dark` `.black`

### background-color
With background-color classes you can set an element's `background-color` property. There are 10 background-color classes.

`.primary-bg` `.secondary-bg` `.red-bg` `.orange-bg` `.yellow-bg` `.green-bg` `.blue-bg` `.violet-bg` `.white-bg` `.light-bg` `.dark-bg` `.black-bg`

## Spacing
With spacing classes you can set an element's `padding` and `margin` properties.

### padding
Padding classes starts with `p`, then continues with a side (optional). At last ends with a number.

| Name | Value | Computed (Default) |
| - | - | - |
| `p-0` | `0rem` | `0px` |
| `p-1` | `0.5rem` | `5px` |
| `p-2` | `1rem` | `10px` |
| `p-3` | `1.5rem` | `15px` |
| `p-4` | `2rem` | `20px` |
| `p-5` | `3rem` | `30px` |
| `p-6` | `5rem` | `50px` |

### margin
Margin classes starts with `m`, then continues with a side (optional). At last ends with a number.

| Name | Value | Computed (Default) |
| - | - | - |
| `m-0` | `0rem` | `0px` |
| `m-1` | `0.5rem` | `5px` |
| `m-2` | `1rem` | `10px` |
| `m-3` | `1.5rem` | `15px` |
| `m-4` | `2rem` | `20px` |
| `m-5` | `3rem` | `30px` |
| `m-6` | `5rem` | `50px` |

### Sides
There are six sides for spacing classes.

| Name | Value | Example |
| - | - | - |
| `l` | `left` | `pl-3` |
| `r` | `right` | `mr-5` |
| `t` | `top` | `mt-0` |
| `b` | `bottom` | `pb-4` |
| `x` | both `left` and `right` | `px-3` |
| `y` | both `top` and `bottom` | `my-6` |

## Cursor
With cursor classes you can set an element's `cursor` property. There are four cursor classes.

`.c-default` `.pointer` `.not-allowed` `.wait`