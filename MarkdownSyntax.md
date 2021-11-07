AFTER YOU DOWNLOAD THE FILE, "EDIT" IT TO KNOW THE SYNTAX

# Headings	
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

To create paragraphs, use a blank line to separate one or more lines of text. 

~~~

You should not indent paragraphs with spaces or tabs. 

For line breaks, just enter in next line. 

~~~

**bold text**

` **Insert text here** `

__alternative bold__

`__insert text here__`

*Italic	 text*
---
_alternative italic_

> blockquote
---
## Horizontal Rule can be -- or ____
---
## multiple block quote example 
>there are 3 sticks with n discs sorted by size on one of the sticks. 
>
>the goal is to move all n discs to another stick subject to two constraints: move one disc at a time 
>
>and dont'place a larger disc on a smaller one
## sample code
`for x in y: print(x)`
## Fenced Code Block
```
def poem():
	print("There is a place where the sidewalk ends")
    	print("And before the street begins,")
    	print("To cool in the peppermint wind.")

for count in [1,2,3]:
    poem(count)
```
## Ordered List	followed with no.s - remember numbers can be unordered 
# for loop examples
1. `for x in range(5): print(x)`
2. `for x in range(3, 6): print(x)`
3. `for x in range(3, 8, 2): print(x)`
## Unordered List followed by -/*/+/-
- break is used to exit a for loop or a while loop
- continue is used to skip the current block, and return to the "for" or "while" statement
## indented lists 
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
---
Link can be given as name in [] and link in () 
ex - [link](https://www.example.com)
---
Image can be given as alt_text in ![] and image file in ()!
ex - ![bing](https://www.bing.com/images/search?view=detailV2&id=4FC1825FF6D187C0E4DDD113302E70170938A29F&thid=OIP.U76zK4i1adU2XTHEXHUhmQHaEo&mediaurl=https%3A%2F%2Fwallpapertag.com%2Fwallpaper%2Ffull%2F9%2F6%2F3%2F865468-bing-images-wallpaper-1920x1200-for-retina.jpg&exph=1200&expw=1920&q=bing+images&selectedindex=0&ajaxhist=0&vt=0&eim=1,2,6)
---
## Table can be given in between  " | " and also " | "
| Syntax | Description |
| ----------- | ----------- |
| x == y | assignment operator |
| X ^ y | xor operation |

 
## Defining List using :
term : definition
## Strikethrough is done by 2~
~~This a  strikethrough.~~
## Task List is done by square brackets 
- [x] wake up early
- [ ] do exercise
- [ ] eat healthy
## Email address 
To quickly turn a URL or email address into a link, enclose it in angle brackets.

<https://www.bing.com>

<try@example.com>
## escaping characters 
To display a literal character that would otherwise be used to format text in a Markdown document, add a backslash (\) in front of the character.

\* Without the backslash, this would be a bullet in an unordered list.
