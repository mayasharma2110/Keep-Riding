# Keep Riding

[Link to live project.](https://mayasharma2110.github.io/Keep-Riding/)

This is a website for a fictional horse riding school. It is aimed for those who are interested in taking up horse riding or those with previous experience who wish to improve thier skills.
The riding school is for those of any age, gender or ability. 

# UX

## User Stories

### First Time Visitor Goals

* As a first time user, I want to understand the purpose of the website and learn about the riding school.
* As a first time user, I want to be able to navigate through the site easily.
* As a first time user, I want to be able to view the website on a laptop, tablet or phone and I want the content to be displayed well on any device.
* As a first time user, I want to see what facilites are offered by the riding school.


### Returning Visitor Goals

* As a returning user, I want to check the range of lessons that are offered and the prices. 
* As a returning user, I want to read reviews from current and previous customers about this school.
* As a returning user, I want to contact the school to book a lesson and/or ask for additional information.
* As a returning user, I want to find out where I can follow the riding school on social media platforms.

### Frequent User Goals

* As a frequent user, I want to check the lessons that are offered.
* As a frequent user, I want to check the cost of the lessons offered and if there are any price increases or reductions.

## Strategy

### Business goals

* Increase interaction with potential new customers.
* Increase presence and following on social media platforms including facebook and instagram.
* Increase the number of lessons/hacks booked.

### User goals/needs

* For the school to offer lessons for new and experienced riders. 
* For the school to have a range of lesson options for experienced riders - both dressage and show jumping.
* For the school to have a small group of experienced instructors. 
* For the school to have a range of horses to suit riders of any ability.
* For the school to offer private and small groups lessons, so they can improve quicker.
* For the school to have an indoor and outdoor areana(s), so that you can ride in any weather conditions.
* For the school to offer hacks for a more relaxed riding experience.

## Scope

Key features to be included based on user stories are:

* Responsive website on mobile, tablet and laptop size devices.
* Interactive elements: navbar becomes a burger menu on mobile, also hovering over elements (in navigation bar and footer) gives a color change.
* About Us - allows users to find out who we are and what we do by having them read a short paragraph.
* Facilities - allows users to find out what specific services we can provide and the facilities we have, by reading a list.
* Reviews - allows users to find out how other customers have enjoyed our services, by providing reviews from previous and current customers.
* Prices - allows users to find out what specific lessons are offered and at what cost, by providing the information in a table format.
* Contact/Booking Form - allows users to contact the school if they wish to book a service or ask for extra information. 
* Footer with links to social media accounts - allows the users to keep up to date with the school by following on social media.

## Structure

All pages of the webiste will have a consistent navigaton bar - which collapses when viewed on a small screen.

The home page will contain an about us section explaining the goals of the riding school.

The website will use bootstrap grids to make the layout responsive to different devices and screen sizes.

All pages of the webiste will have a footer with links to the social media accounts that users can view and follow to keep up to date with the company.

The home page will contain a facilities section explaining what the riding school has to offer and what makes it special from competitors.

The website will comtain a prices section which shows the lessons offered and their prices, including any recent changes (with previous price scored out).

The home page will contain a reviews section showing how other customers have enjoyed their time at the riding school.

The website will comtain a contact section which alows users to get in touch with the school to request more information or book a lesson.

## Skeleton

I used Balsamiq to make the wireframes for this project and they can be found [here](assets/Keep_Riding_Wireframes.bmpr).
The website was designed to have 3 pages - home, prices and contact.

## Surface

### Colours

The three main colors used in the website are yellow (palegoldenrod), brown (saddlebrown) and blue (royalblue).

### Typography

The two fonts used are from google fonts these are Roboto Slab for the headings and Montserrat for the body. 

### Imagery

I used some of my own pictures I had as I have enjoyed doing horse riding in the past. 
However, I also took some other images from the internet and information can be found in the credits section.

# Features

## Existing Features

* Responsive on mobile, tablet and laptop size devices.
* Interactive elements: navbar becomes a burger menu on mobile, also hovering over elements (in navigation bar and footer) gives a color change.
* About Us - allows users to find out who we are and what we do by having them read a short paragraph.
* Facilities - allows users to find out what specific services we can provide and the facilities we have, by reading a list.
* Reviews - allows users to find out how other customers have enjoyed our services, by providing reviews from previous and current customers.
* Prices - allows users to find out what specific lessons are offered and at what cost, by providing the information in a table format.
* Contact/Booking Form - allows users to contact the school if they wish to book a service or ask for extra information. 

## Features Left to Implement

* It would be nice to add a gallery of the horses at the school with a brief description of each.

# Technologies Used

* HTML - used to creat the main content for the website.
* CSS - used to add style and colour to the content.
* Bootstrap - grid layout was used to ensure the content was responsive to different device sizes (mobile, tablet and laptop).
* Javascript - used bootstrap javascript to that the navbar could collpase when viewed on small screens but expand on medium and larger size screens.
* Gitpod - used to write the code for the website.
* Github - used to store the current and previous versions of the code. It was also used to host the live website through github pages. 
* Google fonts - used to import the Roboto Slab and Montserrat font families that are used throught the website.
* Font Awesome - used to display the social media icons in the footer of each page.
* Balsamiq wireframes - used to create the wireframes for the website.
 
# Testing

## Headers and Footers

* Checked the links in navigation bar and footer worked. 
* Checked the navigation bar showed the user what page they were on with a bottom border.
* Checked the navbar is responsive - collapses on small screens and expands on medium and larger size screens.
* Checked the links in the navigation bar change color and become bold when you hover over them. 
* Checked the links in the footer change color when you hover over them.

## Index.html

* Checked the hero-image2 is responsive and changes in height on different devices.
* Checked the 3 sub-headings in index.html change color when you hover over them.

## Prices.html

## Contact.html

* Tested the "contact us" heading changes colour when you hover over it.
* Tested the form makes a user enter all text fields (name, email, phone number), tick one of the radio box options and also enter some text in the enquiry textarea.
* Tested the form only takes a email with a @ in the field.
* Tested the form is responsive to different size devices, the label, input and textarea widths change based on the device the website is viewed on.

## Online validation

* Used chrome developer tools and responsinator.com to check responsiveness on mobile, tablet and laptop devices.
* Used validator.w3.org to validate html and css code. 

* lighthouse in chrome dev tools for performance and accessibility

## Meets user/owner needs

## Fixed bugs

### Bug 1

Navigation bar - Active page was not showing as the correct color (saddlebrown).

![Bug1-problem](assets/images/bug1_1.png)

I had to add the following code to resolve the problem, I did this using chrome developer tools to inspect the font color of the problem text.

![Bug1-resolution](assets/images/bug1_2.png)

### Bug 2

I wanted some vertical whitespace between the sections in the home page, due to using bootstrap grid layout using margins did not work as expected.

![Bug2-problem](assets/images/bug2_1.png)

I added a div inside the columns and gave it a width of 100% of the parent element.

![Bug2-resolution](assets/images/bug2_2.png)

## Unfixed bugs

# Deployment

# Credits

## Content

## Media
Hero-image2 is a picture I have taken.

## Acknowledgments