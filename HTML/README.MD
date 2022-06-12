# Interview questions HTML

## 1) What is html?
answer:- Html stands for hypertext markup language, using html we can create web pages. Html is use to create the structure of web pages.

Basic syntax:
```
    <HTML>
        <HEAD>
            <TITLE>Website title</TITLE>
        </HEAD>
        <BODY>
            <p>Some test here...</p>
        </BODY>
    </HTML>
```

## 2) What are Tags?
answer:- Tags in html used to show the content of the web pages, where we have left and right paired and single self closing tags in web pages.

## 3) Do all HTML tags have an end tags?
answer:- No. all HTML tags don`t have end tags.

## 4) What is formatting in HTML?
answer:- In html, text formatting is way of formatting the text of a web page as bold, italic, underline and are used to make a web page better for the look and feel.

## 5) How many types of heading does an HTML document contain?
answer:- In html, we have heading from ```<h1>``` to ```<h6>``` tags for heading text resizing.

## 6) How to create a hyperlink in html?
answer:- In html, we can create hyperlink by using anchor tag ```<a>some_url</a>``` and anchor tags also appear in different colors 1) unvisited - underline and blue 2) visited - underline and purple 3) active link - underline and red

## 7) Which HTML tag is used to display the data in the tabular form?
answer:- HTML table tag is used for displaying the data into the tabular form
``` <table> ``` it defines the table.
```<tr>``` it defines the row.
```<th>``` it defines the heading of the column cell.
```<td>``` it defines the table data cell of a column.
```<caption>``` it defines the caption of the table.
```<colgroup>``` it specifies the group of one or more column. its a child tag of col tag.
```<col>``` it used while grouping the style of one or more column. it is used with colgroup tag only.
```<tbody>``` it specifies the group of body content in a table.
```<thead>``` it specifies the group of heading in a table
```<footer>`` it specifies the group of footer content in a table.

## 8) What are some common lists that are used when designing a page?
answer:- We can use lists type:
1) Ordered list - ```<ol> <li>item here... <li> <ol>``` it display the items in numbers
2) Unordered list - ```<ul> <li>item here... <li> <ul>``` it display the items in bullets
3) Definition list - ```<dl> <dd>text <dd> <dt>item here...</dt> <dl>``` it display the definition

## 9) What is the difference between HTML elements and tags?
answer:- Tags the pair brackets <> to show the text content and html elements are elements which communicate with browser to render the text.

## 10) What is semantic HTML?
answer: - Semantic HTML is a coding style. It is used to tell the meaning of html tags syntax.  ```<b>``` tags are not for bold and ```<i>``` it not for italic text. We have ```<strong>``` tag for bold text and ```<em>``` for italic text style.


## 11) What is an image map?
answer:- Using image map we can make image area clickable and can set the clickable area shape as react, circle , poly, default as entire region and we can set the coordinated using chords attribute. ```href``` is used to set the navigation url path.
example:
```
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
  <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm">
  <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm">
</map>
```

## 12) How to insert a copyright symbol on a browser page?
answer:- We can use the syntax ``` &copy; ``` or ``` &#169; ``` in a html file.

## 13) How to create a nested webpage in HTML?
answer: we can make the nested webpage by using ```<iframe>``` tag.
example:
```
<!DOCTYPE html>    
<html>    
<body>    
<h2>HTML Iframes example</h2>    
<p>Use the height and width attributes to specify the size of the iframe:</p>    
<iframe src="https://www.javatpoint.com/" height="300" width="400"></iframe>    
</body>    
</html>    
```

## 14) How do you keep list elements straight in an HTML file?
answer: You can keep the list elements straight by using indents.
The list-style-position property is used to keep list elements straight in an HTML file.
This property specifies if the list-item markers should appear inside or outside the content flow.
```
<!DOCTYPE html>
<html>
    <head>
        <style>
            ul.i
            {
                list-style-position: inside;
            }
            ul.o
            {
                list-style-position: outside;
            }
        </style>
    </head>
    <body>
        <p>list-style-position: inside:</p>
        <ul class="i">
            <li>HTML</li>
            <li>JavaScript</li>
            <li>jQuery</li>
        </ul>
        <p>list-style-position: outside:</p>
        <ul class="o">
            <li>HTML</li>
            <li>JavaScript</li>
            <li>jQuery</li>
        </ul>
    </body>
</html>
```




## 15) Does a hyperlink only apply to text?
answer:- No. We can use any image, text, or div element to work like same as hyperlink
example: ``` <a href = "..........."> Any tag element here </a>  ```

## 16) What is a style sheet?
answer:- Style sheet are used to style the HTML markups in any format, design or color.

## 17) Can you create a multi-colored text on a web page?
answer:- Yes. To create a multicolor text on a web page you can use ```<font color ="color"> </font>``` for the specific texts you want to color.

## 18) Is it possible to change the color of the bullet?
answer:- Yes we can but when we change the color of the bullet the text color also been changed.

## 19) What is a marquee?
answer:- marquee is used to make moving text or image element from different directions like up, down, bottom and top. We can also specify the speed as well.

## 20) How many tags can be used to separate a section of texts?
answer:- There are three ways to separate a section of text.
 1) ```<br>`` it will break the text.
 2) ```<p>``` it will break the para of the text.
 3) ```<blockqoute>`` it will pull the entire text in tag section only.