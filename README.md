GT Bootcamp
Homework Week 1
Re-factoring

// Horiseon //
Horiseon is a webpage that has:

A. Navigation Bar with 3 links

B. A Hero image

C. Information Cards:
    1) Search Engine Optimization
    2) Online Reputation Management
    3) Social Media Marketing

D. Aside with the benefits:
    1) Lead Generation
    2) Brand Awareness
    3) Cost Management

E. Footer



THE ASSIGNMENT

The task was to 'clean up' the code by refactoring its elements and make it more accessible.  This goal amounted to (1) more concise code, in both the index.html and style.css files, while (2) improving and maintaining readability of the code by utilizing semantic HTML tag elements and more approachable naming conventions. Nothing was to be done about the look of the page itself when rendered.


THE WORK

1) 
The <link> and <title> tags in the head of the HTML doc were switched, addressing the page's title before pulling in the stylesheet.  The title itself was also changed from 'website' to 'Week 1 Homework.' In practice it would be named something like 'Horiseon.'

2)
A <div> functioning as header was changed to <header> element and its previous 'header' class was removed. The stylesheet was changed accordingly. '.seo' class was kept to though could have been identifed by its <span> tag instead of a class. Ex: header h1 span. For funsies, the logo was linked to go back to index.html.

3)
A <div> containing the navigation bar was changed to <navbar> and the style sheet was changed accordingly.  This differentiated the nav in both the index and stylesheet eliminating the need to use the .header class which was removed anyway.

4)
<section class="article-container"> from <div class="content">.  <section> tag to distinguish informational card section. The class from this section was changed from "content" to "article-container" to provide more clarity to the type of content.

Each <article> was changed from <div> and the specific classes to each, e.g. search-engine-optimization, were dropped and identified by their article element in the stylesheet.  The styling for each was identical, and to add another informational card would be simply add another article without having to do an additional entry in the stylesheet.  If articles are used elsewhere on the page, a more specific class for these styles may be defined.  Additionally, each <img> was given an alt attribute naming the image file used.

5)
A similar process to section 4 above was taken with the benefits aside.  The semantic tag <aside> was used instead of <div> with a class, and a single class was given to each <div> instead of separate classes in order to consolidate their syling in the stylesheet.  <img> tags were given alt attributes according to their their file name.

6)
The footer was given the semantic tag <footer> instead of a generic <div> tag and it's class "footer" was dropped.

7)
Comments were added to both index.html and style.css files to label sections/content.