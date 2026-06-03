# Markdown_lecture
Side  preview command  (ctrl+shift+p)
then open and select preview side 
# 1. Heading
How to give headings in markdown files?
# Heading_1
## Heading_2
### Heading_3
#### Heading_4

# 2. Block of word
this is a normal text in markdown
> This is a block of special text   
> This is a 2nd 
# 3. Line break
this is a data science course  
with dr ammar\
called python_chilla
>line break k lia \ bhi use kia ja skta 
# 4. Combine two things
Block of words and heading


> ## Heading 2


# 5. Face of text
**Bold**\
*Italic*
\
__bold__
\
_italic_


# 6. Bullet points/ List
- Day-1
- Day-2
- Day-3 subheading bnany k lia tab press kr k phr dash and space lgyea
    - days-3
        - day-3
- Day-7    
    - day_7a
        - day_7aa (ye sub heading krny k lia tab press krna hota)
      - day_7b
- day-8

## Other wasy to make lists
> __* or+__

* one
+ 2nd way

> Number of list
For making list write 1 and then . 

1. day1
2. day2
3. day3
4. day4
# 7. Line breaks or page breaks

this is page 1.
this is page 2.

what if we add --- is between these lines 

this is page 1.
---
this is page 2.
___ 
3 times underscore also does the same

# 8. Links and hyperlinks
> copy the link and paste it in <>

<https://www.youtube.com/watch?v=qJqAXjz-Rh4&t=175s>

* How to make click here hyperlink

### the playlist of python ka chilla is here
 how do we do it?

[the playlist of python ka chilla is here](<https://www.youtube.com/watch?v=qJqAXjz-Rh4&t=175s>)

[codanics]:https://www.youtube.com/watch?v=qJqAXjz-Rh4&t=175s

This whole course is [here][codanics]

# 9. Images and figure with link



To join this couse scan this QR code
![QR](qr.png)

For commenting out use shift+alt+A

<!-- File name is qr and it is exactly place the folder and ! is important --> 

For online pic

[codanics](https://www.google.com/search?num=10&sca_esv=6afea18307ffceea&sxsrf=ANbL-n5i4frOIEWQDfkR_sqIP52hEL6n0w:1780487372827&udm=2&fbs=ADc_l-aN0CWEZBOHjofHoaMMDiKpaEWjvZ2Py1XXV8d8KvlI3vWUtYx0DZdicpfE1faGYemEDt_n31nSjnkaGEUuGfK-zDPJCizyjnwOksCKDnrk1iKJl1MGwpfzXm4G_pKDSpYtJnBVn6DyP45tw_PSxG1ziXuS3YYGR0ta0-MAXi8h-2z_utAfn0OhkX5cGyZDupKzCbfL&q=codanics&sa=X&sqi=2&ved=2ahUKEwizrImrgOuUAxVBBdsEHVtJJk4QtKgLegQIHhAB&biw=674&bih=695&dpr=1.25#sv=CAMSVhoyKhBlLWdDdWl2WEZEaFozWFNNMg5nQ3VpdlhGRGhaM1hTTToOTkxvUE1uWDJ4RWFMT00gBCocCgZtb3NhaWMSEGUtZ0N1aXZYRkRoWjNYU00YADABGAcg-Mma3QZKCBABGAEgASgB)

# 10. Adding code or code block

To print a string use print("codanics")

If I use back tick ` (its a key with 1)
Now lets see what happens then

### So this is the procedure to write a code

To print a string use `print("codanics")`
`print("Hello Asmat")`

### How do we write block of code
It means you wrote a multiple code in a single block

so we use three back ticks here 
```
x = 5
y = 4
z= x+y
print(z)
```
### For multiple blocks 
```
print("Hello Asmat")
```
```
x = 5
y = 4
z= x+y
print(z)
```
If I want to use this code for python  then just write a python infront of back ticks

```python
x = 5
y = 4
z= x+y
print(z)
```
> # For R 
```R
x = 5
y = 4
z= x+y
print(z)
```
# 11. Adding tables

|cspecies | petal_length| sepal_length |
|---------|-------------|--------------|
| viginaca|    18.2     |   19.2       |
| setosa  |    08.2     |   14.2       |
| vericola|    13.2     |   19.2       |
| viginaca|    12.2     |   19.2       |
| viginaca|    10.2     |   19.2       |
| viginaca|    18.2     |   19.2       |

Thats how we make tables

Now how we make adjusments/ alignments
> if we want to align the value right use : on right of the doted lines
> if we want to align the value left use : on left of the doted lines
> For middle use : on both sides

|cspecies | petal_length| sepal_length |
|---------|------------:|--------------|
| viginaca|    18.2     |   19.2       |
| setosa  |    08.2     |   14.2       |

|cspecies | petal_length| sepal_length |
|---------|:-----------:|:------------:|
| viginaca| 18.2        |   19.2       |
| setosa  | 08.2        |   14.2       |

# 12. Content

[1. Headings](#1-heading)\
[2. Block of words/ citations](#2-block-of-word)\
[3. Line breaks](#3-line-break)\
[4. Combine two thing](#4-combine-two-things)\
[5. face-of-text](#5-face-of-text)\
[7. line-breaks-or-page-breaks](#7-line-breaks-or-page-breaks)\
[8. links-and-hyperlinks](#8-links-and-hyperlinks)\
[9. Images-and-figure-with-link](#9-images-and-figure-with-link)\
[10. Adding-code-or-code-block](#10-adding-code-or-code-block)\
[11. Adding-tables](#11-adding-tables)


>**Let's make hyperlink and image incarporation bit more easy**\
**link:** R. click on link and select toggle hyperlink (paste the link)
**Image:** R. click on link and select toggle image (write name of image)

[Link](https://www.youtube.com/watch?v=qJqAXjz-Rh4&t=175s)

![Image](qr) 

### If  you want to add tables directly 
R. click on link and select add table

Column A | Column B | Column C
---------|----------|---------
 A1 | B1 | C1
 A2 | B2 | C2
 A3 | B3 | C3

