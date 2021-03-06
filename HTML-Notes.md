# HTML Notes

## Type of Tags
1. Single Tag
2. Container Tag (It has a start-tag and a end-tag)

## Structure

1. html - Overall Tag [Parent of head and body tag]
2. head - Head of the document
- Has the data of the document
- Has attributes and title of the document
- Import other files
- Has settings of HTML files
- Has metadata of actual file

3. body Tag 
- (Has the meat and bones of the webpage)
- All the contents which is visible
- It has all contents

### Any tags that are inside other tag is intendend and follow family terminology

### Browser is the parser that parse the website

4. Title Tag 
- (Has the title of the document)
- Use to hold text, is the title of the website

5. Meta tag 
 - (Holds info about the website)
 - Meta tag holds the charecter about the website

 - ```<meta charset = "UTF-8">```
 - ```<meta name = "description" content = "This is an awesome website">```

Those are attributes or properties and those tag will help to do the jobs. The meta tag is to hold meta data and name is an attribute to define what that info it holds

6. Header Tag
- Ranges from ```<h1> to <h7>```
- It is used to create headers for the website

7. Paragraph Tag

- It is the most common tag
- The text will be showing in paragraph.
- They will automatically format themselves

8. Bold Tag
- ```<b> Content <\b> ```


8. Italic Tag
- ```<i> Content <\i> ```

9. Big, Subscript, Superscript Tag
- ```<big><sub><sup>```

10. Comments
- ```<!-- Comment like this  --> ```
- Use the code sparingly

11. Style Attribute
- ```<p style = "color: white;">```

## Layout of HTML

1. Header
- ```<header>```
Inside of header, You will be having navbar
 - Use a nav Tag to make navigational links or a navigational bars```<nav>``` 
2. Main Content
- ```<main>```
- Use a article for a blogpost ```<Article>```
- Use a section tag to have a section in the blogpost ```<sections>```
3. Footer
- ```<footer>```
- Used for Contact and support 

#### Use only 1 header in the entire page, You can make h2 for sub header, h3 for sub header (Use in hirerchial manner) [ Best Practice]
#### Search Engine Optimisation is an important metric for an website

4. Side Tag
- Use aside tag for Google Ads ```<aside>```

5. Links
- attribute tag and href property
- ```<a href="https://www.google.com" target = "_blank">Google</a>```





## Using images in website

1. ```<img src="Href" alt = "Cat" width=200 height=200/ >```
2.  Setting either the width or the height can resize the automatically. Use either one 

## Using videos 
1. In File 
- ```<video src="Source" loop controls width ="1000" poster = "jpg file">```
- Source is the source / relative path of the video
- Control is to give the controls like play to the video.
- Width fixes the width
- loop loops the video forever

2. Youtube Videos (iFrame)
- Right click the share button
- Click Embed
- Change the height for much clear view

# Using Lists

1. Unordered List
- ```<ul>```
- Unordered List is the one used to create a non-ordered list

- ```<li>```
- List item adds items 
- It has bullets the list

2. Unordered List
- ```<ol>```
- Ordered List is the one used to create a ordered list

- Give a type ["A", "I","i"]
- List can be embeded 


2. Description List
- ```<dl>```
- Ordered List is the one used to create a descriptive list
- ```<dt>```
- They are the descriptive terms 
-```<dd>```
- Descriptive Description

## Creating Tables

1. A table is a way to store or format information
2. The table tag looks like
-   ```<Table>```
3. A table row is one horizontal row in a table or one entry 
- ```<tr>```
4. A table data is for the one column 
- ```<td>```
5. A table header is to give heading for the column. They still reside in the table data
- ```<th>```
6. Caption
- ```<Caption>```
- Comes below the table tag
7. Table header
- `<thead>`
-  Comes Below the caption
8. Table Body
- `<tbody>`
- Comes Abve the thead
9. Column Span [ Attribute ]
- Helps to have a span in the column
-  `colspan`
- It is a attribute to the table data tag


## Types of HTML Elements
1. Block
- Paragraphs are block elements since they take the entire row 
2. Inline 
- Links are inline. They do not take the whole row

## Using Divs and Spans
0. We can use spans and divs as elements
1. Divs are block elements
2. Spans are inline elements

## Using Inputs 

1. Syntax 
- `<input type=""/>`
- Types avaiable are | Text, Password, Date, Email, Range, File, CheckBox, Radio Button, 
- Value is like a prompt for the box 
- Textarea has a closing area 
- `<textarea>`
- Can specify the rows and the cols
- `rows = 100 cols = 100`
- Use a name attrible for checkbox and radio button 
- `type = "radio`
- `type = "checkbox"`

2. Form
- A form is an element to store all the inputs in general
- `<form>`
- Using forms require another programming language like Java or PHP

## Using iFrame
- `<iFrame src="_Source_">`
- Mentions any frame
- give a width and a height and width
- It is like an site inside an site
- frameborder="0"
- Most famous website never allows iFrames

## Using metatags
- It is for SEO
- Have 160 char for a consistent 
- Major backbone for search ranking
- It has a name and an author 
- Keywords can help to make your website relative
- Use viewport to fix width and initial-scale
### Viewport is very much important for a mobile device





