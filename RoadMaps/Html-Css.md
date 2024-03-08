🚀🚀🚀**HTML-ROADMAP**🚀🚀🚀
🔥🔥🔥**Everything you need to know about HTML is here**🔥🔥🔥
1. ==Basic HTML Document Structure== 
   >Document Type Declaration (`<!DOCTYPE html>`): This declaration tells the browser that the document is written in HTML5, the latest version of HTML.
   HTML Element (`<html>`): The root element of an HTML document. All other elements are nested inside this element.
   Head Section (`<head>`): This section contains meta-information about the document, such as its title, character encoding, stylesheets, scripts, and other metadata.
   Title (`<title>`): This element specifies the title of the document, which appears in the browser's title bar or tab.
   Meta Tags (`<meta>`): These tags provide metadata about the HTML document, such as character encoding, viewport settings, and other information for search engines and browsers.
   Link and Style Tags (`<link>` and `<style>`): These elements are used to link external stylesheets or embed CSS styles directly into the document.
   Script Tags (`<script>`): These tags are used to include JavaScript code in the document, either inline or by referencing external script files.
   Body Section (`<body>`): This section contains the main content of the web page, including text, images, videos, forms, and other HTML elements.
   ```
   <!DOCTYPE html>
   <html lang="en">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">
      <title>My Web Page</title>
      <link rel="stylesheet" href="styles.css">
      <style>
         /* CSS styles can also be included inline */
         body {
               font-family: Arial, sans-serif;
         }
      </style>
   </head>
   <body>
      <h1>Welcome to My Web Page</h1>
      <p>This is a basic HTML document.</p>
      <script src="script.js"></script>
   </body>
   </html>
   ```
2. ==Heading Tags== 
   >`<h1> <h2> <h3> <h4> <h5> <h6>` are used to define headings of different levels. 
   `<h1>` is typically the largest and most important heading, while `<h6>` is the smallest. 
   Search engines use heading tags to understand the structure and hierarchy of the content on a page
3. ==Paragraph Tags==
   >`<p>` is used to define a paragraph of text. 
   It's a block-level element, meaning it starts on a new line and stretches out to the full width available. 
   Paragraph tags are commonly used to separate blocks of text, making the content more readable and structured.
4. ==Image Tag==
   >The `<img>` tag in HTML is used to embed images into a web page. 
   It's a self-closing tag, meaning it doesn't require a closing tag. 
   The `<img>` tag has several attributes that allow you to specify various properties of the image, such as its source (src), alternate text (alt), width (width), height (height), etc.
5. ==Links Tag==
   >The `<a>` tag in HTML is used to create hyperlinks, allowing users to navigate between web pages or to specific sections within a page. 
   Here's how the `<a>` tag works: __`<a href="URL">Link Text</a>`__ 
   href: This attribute specifies the URL (Uniform Resource Locator) of the linked document or resource. 
   It can be an absolute URL (starting with "http://" or "https://") or a relative URL (a path relative to the current document). 
   Link Text: This is the visible text or content of the hyperlink that users click on.
6. ==Semantic Tags==
   >Semantic HTML tags provide meaning to the content they encapsulate, making it clearer for both browsers and developers to understand the structure and purpose of different parts of a web page. Here are some commonly used semantic tags:
