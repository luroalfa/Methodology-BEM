# METHODOLOGY BEM

## Description BEM
> The BEM methodology helps us divide the user interface into independent blocks.
> This helps us create scalable and reusable components.
> 
As its name suggests, BEM clearly distinguishes 3 concepts:

1. **Block**
2. **Element**
3. **Modifier**


## Block
### For example:
>When making the blocks take into account the following:

1. There are simple and compound blocks, compound blocks are those that contain more blocks inside.
2. You cannot use two underscores in a row or even two dashes in a row as they are reserved for elements and modifiers.
3. Capital letters cannot be used in class names.

**.main** (This is a block)

> It is any autonomous and isolated element of our document.
It can be a menu, a gallery, a form and a browser etc.

## Element
### For example:
**.main__item** (This is a element using __)

>It is each of the elements of the block.
It can be a link, a photo, a text field etc.

## Modifier
### For example:
**.main--footer** (This is a modifier using --)

>When a block exists elsewhere on our website but with a modification. 
It can be the text color, font size, alignment etc.


### For more information:
[Official website](http://getbem.com/introduction/)
[9 Bem Tricks](https://9elements.com/bem-cheat-sheet/)


