Please disregard the parenthesis that start and stop the examples I give you for correct notation. They are placed there to stop the markdown file from displaying it and so you can see the correct notation without markdown processing it. 

1. A (#) in a markdown file makes a header. See Below.
# This has one pound sign

2.The amount of (#) you have makes the text smaller. Below has different amounts of # to show an example of what happens. 
## This has two pound signs
#### This has four pound signs 


3.Brackets link to an external link in a Markdown File. This is the correct notation: ([name of link](this is where the link goes)
[Github](https://github.com)

4.You can also do this for another file on your github. The link below links to the other markdown file in my repository. This is the notation: ([what you want to name file](actual name of file)
[testfile](test.md)

5.You can link to an image using (![image](this is where the name of the picture goes). As long as the picture is included in your github files it will load the picture perfectly. 
![image](Unknown.jpeg)

6.This is how you can also link to an image. You can put ([Image](then the link goes in here of the image])
[Image](http://octodex.github.com/images/octdrey-catburn.jpg)

7.The following is an example of syntax coding. You start with three grave accent signs, then put your code in the middle then end it with 3 acute accent signs. 
```javascript
var a = "JavaScript syntax highlighting";
alert(a);
```

8.The following is a blockquote. You can do this by putting a (>) in the front then saying your message after the sign. 
> I have never used a block quote before

9.The following is a bulleted list. You make this by using an asteric that you place in front of each item that needs to be bulleted. 
* Mcdonalds
* Burger King
* Jimmy Johns

10. This is a numbered list all you do is number the list just exactly like you normally would. You can create a nested list by indenting one or more list items below another item.

To create a nested list using the web editor on GitHub or a text editor that uses a monospaced font, like Atom, you can align your list visually. Type space characters in front of your nested list item, until the list marker character (- or *) lies directly below the first character of the text in the item above it.

1. Mcdonalds
2. Burger King
3. Jimmy Johns

11. The following is a table in markdown. To make the columns you use (|). For each row you must have an (|) and also after each item you must have an (|) to tell it to end and to start the next column. After the headers in each column you need to have multiple (-) however long you want that column. This tells markdown you are starting into the content cell. If you want to center align it you need (:) at the beginning and end of the -. Like the middle colummn below. If you want to right align it you need to put (:) at the end of the (-), like the column on the right. To left align it you need to put (:) at the beginning of the (-) after the header. 

| Name          | Type          | Cost  |
| ------------- |:-------------:| -----:|
| Mcdonalds     | fast food     |    $6 |
| Burger King   | fast food     |    $6 |
| Jimmy Johns   | sub shop      |    $9 |

12. Two astericks both at the beginning of the phrase and at the end make the statement bulleted.
**Austin**

13. One asterick at both the beginning and end of the phrase make it italicized.
*Austin*

14. Two of ~ both at the beginning and the end of the phrase make it a strikethough like the following example.
~~Austin.~~

15. To make a horizontal rule you need three of one of the following symbols, they all three must be the same symbol. They can be an asterick, underscore, or hyphens. 
This is a horizontal rule..
___


18. Here is a list of emojis you can add in markdown. 
[Emoji Cheatsheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md)

19. You can also make lists with checkboxes. To do this you put a (-) in front then an ([]) with the text you want it to say as follows:

- [ ] Mcdonalds
 - [x] Jimmy Johns
 - [ ] Burger King
 - [x] Papa Johns
 - [ ] This is a cool example

20. Typing an @ symbol followed by a username, will notify that person that they were tagged in something. 
