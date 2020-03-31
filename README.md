# Bere Gloria

![Multi device Screenshot](https://github.com/Magnusson95/MS1-Bere-Cu-Miere/blob/master/wireframes/index-multi.jpg?raw=true)

Bere Gloria is an established Brewery in Romania, with need for an updated website. You can visit the site [here](https://magnusson95.github.io/MS1-Bere-Cu-Miere/).

Potential customers will come to the site for information on the products they sell including locations where they can find them and differences between the different beers.

Potential suppliers can come to the site for information on how to contact Bere Gloria and understand the current market in their city.

---

# Contents

---

## UX

### User Stories:

* "As a new customer, I want to see Bere Gloria's social links, so I can see Bere Gloria's social posts."
* "As a customer, I want to order the beer online, so I can have the the beer delivered to my door."
* "As a new customer, I want to see where the beer is brewed and find out the history of the business, so I can appreciate the product and discuss it with friends."
* "As a customer, I want to subscribe to news updates, so I can find out about new product releases."
* "As a customer, I want to provide feedback, so I can let Bere Gloria know what they're doing well/not well."
* "As a supplier, I want to contact the company, so I can start a commercial contract to supply their beer."
* "As a new customer, I want to find out what other beers are on offer, so I can pick products I will like."
* "As a customer I want to know what events Bere Gloria is attending, so I can go and enjoy the beer at local events."
* "As a customer I want to know where I can go to drink Bere Gloria, so I can drink Bere Gloria in the pub with friends"

### Design Choices

* Pagination style with distinct pages for each section
* Video of the product acts as a hero image as you land on the page, with the invitation to scroll to see the products in order to purchase them
* Gold was used as one of the primary colours (#997137) as one of the key ingredients of the product is honey. This was complemented with a dark red (#631519) within the logo and graduated to black as the main background colour of the site as a nod towards the Romanian national colours; the red has been purposefully darkened as I feel this gives a more modern look, merges with the gold well and ensures the background colour does not vary drastically as it graduates to black.
* EB Garamond is the main font family used which is well suited to large font sizes which feature throughout the page and blends well with the classic style of the monument depicted in the logo.
* Icons are used within the navbar to accentuate the descriptions of the pages and within the optional radio buttons for the contact form to provide clarity and interactivity.

### Wireframes: 

I used [Balsamiq](https://balsamiq.com/) to create detailed wireframes for each page at a desktop level.

As is to be expected certain elements present in the wireframes did not make it into the project itself but may yet do so further down the line.
 
You can find my wireframes [here](https://github.com/Magnusson95/MS1-Bere-Cu-Miere/tree/master/wireframes).

---

## Features

### Existing Features
* Navbar that fixes to the top of the screen at all times to enable user instant navigation around the. Collapses into burger menu on smaller screens.
* Contact section with name, email and text input fields.
* Footer at the bottom of each page that allows you to subscribe with name and email input fields
* Events section which provides posters of events which, when hovered on, show details an event links
* About us page which gives information about the Brewery company and the Monument it was named after
* A locations page which provides a map of the different cities in which the product is sold at bars, with a list of those bars and direct links to google maps for each location
* Contact details including email address (automatically opens to send mail), company address which opens to a google maps link of the location and an embedded map of the company address
* Product section showing each of the 3 products, with details of each and a link to buy online

### Features Left to Implement

* Allow customers to book a tour of the Brewery, by having them fill out a form with date and time inputs.

---

## Technologies Used

* Adobe Illustrator
* Adobe Illustrator was used to remove backgrounds from images
* Github to host this project's respositories.
* Gitpod IDE of choice for development.
* Git for version control
* Google Chrome developer tools for testing and troubleshooting.
* Coolers for colour schemes.
* W3C Markup Validation used to validate HTML.
* W3C CSS validation used to validate CSS.

---

## Languages

* HTML to build the page.
* CSS to style the page.

---

## Libraries

* [Bootstrap](https://getbootstrap.com/) used for initial layout but later removed; some bootstrap remained for basic styling of buttons.
* [Font Awesome](https://fontawesome.com/) for icons.
* [Google Fonts](https://fonts.google.com/) used for fonts.

---

## Testing

Throughout development of this project Google Chrome developer tools was used to check the styling and layout of the page.
Particular care and attention was taken to ensure the page was responsive at all screen sizes by selecting the various device models and dragging the responsive window past breakpoints.

### Internet browsers

The same process of opening up the live page and meticulously clicking all links, buttons, and re-sizing of windows was utilized in the following browsers:
* Google Chrome - Main browser of choice for development.
* Microsoft Edge – All working as intended besides flex at minimum width
* Mozilla Firefox - No issues. Everything works as intended.
* Safari - All working as intended.

The site has been tested physically on a number of mobile devices including:
* iPhone 5, 7, 10 and 11
* Google Pixel
* Galaxy S9.

### Issues and Resolutions

* Firefox was not showing text in event page when hovering on event posters. Instead of using opacities and multiple z-index functions, which worked on the other browsers tested, I simplified my code to only adjust the bottom layer of the event card (the underlying text) with a z-index and remove all opacity functions; this fixed the bug.
* When reducing the screen size down to mobile it was noticed that the text within my event posters was overflowing. This was fixed by using media queries to reduce the font-size of the text and adjusting the number of columns to 1 on the smallest devices.
* I found that the bootstrap layout was causing some containers to overflow the width of the screen, and others to cause a narrow white margin along the side of the page. As this was widespread across the whole site, I decided to remove all bootstrap layout classes and use flex to create my layouts instead

### Known Issues
* •	All responsiveness working on Microsoft Edge except minimum flex view

---

## Deployment

Bere Gloria was developed on GitPod, using git and GitHub to host the repository.

__When deploying Bere Gloria using GitHub Pages be sure to follow these steps:__

1.	Navigate to '/Magnuson95/MS1-Bere_Cu_Miere' or alternatively click here.
2.	In the top navigation click on 'settings'.
3.	Scroll down to the GitHub Pages area.
4.	Select 'Master Branch' from the 'Source' dropdown menu.
5.	Click to confirm my selection.
6.	Mambo should now be live on GitHub Pages.

__In order to run Bere Gloria locally be sure to follow these steps whilst still on Github:__

1.	Navigate to '/Magnusson95/MS1-Bere-Cu-Miere' or alternatively click here.
2.	Click the green 'Clone or Download' button.
3.	Copy the url in the dropdown box.
4.	Using your IDE of choice open up your preferred terminal.
5.	Navigate to your desired file location.
6.	Copy the following code and input it into your terminal to clone Mambo.

```git clone https://github.com/Magnusson95/MS1-Bere_Cu_Miere.git```

---

## Credits

### Content

* All content was written by myself or provided by the client’s original website and translated

### Media

* The product photos were taken by myself
* The logo was designed by myself on Adobe Illustrator
* The events logos were provided by the client’s original website and their Facebook Page
* Index.html hero video is a royalty-free, full use license video provided downloaded from videvo

### Acknowledgements

* I received inspiration for this project from Bere Gloria’s original website, and the product card design from the Youtube Page “Online Tutorials”
