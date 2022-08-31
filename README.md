# A.K.Amherst

## Welcome To A.K. Amherst's Writer Website!

When visiting the writer's website of A.K. Amherst the user is presented with 4 sections to choose from: About, Books, Short Stories and SEO writing. Clicking on the picture and heading of one section directs the users to the corresponding subsection.

The website is targeted at two types of users. One, the fiction readers searching for interesting novels and short stories to read and the business users who are searching for a good writer for their SEO projects (blogs, website texts etc.).

By showcasing her fictional work, A.K. Amherst shows her writing talent and variety to both type of users. While the Books and Short Story sections are mainly targeted at fiction readers , they showcase her writing style and capability for the business users as well. The short story section is leading to further subpages, each subpage showing one free short story to read. 

The SEO writing section is targeted mainly at the business users but  also offers interesting information for fictional readers. After all, fictional readers may need a business writer as well or know someone who does.

In the About section the writer gives background information about herself and her writing career - which addresses both user types. After all, no matter what they seek - fiction or business writing - they will most likely want to know more about the writer behind it. 

# Responsiveness
All the main page, all 4 sub sections and the short story subpages are responsive as shown in detail below.

## Main Page
![A.K.Amherst Starting Page Screenshot](assets/images/readme/responsiveness/mainpage_resp.png "A.K.Amherst Starting Page")

## Sub Sections 

### About
![About Sub Section Screenshot](assets/images/readme/responsiveness/sub_about_resp.png "About A.K. Amherst")

### Books
![Books Sub Section Screenshot](assets/images/readme/responsiveness/sub_books_resp.png "Books by A.K. Amherst")

### Short Stories
![Short Stories Sub Section Screenshot](assets/images/readme/responsiveness/sub_shortstories_resp.png "Short Stories by A.K. Amherst")

### SEO Writing
![SEO Writing Sub Section Screenshot](assets/images/readme/responsiveness/sub_shortstories_resp.png "SEO Writing by A.K. Amherst")

------

# Features Overall

## Navigation Bar
On top of each page there is a logo allowing the user to go back to the main page. On top of each subsection there is a navigation bar allowing the user to switch between the sub sections. - Since the main page showcasts the four main sections at its center, the navigation bar was not added to the main page. 

![Logo](assets/images/readme/features/navigationbar/logo.pnglogo.png)
![Navigation Bar](assets/images/readme/features/navigationbar/navigationbar.png)

# Features on Pages

## Start Page
The main page is divided in 
    a) a header with the A.K. Amherst Logo
    b) a footer with links to the social media channels (instagram, facebook and twitter), display of email address and copyright
    c) a main section displaying the options to choose from - About, Books, Short Stories, SEO 

![Start Page](assets/images/readme/features/startpage/startpage.png)

## About Page

The About page sums up some background information of the writer A.K. Amherst. To make the information more interesting and more interactive there is a Press sidebar offering two audios of radio interviews to listen to and a press portfolio PDF to flip through.

![About Page](assets/images/readme/features/aboutpage/aboutpage.png)

The title image on the page equals the section image on the front page. Thus, guaranteeing that the users recognize in which section of the page they currently are. An important feature of consistency.

![Title Img About](assets/images/readme/features/aboutpage/titleimgabout.png)

## Books Page
The Books page presents information about the debut novel ' Belfast Central' by A.K. Amherst. Following the same structure as the About page, the books page has a text part explaining the story and background of the book and uses a sidebar for additional information - Book Extras, like a reading extract and book trailer, as well as statements from book blog reviews. Again, creating greater interest and a level of interactivity was the main goal behind this design.  

![Books Page](assets/images/readme/features/bookspage/bookspage.png)

The title image on the page equals the section image on the front page. Thus, guaranteeing that the users recognize in which section of the page they currently are. An important feature of consistency.

![Title Img Books](assets/images/readme/features/bookspage/titleimgbooks.png)

## SEO writing Page
The SEO writing page offers information on the writers experience in business writing, especially regarding online marketing and SEO. A question as the tile catches the readers attention, two lists sum up the most important information and a contact form allows the users to get in touch directly. Following the same structure as the other 3 sections, a sidebar delivers addtional information. In this case, recommendations of customers who worked with SEO writer A.K. Amherst.

![SEO writing Page](assets/images/readme/features/seopage/seopage.png)

The title image on the page equals the section image on the front page. Thus, guaranteeing that the users recognize in which section of the page they currently are. An important feature of consistency.

![Title Img SEO](assets/images/readme/features/seopage/titleimgseo.png)

## Short Stories Page
The Short Stories page gives an overview of short stories by A.K. Amherst that can be read for free on this website. Longer stories only show an extract on the overview page and a 'read more' button leads to the full story. Stories that are really short - only a paragraph - are displayed completely on the page without a 'read more' button. While the short stories overview presents the text part of the page, a sidebar inspires reading short stories with quotes.

![Short Stories Page](assets/images/readme/features/shortstories/shortstories.png)

The title image on the page equals the section image on the front page. Thus, guaranteeing that the users recognize in which section of the page they currently are. An important feature of consistency. On top of that, the title image of the books page shows all formats of the book - paperback, e-book and audio book.

![Title Img Books](assets/images/readme/features/shortstories/titleimgshort.png)

## Subpage_Read 
When clicking the 'read more' button on the Short Stories page, the users are directed to the Subpage to read the short story they picked.
The design of the page differs from the main page as well as the main sections and focuses on the story itself. Below the story is a short story navigation offering the possibility to browse other short stories directly.

![Subpage Read](assets/images/readme/features/subpage_read/subpage_read.png)

The title image on the page equals the section image on the front page. Thus, guaranteeing that the users recognize in which section of the page they currently are. An important feature of consistency. 

![Title Img Read](assets/images/readme/features/subpage_read/titleimgread.png)

------

# Testing
Through out the process of coding the website and its functionalities were tested. The Dev Tools were used for debugging and responsive design decisions.

## Central Debugging Cases
There were two main stages of debugging. Stage 1: First submission. Stage 2: Second Submission.

## Stage 1 Debugging
For the first submission the code was already vastly tested and the following debugging cases were the center of attention.

### TitlePage
The main issue while coding this website was indeed the front page with the four sections at its center. I tried a lot with the float command before being introduced to the flex command by my mentor. In both cases the main challenge was to align the picture tiles and the text captions on top in the same position.
Through research on the net I am aware that such features are far easier to implement with JavaScript. Still, flex is a very good method to do what I aimed to do: visualize the pages content in a 4-split-screen.

### Footer
Another issue I faced during coding was the footer. I imagined to have the 3 social media icons with a decent padding on the left, the email contact in the middle and the copright text on the right. I also wanted to solve this with flex, after being introduced to it. But each time I tried to align the elements, the 3 social media icons were squeezed together. This could be solved by introducing 3 divs in the footer.

### Header
Although, I am aware that the header could be done with flex as well - I even had it in one of the early coding version, I felt like using another approach to train multiple different commands in CSS and HTML and not get to fixed on flex alone.

### Lessons Learned
Through trial and error I managed to program the website I wanted. The main lessons learned were:
1) the level of divs used is very important
2) being careful what I target - sometimes I targeted the div instead of  e.g. the h2 inside the div and wondered why the CSS command was not working.
3) I learned a lot about responsive design - this was a huge process of trial and error.

## Stage 2 Debugging
After a few weeks break I took another chance on making my second submission even better than the first one. The break was very important to get a bit of distance from the work I had done before. All of a sudden a lot of things were much clearer to me than before.

### TitlePage
The main page still suffered from some major issues:
    a) the pictures were stretched due to the tile format I wanted for them (height and width were defined)
    b) the way it was done was too complicated (too many divs)
The break helped me to see a much more straight forward way to solve the issue. I got rid of the complicated div structure and instead focused on the main content which were the pictures. Once I had them aligned with flex in CSS, I added the heading and wrapped the links around it. Adding a purple background color and giving the img as well as the heading an opacity made for the visual effect I aimed for from the start: The pic and heading are changing color when the mouse hovers over. In the first try I tried with a:hover but abondoned it because it didn't work out the way I wanted it to. Now it does.

![Old Start Page](assets/images/readme/features/oldstartpage/AKAmherstStartingPage.png)

### Subpages
To make the overall appearance of the subpages nicer I swapped the title images (giving them a better suiting size), increased the font size and aligned the sidebar content at its center.
With the seo writing page I aligned the input fields into one width, and re-aligned the submit button to improve the overall appearance of the page.
I was considering a background img for the short story subpages but neglected the thought. It would have been too much. The subpages with short stories on them are there to read short stories and not to display pics and pics and pics.

### Header & Footer
I had to update the header and footer CSS due to changes in HTML that were required for the front page. IDs and classes were changed or deleted alltogether, making the code much nicer and the output way clearer.

### Lessons Learned
Sometimes going at something a second time after some break, gives the needed perspective to make a project grow to its full potential. I am very satisfied with the outcome.

------

## Validators
There were validator checks done for the first and second submission stage. In both cases no errors occured. 

### HTML: Stage 1 Testing (1st submission)
The index page as well as all subpages were tested with the W3 validator. The index.html file didn't have any errors or warnings:

![Testing index.html Screenshot](assets/images/readme/index_validation.png "Testing index.html for A.K.Amherst website").

On the subpage shortstories was a bad practice of using a button as a child of an achor tag. I fixed this by creating an anchor tag and styling it as a button. There were a few "loose" closing tags of paragraphs around that I got rid of quite efficiently with this testing. The iframes had values by default that were not needed and also deleted by me throughout this testing.
There also appeared warnings about the use of h1 headings in articles. Since I discussed this with my mentor beforehand and he said it was fine to do it like this, I ignored these warnings on purpose:

![Testing subpages Screenshot](/assets/images/readme/subpages_warning.png "Testing subpages for A.K.Amherst website").

### CSS: Stage 1 Testing (1st submission)

The CSS validator showed no errors for the style.css. For the subpages I had twice used as semi-colon instead of a colon to end a width command. And the color white was not enter properly once. Both mistakes were erased.

![Testing CSS Screenshot](assets/images/readme/subpages_warning.png "Testing CSS for A.K.Amherst website").

### HTML: Stage 2 Testing (2nd submission)



------

## Technologies

### Languages Used

HTML
CSS

### Frameworks, Libraries & Programs Used

1. Google Fonts: Google Fonts was used to import the two fonts "Fredericka the Great" and "Oswald" into the css stylesheet. The fonts are on all pages of this project.
2. Font Awesome: Font Awesome was used to import icons for the social media links in the footer.

## Credits

### Code

1. The following ideas came from the Love Running Project:
    a) setting box-model elements to zero/none in the css stylesheet.

    b) doing the menu as an unordered list

    c) how to create responsiveness for the header.
2. My mentor introduced me to the CSS command flex which opened completely new doors regarding my front page and many other elements in the code.

## Style

1. Font choice: The wireframe worked with the heading font Chalkduster. Since this font was not available by Google fonts, Frederika the Great was suggested by Graphichow (https://graphichow.com/knowledge/what-is-a-chalkboard-font-2/). Thus, this font was chosen as a heading font. Since Google Fonts doesn't the pairing feature anymore the developer googled for pairing fonts and found the recommendation to use Oswald. This recommendation was given by Easil (https://about.easil.com/free-font-pairing-guide-templates/)

2. There are four different page designs on website: 
    
    a) the title page

    b) the subpages main design (about, seo writing, books)

    c) the short stories design (choice of articles menu)

    d) the reading pages of short stories
3. Since the front page already displayed the main navigation, me and my mentor decided that a navigation bar at the top would be repetitive. Still, we decided to add a header and footer for consistency.
4. The main goal of the design was to keep it simple and guarantee that the user has a good overview of the divers content (audio, video, extracts, texts ...) at all times.

### Content

The content of the website was created by me, the developer and writer behind A.K. Amherst.

### Media

The media used on this website was either produced by me or bought for commercial use (e.g. the footage of the book trailer). While the reading extract was layouted by the graphic designer Grit Bomhauer, the press portfolio was designed by me.

### Acknowledgements

Thanks to my mentor who believed in me and this project. His advice and tips were precious and I learned a lot. 

Also thanks to the great teachers at Code Institute and the amazing tutors. The one time I needed a tutor - when first setting up Gitpod - the support was friendly, fast and reliable. 

---
Happy surfing!