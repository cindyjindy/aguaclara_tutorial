# Interactive Tutorial 1: Markdown

## Working with Markdown

Press `Ctrl + Shift + M` to open a formatted preview on the right.

## Basic Text

Write two sentences about yourself, each in a different paragraph.

My name is Cindy Jin.

I like to bake.

## Headers

Make a 3rd level header with your name:

### Cindy Jin

## Emphasis

Write 4 of your favorite words using each type of emphasis:

*Boo*

**Fluffy**

***Simple***

~~Friend~~


## Lists

Make an ordered list of 3 things you hope to achieve this semester, and elaborate on them with sub items. Then, make an unordered list of 3 classes that you're taking this semester:

1. Exercise regularly.
    1. Go three times a week
2. Eat healthily.
    1. Stop eating processed food
3. Get research.
    1. Email professors.
- CHEME 3230
- HD 3620
- CHEM 3900

## Links

Write a sentence describing your major, and insert a link to your major's department website:

[My major is Chemical Engineering.](https://www.cheme.cornell.edu/cbe)

## Images

Insert the Cornell seal image with:
  1. A relative file path(`/images/Cornell_University_seal.png`)
  2. A URL (https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)

![Cornell](/images/Cornell_University_seal.png)

![Local](https://raw.githubusercontent.com/AguaClara/aguaclara_tutorial/master/Images/Cornell_University_seal.svg.png)



## Code Formatting

Put the name of this file in an in-line (single backtick) code format.

`Interactive-Tutorial-1-Markdown`

Put the following text in a Python-formatted code block:

```
def foo():
    print("Particles of a feather...")
    print("...floc together!")
```

```Python
def foo():
    print("Particles of a feather...")
    print("...floc together!")
  ```

## Tables

Create a table listing your 3 favorite animals, books, and places on campus. Use a different alignment for each column.

| Animals | Books | Places |
| --- | :---: | ---: |
|Panda   | Virals | Terrace |
| Penguin  |  Exposure | Upson  |
| Dogs  |Code   | Dorm  |


## Blockquotes

Write your favorite quote. It must be attributed to Albert Einstein.

> Two things are infinite: the universe and human stupidity; and I'm not sure about the universe.

## Horizontal Rules

Add a horizontal rule:

---


## LaTeX Formatting

Copy the equation towards the end of the [Markdown tutorial](https://github.com/AguaClara/aguaclara_tutorial/wiki/Markdown#latex-formatting) and paste it here:

$$ a^2 + b^2 = c^2 $$
