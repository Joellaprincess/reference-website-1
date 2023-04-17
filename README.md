# reference-website
1. Naming convention for all filenames, paths and folders
- The naming conventions for all filenames should be lowercase, no spaces and dashes are fine. Folder naming convention should be similar to filenames. For paths, the folders, assets and files should be inside the root folder so they can be easily linked inside any .html files
    `index.html` 
2. Best practices for commit messages
- Keep commit messages concise and descriptive of the changes made.
- Use the present tense and imperative mood (e.g. "Add new feature" instead of "Added new feature").
- Reference any relevant issue or ticket numbers in the commit message.
3. What is HTML?
- HTML (Hypertext Markup Language) is the standard language used to create web pages. It consists of a series of tags that define the structure and content of a page.
4. Proper syntax for HTML tags
- HTML tags consist of an opening tag, a closing tag, and the content that goes between them. For example, a basic paragraph tag looks like this:
- This is a paragraph.
5. Explain or demonstrate commonly used html tags/elements:
- headings: h1-h6 - Used to create headings of various sizes, with h1 being the largest and h6 being the smallest.
- P: Used to create paragraphs of text.
- Lists: ul, ol, dl - Used to create unordered lists, ordered lists, and definition lists, respectively.
- A: Used to create hyperlinks.
- Img: Used to insert images.
- Q: Used to create inline quotations.
- Blockquote: Used to create block quotations.
- Cite: Used to define the title of a work being referenced.
- Em: Used to emphasize text.
- Strong: Used to indicate important text.
- B: Used to make text bold.
- I: Used to make text italicized.
- Small: Used to make text smaller.
6. Explain block Elements and also explain the list of block elements and why they are used from below:
- In HTML, block-level elements are those that create a block of content, typically starting on a new line and taking up the full width available. These elements are used to structure the content of a web page, and they can contain other elements as well as text. The following is a list of some common block-level elements and their purposes:

    1. html: This is the root element of an HTML document and contains all the other elements.
    2. head: This element contains information about the document, such as the title, metadata, and links to external resources.
    3. body: This element contains the main content of the page, such as text, images, and other elements.
    4. header: This element is typically used to define a header section of a page or article.
    5. nav: This element is used to define a set of navigation links that are typically used to navigate the website.
    6. main: This element is used to define the main content of the page, which should be unique to the page.
    7. section: This element is used to group related content together and often contains a heading.
    8. article: This element is used to define a standalone piece of content, such as a blog post or news article.
    9. div: This element is used to group related content together and often has a specific purpose, such as styling or scripting.
    10. aside: This element is used to define content that is not directly related to the main content of the page, such as a sidebar.
    11. footer: This element is typically used to define a footer section of a page or article.
    12. span: This element is used to group inline content together, such as text or images.
    13. small: This element is used to define smaller text, typically for disclaimers or fine print.
- Block-level elements are used to structure the content of a web page, making it easier to read and understand. By using block-level elements appropriately, you can create a well-organized and visually appealing web page.
7. Explain why accessibility is important and also explain the accessibility properties like:
- Accessibility is important because it ensures that websites and web applications can be used by as many people as possible, including those with disabilities. Accessibility properties help make websites more accessible by providing additional information to assistive technology, such as screen readers. Some commonly used accessibility properties include:
- Landmark roles: Used to define regions of the page, such as the header, footer, and main content.
- Aria labels - Used to provide a descriptive label for an element that may not be clear from its content.
- Image alternative texts - Used to provide a description of an image for users who cannot see it.
8. What is CSS and how can we implement CSS to our html file (write a proper explanation with the code required to attach a CSS file inside html file)
- CSS stands for Cascading Style Sheets and is a styling language used for web pages. It allows you to apply styles like fonts, colors, and layouts to HTML documents. You can implement CSS in an HTML file by adding a style element in the head section of the HTML file or by linking an external CSS file to the HTML file using the link element.
- To link an external CSS file, add the following code in the head section of your HTML file
9. What is the difference between CSS property and value (write explanation and an example code)
- In CSS, a property is an attribute of an element that you want to change, while a value is the specific setting or option for that property. For example, the font-size property can have a value of 16px or 1.2em.
10. Why do we use border-box property in CSS?
- The border-box property in CSS changes the way the width and height of an element are calculated. By default, the width and height of an element are calculated based on the content size, and any padding or border added to it increases the size of the element.
11. Explain different type of ways we can add spacing to an element
- margin: adds space outside of the element
- padding: adds space inside of the element
- line-height: adds space between lines of text
- letter-spacing: adds space between characters of text
- word-spacing: adds space between words of text
12. What is the main difference between margin and padding?
- Margin adds space outside of the element, pushing nearby elements away.
- Padding adds space inside of the element, between the element's content and its border.
13. What are different types of display properties?
- block: creates a block-level element that takes up the full width available and creates a new line after the element.
- inline: creates an inline-level element that takes up only as much width as necessary and does not create a new line after the element.
- inline-block: creates an inline-level element that can have a width and height specified, and creates a new line after the element.
- none: removes the element from the page completely, making it invisible.
- flex: creates a flexible container for a set of child elements, allowing you to control the layout of the children using flexbox properties.
14. Write a brief explanation of flexbox property
- Flexbox is a layout system in CSS that provides a flexible and efficient way to organize elements within a container. It is based on the idea of creating a flexible box that can adapt to the available space and distribute its elements according to various rules and constraints.
15. What are different types of flexbox properties and what is the major difference between them?
- Container properties: These are properties that are applied to the container element and control the layout of the child elements. Some common container properties include display, flex-direction, justify-content, align-items, and flex-wrap.
- Item properties: These are properties that are applied to the child elements and control how they are sized and aligned within the container. Some common item properties include flex-grow, flex-shrink, and flex-basis.
16. Explain with code the use of flexbox property on a parent element and also explain the sub properties you might need for the flexbox property
- To use the flexbox property on a parent element, you need to set the display property to flex. This code creates a flex container with the class name "container". You can then use flexbox properties to control the layout of the child elements within the container.
- Some common flexbox properties include:
    1. flex-direction: controls the direction of the main axis, which can be either row or column.
    2. justify-content: controls the alignment of the child elements along the main axis.
    3. align-items: controls the alignment of the child elements along the cross axis.
    4. flex-wrap: controls whether the child elements should wrap onto a new line if they cannot fit within the container.
17. Write a code example on how you will use a flexbox property on a parent element with sub properties.
- To use the flexbox property on a parent element, you can set the display property to flex. This will create a flex container and turn all its direct children into flex items. The example is in CSS
18. What is CSS grid property?
- CSS Grid is a powerful two-dimensional layout system that allows you to create complex grid structures for your web pages. It provides a way to divide a page into rows and columns and place content in specific areas or cells. CSS Grid is designed to work with both rows and columns, allowing you to create intricate and customizable layouts.
19. Write the parent and two sub-properties used for CSS Grid Property.
- grid-template-rows: Defines the height of each row in the grid. You can specify a value in pixels, percentages, or fractions using the repeat() function.
- grid-template-columns: Defines the width of each column in the grid. You can specify a value in pixels, percentages, or fractions using the repeat() function.
20. What is the difference between display: flex and display: grid?
- The main difference between display: flex and display: grid is that flexbox is a one-dimensional layout model, while grid is a two-dimensional layout model. In flexbox, you can only lay out items in a single row or a single column, whereas in grid, you can create both rows and columns to create a more complex layout.
21. 