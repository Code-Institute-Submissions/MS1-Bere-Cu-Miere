Bere Gloria
Bere Gloria is an established Brewery in Romania, with need for an updated website. You can visit the site here.
Potential customers will come to the site for information on the products they sell including locations where they can find them and differences between the different beers.
Potential suppliers can come to the site for information on how to contact Bere Gloria and understand the current market in their city.
UX
User Stories:
•	As a user type, I want to perform an action, so that I can achieve a goal.
•	As a new customer, I want to see Bere Gloria's social links, so I can see Bere Gloria's social posts.
•	As a customer, I want to order the beer online, so I can have the the beer delivered to my door.
•	As a new customer, I want to see where the beer is brewed and find out the history of the business, so I can appreciate the product and discuss it with friends.
•	As a customer, I want to subscribe to news updates, so I can find out about new product releases.
•	As a customer, I want to provide feedback, so I can let Bere Gloria know what they're doing well/not well.
•	As a supplier, I want to contact the company, so I can start a commercial contract to supply their beer.
•	As a new customer, I want to find out what other beers are on offer, so I can pick products I will like.
•	As a customer I want to know what events Bere Gloria is attending, so I can go and enjoy the beer at local events.
•	As a customer I want to know where I can go to drink Bere Gloria, so I can drink Bere Gloria in the pub with friends
Design Choices
•	Pagination style with distinct pages for each section
•	Video of the product acts as a hero image as you land on the page, with the invitation to scroll to see the products in order to purchase them
•	Gold was used as one of the primary colours (#997137) as one of the key ingredients of the product is honey. This was complemented with a dark red (#631519) within the logo and graduated to black as the main background colour of the site as a nod towards the Romanian national colours; the red has been purposefully darkened as I feel this gives a more modern look, merges with the gold well and ensures the background colour does not vary drastically as it graduates to black.
•	EB Garamond is the main font family used which is well suited to large font sizes which feature throughout the page and blends well with the classic style of the monument depicted in the logo.
•	Icons are used within the navbar to accentuate the descriptions of the pages and within the optional radio buttons for the contact form to provide clarity and interactivity.
Wireframes: 
I used Balsamiq to create detailed wireframes for each page at a desktop level.
As is to be expected certain elements present in the wireframes did not make it into the project itself but may yet do so further down the line.
 
Index.html	 
About.html
 
Events.html	 
Locations.html
 
Contact.html	
Features
Existing Features
•	Navbar that fixes to the top of the screen at all times to enable user instant navigation around the. Collapses into burger menu on smaller screens.
•	Contact section with name, email and text input fields.
•	Footer at the bottom of each page that allows you to subscribe with name and email input fields
•	Events section which provides posters of events which, when hovered on, show details an event links
•	About us page which gives information about the Brewery company and the Monument it was named after
•	A locations page which provides a map of the different cities in which the product is sold at bars, with a list of those bars and direct links to google maps for each location
•	Contact details including email address (automatically opens to send mail), company address which opens to a google maps link of the location and an embedded map of the company address
•	Product section showing each of the 3 products, with details of each and a link to buy online
Features Left to Implement
•	Allow customers to book a tour of the Brewery, by having them fill out a form with date and time inputs.
Technologies Used
•	Adobe Illustrator
o	Adobe Illustrator was used to remove backgrounds from images
•	Github to host this project's respositories.
•	Gitpod IDE of choice for development.
•	Git for version control
•	Google Chrome developer tools for testing and troubleshooting.
•	Coolers for colour schemes.
•	W3C Markup Validation used to validate HTML.
•	W3C CSS validation used to validate CSS.
Languages
•	HTML to build the page.
•	CSS to style the page.
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.
Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.
For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:
1.	Contact form:
i.	Go to the "Contact Us" page
ii.	Try to submit the empty form and verify that an error message about the required fields appears
iii.	Try to submit the form with an invalid email address and verify that a relevant error message appears
iv.	Try to submit the form with all inputs valid and verify that a success message appears.
In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.
Throughout development of this project Google Chrome developer tools was used to check the styling and layout of the page.
Particular care and attention was taken to ensure the page was responsive at all screen sizes by selecting the various device models and dragging the responsive window past breakpoints.
The following tools were also utilized in the testing of this project:
•	W3C Markup Validation to validate HTML at various stages - besides one heading suggestion there are no other issues found.
•	W3C CSS validation to validate CSS at various stages - currently no issues found.
Internet browsers
The same process of opening up the live page and meticulously clicking all links, buttons, and re-sizing of windows was utilized in the following browsers:
•	Google Chrome - Main browser of choice for development.
•	Microsoft Edge - no issues encountered. Everything works as intended.
•	Mozilla Firefox - Currently no issues. Everything works as intended.
•	Safari - All working as intended besides smooth scrolling.
The site has been tested physically on a number of mobile devices including:
•	iPhone 5, 7, 10 and 11
•	Google Pixel
•	Galaxy S9.
   
Issues and Resolutions
•	During development there was a problem with changing the color of my hamburger menu from the bootstrap nav bar snippet. Upon noticing that I was successfuly grabbing the other elements I examined this further in dev tools and realised that it was because it was actually a linked image. I removed this from the code and inserted a fully customizable font awesosme icon instead.
•	When reducing the screen size down to mobile it was noticed that my price lists were becoming too squashed and displaying incorrectly. This unwanted result was avoided by using media queries to reduce the font-size and letter spacing of the text.
•	An unwanted side effect of the bootstrap form snippet was that on larger screens the input fields span the entire width of the screen. Finding a solution to this was a rather frustrating endeavour but eventually I got something that I was satisfied with by adding a smaller bootstrap col class either side of the central content, resulting in the shorter input fields and responsive re-sizing that now achieves the desired look.
Known Issues
•	Smooth scrolling on Safari is not yet supported.
•	When the hamburger menu is clicked it does not close itself once a navigation link is seleceted.
•	Video continues to play after modal window is closed. This is because it requires additional JavaScript that is not present in Bootstrap to automatically stop playback as stated here. Needs testing.
•	Background images on physical iPhone not displaying correctly as they do in dev tools. According to this Stack Overflow post the solution is to change background-attachment:fixed; to background-attachment:scroll
Deployment
Bere Gloria was developed on GitPod, using git and GitHub to host the repository.
When deploying Mambo using GitHub Pages be sure to follow these steps:
1.	Navigate to '/Magnuson95/MS1-Bere_Cu_Miere' or alternatively click here.
2.	In the top navigation click on 'settings'.
3.	Scroll down to the GitHub Pages area.
4.	Select 'Master Branch' from the 'Source' dropdown menu.
5.	Click to confirm my selection.
6.	Mambo should now be live on GitHub Pages.
In order to run Mambo locally be sure to follow these steps whilst still on Github:
1.	Navigate to '/Magnusson95/MS1-Bere-Cu-Miere' or alternatively click here.
2.	Click the green 'Clone or Download' button.
3.	Copy the url in the dropdown box.
4.	Using your IDE of choice open up your preferred terminal.
5.	Navigate to your desired file location.
6.	Copy the following code and input it into your terminal to clone Mambo.
git clone https://github.com/Magnusson95/MS1-Bere_Cu_Miere.git
Credits
Content
•	All content was written by myself or provided by the client’s original website and translated
Media
•	The product photos were taken by myself
•	The logo was designed by myself on Adobe Illustrator
•	The events logos were provided by the client’s original website and their Facebook Page
•	Index.html hero video is a royalty-free, full use license video provided downloaded from videvo
Acknowledgements
•	I received inspiration for this project from Bere Gloria’s original website, and the product card design from the Youtube Page “Online Tutorials”