__`<header>`__ Defines the header of a document or a section. It often contains introductory content or navigation links.
__`<nav>`__ Represents a section of a page that links to other pages or parts within the page, typically used for navigation menus.
__`<main>`__ Specifies the main content of a document or a section within a document. It usually excludes content that is repeated across multiple pages, such as navigation menus.
__`<section>`__ Defines a thematic grouping of content within a document, such as chapters, headers, footers, or any other distinct areas.
__`<article>`__ Represents a self-contained piece of content that can be independently distributable or reusable, such as blog posts, news articles, forum posts, etc.
__`<aside>`__ Indicates content that is related to the surrounding content but can be considered separate from it, such as sidebars, pull quotes, or advertising banners.
__`<footer>`__ Defines the footer of a document or a section. It typically contains information about the author, copyright, contact information, or links to related resources.
__`<figure>`__ Represents any content that is referenced from the main content, such as images, videos, illustrations, diagrams, etc. It's often accompanied by a `<figcaption>` tag to provide a caption.
__`<figcaption>`__ Defines a caption or legend for a `<figure>` element.
__`<time>`__ Represents a specific point in time or a range of time, such as dates, times, or durations. It can improve accessibility and search engine indexing for temporal information.
Using semantic tags not only improves the structure and accessibility of your web pages but also enhances search engine optimization (SEO) by providing clear cues about the meaning and relevance of different parts of your content.
7. ==List Elements==
   HTML provides several list-related elements to organize and present information in a structured manner. 
   The main list elements are:
    Ordered List (`<ol>`): Represents a list of items where each item is sequentially numbered. 
    The numbering can be customized using CSS, but by default, it is rendered as Arabic numerals ```(i, ii, iii, ...).```
    ```
    <ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
    </ol>
    ```
    Unordered List (`<ul>`): Represents a list of items where the order does not matter. Each item is typically preceded by a bullet point.
    ```
    <ul>
    <li>Item A</li>
    <li>Item B</li>
    <li>Item C</li>
    </ul>
    ```
    List Item (`<li>`): Represents a single item in a list, whether it's an ordered list or an unordered list.
    ```
    <ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
    </ul>
    ```
    
    These list elements can be nested within each other to create hierarchical or nested lists. 
    For example:
    ```<ul>
    <li>Main Item 1</li>
    <li>Main Item 2
        <ul>
        <li>Subitem A</li>
        <li>Subitem B</li>
        </ul>
    </li>
    <li>Main Item 3</li>
    </ul>

    This would render as:
<ul>
        <li>Main Item 1</li>
        <li>Main Item 2
            <ul>
            <li>Subitem A</li>
            <li>Subitem B</li>
            </ul>
        </li>
        <li>Main Item 3</li>
    </ul>

    Lists are versatile and commonly used for navigation menus, content summaries, steps in a process, and more. 
    They provide a clear and structured way to present information to users.




8. ==Tables== 
   >Tables in HTML are used to display data in rows and columns. The main elements involved in creating tables are:
   `<table>`: This element defines the whole table.
   `<tr>`: Stands for "table row." It defines a row within the table.
   `<th>`: Stands for "table header cell." It defines a header cell within a row. Header cells are typically bold and centered by default.
   `<td>`: Stands for "table data cell." It defines a regular cell within a row, containing data.
   ```
   <table>
   <tr>
      <th>Header 1</th>
      <th>Header 2</th>
      <th>Header 3</th>
   </tr>
   <tr>
      <td>Data 1</td>
      <td>Data 2</td>
      <td>Data 3</td>
   </tr>
   <tr>
      <td>Data 4</td>
      <td>Data 5</td>
      <td>Data 6</td>
   </tr>
   </table>

   In this example:
   The <table> element defines the entire table. Each <tr> element represents a row. 
   Within each row, <th> elements define header cells, and <td> elements define regular data cells.

   Here's how it would look when rendered in a browser:
   | Header 1 | Header 2 | Header 3 |
   | -------- | -------- | -------- |
   | Data 1   | Data 2   | Data 3   |
   | Data 4   | Data 5   | Data 6   |
   Tables can become more complex with the use of attributes such as colspan and rowspan to merge cells, as well as styling through CSS to customize their appearance. 
   However, it's important to use tables judiciously, as they are primarily meant for tabular data and not for layout purposes. 
   For layouts, CSS is the preferred method.


