**Note**: This guide is written in Markdown. View the code to know the syntax.

## Headings	
`#` for H1

`##` for H2

`###` for H3

`####` for H4

`#####` for H5

`######` for H6


Alternatively you can use `===` for H1 and `--` for H2.

~~~
Heading 1 
=========
Heading 2 
----------
~~~

## Paragraphs

To create paragraphs, use a blank line to separate one or more lines of text. 

~~~

You should not indent paragraphs with spaces or tabs. 

For line breaks, just enter in next line. 

~~~

### Formatting the text

**bold text**

` **Insert text here** `

__alternative bold__

`__insert text here__`

*Italic	 text*

`*insert text here*`

_alternative italic_

`_insert text here_`

Strikethrough is done by `2~`

` ~~This a strikethrough.~~ `

> blockquote

` > Add block quote here ` 

#### multiple block quote example 
~~~
> There are 3 sticks with n discs sorted by size on one of the sticks. 
>
> The goal is to move all n discs to another stick subject to two constraints: move one disc at a time,
>
> and dont'place a larger disc on a smaller one.
~~~

## Horizontal rule 

> can be -- or ____


## Code

Add the code in between the special character back tick ( ` ).

#### Example;

`for x in y: print(x)`

### Fenced code block

Add the code in between ` ```   ``` ` or ` ~~~   ~~~ `

#### Example:

```
def poem():
	print("There is a place where the sidewalk ends")
    	print("And before the street begins,")
    	print("To cool in the peppermint wind.")

for count in [1,2,3]:
    poem(count)
```
## List

### Ordered 

Continue the numbers or repeat one(1). Markdown will automatically order the list. Remember, the numbers can be unordered.

#### Example:

1. `for x in range(5): print(x)`
1. `for x in range(3, 6): print(x)`
1. `for x in range(3, 8, 2): print(x)`

### Unordered 

Use  `-/*/+/-` to start an unordered list. 

#### Example:

- break is used to exit a for loop or a while loop.
- continue is used to skip the current block, and return to the "for" or "while" statement.

### Indented lists

```
1. if expression1:
    - statement(s)
2. if expression2:
    - statement(s)
3. elif expression3:
    - statement(s)
4. else:
   - statement(s)
5. else:
   - statement(s)
```

### Defining List using `:`

term : definition

## Task List 

It is done by square brackets `[]`. Use `[x]` to mark the task as complete. 


- [x] wake up early
- [ ] do exercise
- [ ] eat healthy

## Link

Link can be given as: name in between `[]` and link in between `()`.

It's diaplayed as seen -  [link](https://www.example.com)

### Email address 
To quickly turn a URL or email address into a link, enclose it in angle brackets `<>`. 

Example:
<https://www.bing.com>

<try@example.com>

## Image

Image can be given as: alt_text in `![]` and image file in `()`.

It's diaplayed as seen - ![bing](https://www.bing.com/images/search?view=detailV2&id=4FC1825FF6D187C0E4DDD113302E70170938A29F&thid=OIP.U76zK4i1adU2XTHEXHUhmQHaEo&mediaurl=https%3A%2F%2Fwallpapertag.com%2Fwallpaper%2Ffull%2F9%2F6%2F3%2F865468-bing-images-wallpaper-1920x1200-for-retina.jpg&exph=1200&expw=1920&q=bing+images&selectedindex=0&ajaxhist=0&vt=0&eim=1,2,6)

## Table 

Table can be given in between  ` | ` and ` | `.

#### Example:

| Syntax | Description |
| ----------- | ----------- |
| x == y | assignment operator |
| X ^ y | xor operation |

## Escape characters 

To display a literal character that would otherwise be used to format a text, add a backslash `\` in front of the character.

> \* Without the backslash, this would be a bullet in an unordered list.
