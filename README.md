# Literary Edinburgh

Literary Edinburgh is the minimum viable product of a mobile-first web application that introduces users to the rich literary history of the capital of Scotland. The site introduces visitors to novels, across numerous genres, which are set in Edinburgh and informs users about literature-related sights, attractions, tours, and events throughout the city. The aims of the website are thus to enrich the experiences of cultural tourists and to increase interest in tourism in the city. Literary Edinburgh is designed in the first instance as shoulder marketing to existing tourist marketing for the city, such as that offered by *This is Edinburgh: Official Guide to Edinburgh* (https://edinburgh.org/), and, as such, is envisaged as a local government initiative to boost economic growth in the city, i.e. rather than a for-profit business in and of itself. Literary Edinburgh could appear as a link on the *This is Edinburgh* website, on flyers in tourist offices, museums, libraries, handed out during festivals, etc., and have its own social media accounts.

## UX

NOTE: A full user experience design document, detailing the five planes of design for Literary Edinburgh appears as a separate PDF. The Following UX section in the present document provides an overview.

Edinburgh thrives on cultural tourism, most notably through its many festivals in August, e.g. the International Book Festival, the Fringe Festival, and The International Festival. Such events draw huge numbers of tourists with disposable income and a keen interest in culture and the arts to Edinburgh each year. These cultural tourists form the primary target group for Literary Edinburgh. As such, the site aims to cater to cultural tourists who are already visiting or interested in visiting Edinburgh in August.

In its present form, Literary Edinburgh is designed for a post-Corona world, in which tourism and event restrictions have returned to normality. However, should the current situation persist in the long-term, the“Books” page enables users to discover Edinburgh through fiction. And in such a context the site could be modified to involve virtual literary tours or act as a platform for writers to perform and discuss their work. This will be discussed further in the‘Features' section.

### User stories

##### User story 1:
“As a huge bookworm, I always love to read about the places I visit so I want to find some great books set in Edinburgh to put me in the mood before I get there.”

##### User story 2:
"As someone who loved visiting Edinburgh last year, I want to read more about the city so I can learn more about its culture and history.”

##### User story 3:

“As someone considering a visit to Edinburgh for the Fringe next summer, I would like to know more about what tours and attractions the city has to offer so I can decide where to spend my holiday.”

##### User story 4:
“As a major reading nerd, I always want to know where I can get my hands on books whenever I am in a city so I know where to go if I am in the mood to read something new.”

## Features: Existing features

##### All pages
* The fixed navigation bar allows users to easily navigate the pages of the site by giving them quick access to the navbar regardless of how far they may have scrolled down any one page.
* The fixed footer allows users to easily access related social media pages by giving them quick access to the footer without having to scroll to the bottom of a long page.

##### Index.html
* Using media queries, the background image of the landing page changes from a landscape of Arthur’s Seat and Edinburgh’s city centre on large devices to a more vertical image of one of Edinburgh's picturesque closes on smaller devices. This enables users to have a more visually pleasing experience of the site by giving them an image which best suits their device.
* The call to action button entitled ‘Get me reading’ enables readers to jump straight to the books page by offering them a visually prominent alternative to the navigation bar.

##### books.html and sights.html
* By offering them a quick inner-page hyperlink, the ‘Return to the top of the page’ button after each genre category allows users to avoid scrolling for a long time to return to the top of the page.
* The ‘fade-out-photo’ provides a buffer at the end of each page and allows users to read the text at the bottom of the pages by ensuring that this text is not covered by the social media links in the footer.

##### books.html 
* The internal page navigation bar allows users to easily browse books by genre by providing inner-page hyperlinks, and, thus to avid scrolling down the page if they so wish.
* The book descriptions allow users to decide whether they are reading a particular book by giving a brief background and plot summary of each.
* The ‘Buy now!’ buttons enable users to purchase a book by providing a direct link to that book’s Amazon page.

##### sights.html 
* The internal page navigation bar, aided by images, allows users to quickly jump to one of the five categories of sights and activities on the page by providing an inner-page hyperlink to each. 
* The descriptions of each sight or activity allow users to decide what they would like to see or do in Edinburgh by giving a brief overview of each.
* The hyperlinks on various sights, activities, and writers enable users to easily find out more information on issues they are interesting by opening up relevant pages on a new tab.
* The embedded videos allow users to find out further information on sights and activities that interest them by watching these videos without having to leave the Literary Edinburgh site.


## Features: Features left to implement
* Given that Literary Edinburgh is conceptualized as static shoulder marketing to the official Edinburgh tourist site *This is Edinburgh: Official Guide to Edinburgh* (https://edinburgh.org/), no “About” or “Contact” pages were included, since contact and overall information would best be delivered on the main site. However, were Literary Edinburgh to become a standalone site with a working marketing team. “About” and “Contact” pages would be among the first additions.
* An ‘Authors’ page comprised of an image gallery of Edinburgh authors. Clicking an author’s image would take the user to an in-site biography and bibliography of the author, including relevant embedded videos and external links.
* A platform for Edinburgh authors to perform their work and to discuss it with readers through live streams.
* A "Local bookshops" page with information on and images of local Edinburgh bookshops. Once I have acquired the skills to do so, an embedded mapping API can assist users in locating each shop.
* Integrating a mapping API for the“Sights and activities” to assist users in finding each sight /activity.
* Develop a social media presence.

## Technologies used
* GitHub was used to host the application’s repositories: https://github.com/
* GitPod served as the IDE on which the site was coded: https://www.gitpod.io/
* The website uses HTML to input the structure and content: https://developer.mozilla.org/en-US/docs/Web/HTML
* The website uses CSS to style the HTML elements: https://developer.mozilla.org/en-US/docs/Web/CSS
* The website uses the Bootstrap 4 framework to simplify the integration and styling of responsive elements: Bootstrap 4: https://getbootstrap.com/
* The site uses Google Fonts to integrate the Lato and Amatic SC fonts into the website: https://fonts.google.com/
* The site uses Font Awesome to integrate social media icons into the footer: https://fontawesome.com/

## Testing

To ensure that the site contains valid HTML, the HTML code was checked by direct input using the W3C Markup Validation Service: https://validator.w3.org/

To ensure valid CSS, direct input via the W3C CSS Validation Service was used: https://jigsaw.w3.org/css-validator/

To test functionality across various devices, I used the web developer tools inspection feature of each of the following browsers:
* Google Chrome
* Mozilla Firefox
* Microsoft Edge
* Microsoft Opera

I manually checked all the pages and features of the website (navigation, links, buttons, hover effects, embedded videos) across all device simulations that each browser offers. In all cases, the site now appears to function as desired. Initially, the “Monuments” navigation image of the “Sights and activities” page did not appear as desired on one device, having not filled the entire screen width on “Laptop with HiDPI screen” according to Chrome developer tools. The simplest solution for this was to find an almost identical image of greater width, which now fills the entire width across all devices.

In addition to checking functionality using browser developer tools, the site has been manually checked and found to function as desired on the following devices:

Laptops (checked by both myself and my wife, Anita):
* Lenovo Yoga 530
* HP 255 G5 Notebook

Tablets:
* Kindle Fire 3 HD (checked by both myself and my wife, Anita)
* iPad mini 3 (checked by my father, George)

Smartphones:
* Samsung Galaxy J4+ (checked by myself)
* Samsung A50 (checked by my wife, Anita)
* iPhone 6+ (checked by my friend, Julia)
* iPhone XR (checked by my brother, Greg)

Initially, some styling problems, particularly overly large spacing between text sections, was a problem on some devices. But this has been resolved using media queries. In the case of the “Books” page, having the book cover image on the left and the descriptive text on the right left too much white space and an unwieldy look on larger screens. As such, the book cover images appear above the descriptive text on larger screens in the finished product.

Once I had deployed Literary Edinburgh to GitHub Pages, the site navigation did not work unless the project GitPod workspace was running. It emerged that I had entered the links incorrectly, hardcoding them using the URLs that appeared on the GitPod preview. The problem was then resolved once the correct navigation links were entered.

### How the site meets user needs

##### User story 1:
“As a huge bookworm, I always love to read about the places I visit so I want to find some great books set in Edinburgh to put me in the mood before I get there.”

##### How the site meets this need:
The “Books” page provides a list of novels, categorized by genre, that take place in Edinburgh. The page contains a description of each novel and a “Buy now!” button with a link to the Amazon page of each novel.

##### User story 2:
“As someone who loved visiting Edinburgh last year, I want to read more about the city so I can learn more about its culture and history.”

##### How the site meets this need:
In addition to the “Books” page providing novels set in Edinburgh, the “Sights and activities” page provides background historical and cultural information on Edinburgh literary landmarks, monuments, and festivals. This information is supported by hyperlinks to relevant, informative websites and by embedded YouTube videos.

##### User story 3:
“As someone considering a visit to Edinburgh for the Fringe next summer, I’d like to know more about what tours and attractions the city has to offer so I can decide where to spend my holiday.”

##### How the site meets this need: 
The “Sights and activities” page contains descriptions of, hyperlinks to, and embedded videos on tours of Edinburgh as well as major landmarks, monuments, and festivals.

##### User story 4:
“As a major reading nerd, I always want to know where I can get my hands on books whenever I’m in a city so I know where to go if I’m in the mood to read something new.”

##### How the site meets this need:
The “Sights and activities” page contains hyperlinks to, and embedded videos on the National Library of Scotland, The Edinburgh International Book Festival, The Writers’ Museum, and The Scottish Storytelling Center, all of which offer ample reading material for anyone interested.

## Deployment
I deployed Literary Edinburgh to GitHub Pages. To do so, I opened the project repository on GitHub, opened the Settings, and scrolled down to the GitHub Pages section. To build the site, I selected the Master Branch option from the drop down menu of sources. GitHub then published Literary Edinburgh to GitHub Pages.

To run the code for Literary Edinburgh locally, one may:
1.	Open the main page of the repository at: https://github.com/RossClarkScotland/Milestone-Project-Literary-Edinburgh

2.	Click the green “Code” button.

3.	Click the clipboard icon to copy the project URL.

4.	Open a terminal in GitPod, or other Integrated Development Environment.

5.	Open the file you wish to clone to.

6.	Enter the following command into the terminal:

$ git clone https://github.com/RossClarkScotland/Milestone-Project-Literary-Edinburgh

Further details are available via: https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository



## Credits

### Content:
* My initial manner of linking the call to action button to the “Books” page was to include anchor tags within the button tags, but the W3C Validation Service flagged this as invalid code. As such, I changed the code to follow the format laid out by W3C Docs at: https://www.w3docs.com/snippets/html/how-to-create-an-html-button-that-acts-like-a-link.html
* The linear-gradient method and centralized call to action button of the landing page were based on the design and code used for the CSS project on the following Udemy course (though the images, linear gradient values, and button, the button being from Bootstrap, themselves differ from those on that course): https://www.udemy.com/course/design-and-develop-a-killer-website-with-html5-and-css3/
* The social media link icons code in the footer was adapted from that in the Bootstrap mini project of the User Centric Frontend Development module. 
* The code for the “Return to the top of the page” buttons was taken, and slightly adapted, from that given on the following web page: https://www.computerhope.com/issues/ch001475.htm#:~:text=In%20your%20HTML%20code%2C%20find%20the%20opening%20%3Cbody%3E,you%20back%20to%20the%20top%20of%20the%20page
* The base structure for the navigation image gallery on the “Sights and activities” page is a now heavily edited version of that given on the following web page: https://www.w3schools.com/bootstrap/bootstrap_images.asp
* Images on the “Sights and activities” page were centered using code from the following tutorial: https://www.w3schools.com/howto/howto_css_image_center.asp

### Media:

##### index.html
* The background image comes from Pixabay.com

##### books.html
* The book cover images are links to those on Amazon.co.uk. This links were made to ensure that A) all images would be the same size, B) that the links would remain secure as they come from a stable website, and C) that the images on the website would match those the users would see when taken to Amazon by the “Buy now!” button. N.B. these images, and this website as a whole, are used only for educational purposes and no copyright infringement is intended.
* The ‘fade-out-photo’ comes from Pixabay.com

##### sights.html
* The “Landmarks” image on in the page navigation bar comes from Pexels.com. The “Monuments” image on in the page navigation bar comes from Unsplash.com. All other images come from Pixabay.com. 
* All videos embedded in sights.html come are hosted on YouTube.

## Acknowledgements:
I would like to thank my wife, Anita, for being a great sounding board for ideas for this project, for proof-reading site content, for double-checking functionality across various devices, and, most of all, for putting up with my furious swearing at my laptop when my code refused to work. 

I also owe a debt to my friend Milana, for being decidedly unimpressed with my first idea for this project, and thus forcing me to think of a better one, and for offering invaluable feedback on site visual design.

I am indebted, too, to my friend Julia, my father, George, and my brother, Greg, for checking the functionality of the website on their devices.

I would also like to express my gratitude to my course mentor, Spencer Barribal, for offering encouragement and useful ideas and to the Code Institute tutors and Slack community for pointing me in the right direction when my code was leading nowhere but the deepest depths of despair.






 