9. ==Form Elements== 
   >HTML provides a variety of form elements that allow users to input data and submit it to a server for processing. Here are some commonly used form elements:
   `<form>`: Defines an HTML form that collects user input. It's used to wrap all the input elements within a form.
   `<input>`: The most versatile form element, used to create various types of input fields such as text inputs, checkboxes, radio buttons, buttons, and more.
   `<textarea>`: Allows users to input multiline text.
   `<select>`: Creates a dropdown list from which users can select one or more options using `<option>` elements.
   `<label>`: Associates a label with a form control, improving accessibility and usability.
   `<button>`: Represents a clickable button, either a submit button or a regular button.
   `<fieldset>` and `<legend>`: Used to group related form elements together and provide a title or caption for the group.
      ```
      <form action="/submit" method="post">
      <fieldset>
         <legend>Contact Information</legend>
         <label for="name">Name:</label>
         <input type="text" id="name" name="name" required>
         <br>
         <label for="email">Email:</label>
         <input type="email" id="email" name="email" required>
      </fieldset>
      <br>
      <fieldset>
         <legend>Message</legend>
         <textarea id="message" name="message" rows="4" cols="50" required></textarea>
      </fieldset>
      <br>
      <button type="submit">Submit</button>
      </form>
      ```
   >In this example:
   The `<form>` element wraps all the form elements.
   Input fields for name and email are created using the `<input>` element with different types (text and email) and labels associated with them using `<label>`.
   A textarea is provided for the message input.
   A submit button is created using the `<button>` element.
   These are the basic form elements, but HTML5 also introduced new input types and attributes to enhance form validation and user experience, 
   such as type="date", type="number", type="tel", pattern, min, max, etc.

10.   ==Multimedia Tags== 
   >HTML provides several tags to embed multimedia content such as images, audio, and video into web pages. 
   >Here are some commonly used multimedia tags:
   + `<img>`: Used to embed images into a web page.   
      `<img src="image.jpg" alt="Description">`
   + `<audio>`: Embeds audio content into a web page. 
      `<audio controls> <source src="audio.mp3" type="audio/mp3"> Audio element </audio>`
   + `<video>`: Embeds video content into a web page.
      `<video controls width="400" height="300">  <source src="video.mp4" type="video/mp4"> Video element </video>`
   + `<iframe>`: Embeds external web content such as videos, maps, or other webpages into a web page. 
      `<iframe src="https://www.youtube.com/embed/video_id" width="560" height="315" frameborder="0" allowfullscreen></iframe>`
   + `<source>`: Specifies multiple sources for `<audio>` and `<video>` elements, allowing the browser to choose the most suitable one.
      `<video controls width="400" height="300">`
      `  <source src="video.mp4" type="video/mp4">`
      `  <source src="video.webm" type="video/webm">`
      `  Your browser does not support the video element.`
      `</video>`
   + `<track>`: Specifies text tracks for `<audio>` and `<video>` elements, such as subtitles or captions.
      `<video controls>`
      `  <source src="video.mp4" type="video/mp4">`
      `  <track src="subtitles_en.vtt" kind="subtitles" srclang="en" label="English">`
      `  Your browser does not support the video element.`
      `</video>`
>These tags allow web developers to enrich their web pages with various multimedia content, enhancing user experience and engagement.

11.    ==Container Elements== ```<div>, <span>, <section>, <nav>, and <main>.```
12.    ==Structuring a Web Page== ```semantic HTML elements, such as <header>, <footer>, <aside>, <nav>, <main>, etc.```

>__SEMANTIC ELEMENT :__   Semantic HTML refers to using HTML markup that provides meaning and structure to the content it represents. 
By using semantic HTML elements, developers can convey the purpose and significance of different parts of a web page more clearly to both browsers and developers. 
This improves accessibility, search engine optimization (SEO), and overall code readability.
>__CONTAINER ELEMENT :__   Container elements in HTML are used to group and structure content within a web page. 
These elements do not typically have any inherent visual representation but are essential for organizing and styling the content effectively. 
Here are some commonly used container elements: