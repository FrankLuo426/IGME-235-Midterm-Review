# Stuff to know for the Midterm:

- The common web professionals and what they do.
  - 
- The organization that oversees the web and who founded it.
  - World Wide Web Consortium W3C
  - 1994 Tim Berners-Lee
- The systems and technologies that get us connected to web servers.
  - Client
  - Domain Name System DNS
  - IP Address
- The default file name that you should use for web pages.
  - index.html
- Some common HTTP status codes.
  - 200 OK
  - 300 redirection
  - 400 Client Error
  - 500 Server Error
- How the HTTP request/response cycle works.
  1.  Type in URL or click a link
  2. The browser sends and HTTP requests
  3. The sever finds the file, and sends back
  4. the browser parse the file
  5. The browser assemble all the things.

- Some basic facts about:

  - Graceful Degradation
    - Design a fully-enhanced experience first, and then create fall-backs for non-supporting browsers.
    - NVidia
  - Progressive Enhancement
    - Provide a better version for the better browser.
  - Responsive Web Design
    - Make the layout different for different browser

- Some typical naming conventions for web documents.

  - No space
  - Allow hyphen or underline 

- The parts of HTML elements

  - Opening tag, Closing tag, Empty tag

- Know what these are:

  - The Document Object Model
    - Gives the document a structure like a family tree
  - Semantic Markup
    - Provide a meaningful description of the content
  - The User Agent Style Sheet
    - the built-in feature that all browsers have that make them display elements in a default style.
  - Caching
    - Store something in your local to make the loading speed up
  - A CSS Reset
    - Clear the user style sheet so they all start from the same point.

- Understand the purpose of heading tags (``, ``, etc) and when to use them.

  - Don’t just use it for size, use it semantically

- Be able to identify what common structural HTML tags do.

  - Header(head is not), footer, nav, section

- Be able to identify common semantic HTML elements.

  - html, head, tittle, body

- Know the two basic generic elements and describe the different attributes that can be used to add identity to them so that they can have CSS rules applied.

  - div can be add ID and Class

- Know the difference between absolute and relative links.

  - / => absolute
  - ../ => back to upper level
  - image/myphoto.jpg => relative

- Know how to make a link to a document fragment.

  - Give an ID to a part and put an a tag link to it

- Know the different image formats that are compatible with the web and how they differ.

  - png jpg gif webP
  - SVG vector

- Why we use alt text in image tags.

  - screen reader

- The basic concepts of bitmapped images.

  - Bitmaps are used to create realistic graphics and images.

- The different places where CSS rules can be applied to a page.

  - External Use link to add css

    ```html
     <link rel = "stylesheet" type = "text/css" href = "myStyle.css" />
    ```

  - Internal css add in the hed tag with style

    ```html
    <head>
        <style>
        	balabalabala
        </style>
    </head>
    ```

  - Inline css

- The common CSS units of measure.

  - Px - A pixel (defined in CSS3 to be 1/96 of an inch)
  - Vh - The viewport height. Equal to 1/100th of the current browser window height.
  - Rem - A root em (equal to the em size of the root element)
  - Em - A unit of measurement equal to the size of the current font.
  - Ex - A unit of measure equal to the height of a lowercase "x" in the current font.
  - Vw - 	Equal to 1/100th of the current viewport width.
  - Pt - A point. 1/72 of an inch. A unit commonly used in print design.

- Know the various forms of CSS selectors.

  - Style rule - strong { color: red; font-style: italic; }
  - Selector - strong
  - Declaration - color:red;
  - Declaration block - 	{ color: red; font-style: italic; }
  - Property - color
  - Value - red

- Some basic ways to specify colors such as black, white, and gray.

  - 

- Know the five basic types of positioning. (static, relative, absolute, etc)

  - Static - The normal positioning scheme in which elements stay where they'd normally occur in the document flow.

  - Relative - Move the element from its original location to a spot that is related to the viewport or containing element. The space it previously occupied is closed up and has no influence on other elements.

    生成相对定位的元素，相对于其正常位置进行定位。

    因此，"left:20" 会向元素的 LEFT 位置添加 20 像素。

  - Absolute - Moves the element from its original position to a new location, leaving the space where it used to be located as an empty area.

    生成绝对定位的元素，相对于 static 定位以外的第一个父元素进行定位。

    元素的位置通过 "left", "top", "right" 以及 "bottom" 属性进行规定。

  - Fixed - The element becomes positioned in one spot (even if the document scrolls) relative to the viewport rather than another element in the document.

    生成绝对定位的元素，相对于浏览器窗口进行定位。

    元素的位置通过 "left", "top", "right" 以及 "bottom" 属性进行规定。

  - Sticky - A combination of other positioning behaviors that allow the element to scroll into a specific position relative to the viewport, at which point it remains fixed in place.

- Know what breakpoints are and how we specify them.

  - ```css
    @media screen and (max-width: 300px)
    ```

- Know a rule of thumb for each of the Basic (CRAP) Design principles (and what are they, of course)

  - Contrast 
    - making different things different
    - making the important elements stand out
    - muting less important elements
    - creating a bit of dynamism on the screen.
  - Repetition
    - Introductions
    - Scenarios
    - Screens with media (images, audio, video)
    - Interactions
    - Summaries
    - Quiz instructions
    - Quiz screens
  - Alignment
    - make everything has a same alignment
  - Proximity
    - put the same thing in the same group

- The purpose of an .htaccess file and how and when it’s directives are followed.

  - change sever setting(404, index.html)
  - only one per folder

- The order in which the Site Design process steps are followed.

  - 

- The basic questions that all good navigation systems should address.

# Stuff to be able to do:

- Spot correct and incorrect markup examples.
- Create a functional link tag.
- Look at a file structure and determine relative links to connect various pages/resources.
- Write a valid image tag.
- Identify the different parts of a CSS style rule.
- Specify a preferred font using the font-family property.
- Label the different parts of CSS box model.
- Define a flexbox container and its items as well as basically how to control their layout.
- Define a grid container and its items as well as some techniques to specify how you’d like the grid to behave.
- Provide the complete minimal HTML skeleton necessary to pass validation.
- Write a basic CSS rule to change the properties of a page element.
- Write CSS selectors that target a single id on the page and/or all elements of a certain class.
- Write a descendant selector.
- Create an ordered list, and unordered list, and a description list.
- Apply pseudo-class styles (there are five of them) to links (and in what order) to make them colors other than the blue and purple defaults.
