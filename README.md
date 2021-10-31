# Bulk Empire
## Introduction
Bulk Empire is an online weightlifting club that offers many services such as workout advice, routines, tutorials and online personal training sessions to assist people who are motivated and interested to begin lifting weights or exercising to improve their lifestyle. Due to the nature of the global COVID-19 pandemic, the site is targeted at an audience who prefer to exercise remotely at home with the gym equipment provided to reduce the risk of being infected and to feel safer.  

![Responsive Screenshot Markup](/documentation/screenshots/ss-responsive-home-one.jpg)

[The live website can be viewed here on GitHub pages.](https://legenduzair.github.io/bulk-empire-MS1/)

## UX & Planning
## Wireframes
Before developing the website, I used Balsamiq Wireframes to design the potential layout and structure of content for each page for desktop, tablet and mobile view. The wireframes designed are listed below.

### Desktop View
- [Home page](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/screenshots/balsamiq-home.jpg)
- [Workouts page](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/screenshots/balsamiq-workouts.jpg)
- [Memberships page](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/screenshots/balsamiq-memberships.jpg)
- [Sign Up page](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/screenshots/balsamiq-signup.jpg)

### Tablet View
- [Home & Workout pages](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/screenshots/balsamiq-tablet-home-workouts.jpg)
- [Memberships & Sign Up pages](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/screenshots/balsamiq-tablet-memberships-signup.jpg)

### Mobile View
- [All pages](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/screenshots/balsamiq-mobile.jpg)

## Color Scheme
When choosing the color scheme for the website, I wanted to make sure it gave an stylish appearance that made the foreground content stand out from the background content. For this reason, I picked shades of orange, grey, white and black across the whole site using [HTML Color Codes](https://htmlcolorcodes.com/). Hex values were used when picking black, white and grey shades and the rgba color model was used when picking the shade of orange.

## Typography
There were two fonts that were used throughout the website:
 - Roboto
 - Bree Serif
Sans-serif is also listed in the CSS file as a backup to the primary fonts used. These choices of fonts were used as they complement each other very well as noted in Google Fonts.

## Features

### Regular Features
- Navigation Bar

  - The navigation bar is located at the top of the website across all pages and has an identical design for easy navigation.
  - Across the entire website, the company logo is placed on the right and the navigation links are placed on the left. These links include Home, Workouts, Memberships and Sign Up. All of these titles link to their corresponding pages for easy navigation. The company logo acts as a shortcut back to the home page.
  - The navigation bar is designed to be fully responsive across all smaller viewport sizes. For mobile/smaller sized screens, the format of the bar is adjusted to a column display where the navigation links are aligned vertically below the company logo which is centered at the top of the page. For tablets/medium sized screens, the links are horizontally aligned and are placed below the company logo which is centered at the top of the page.
  - The company logo and navigation links can be hovered over to display an orange color using the rgba color model. This specific color is used for various content on the website.  

![Nav Bar](/documentation/screenshots/bulk-empire-navbar.jpg)

- Footer

  - The footer section is located at the bottom of each web page and supplies useful contact information. It includes the relevant social media links in the format of their respective logos, that Bulk Empire is present on. 
  - These links are helpful to keep the user engaged in learning and reading more information about Bulk Empire and is also beneficial to the company by increasing social media following and recognition globally.
  - The background color of the footer is a darker variant of grey that offers visual contrast to the background color of the main section which is a lighter grey. Like the links in the header, the footer links can also be hovered over to display the same orange color.

![Footer](/documentation/screenshots/bulk-empire-footer.jpg)

### Home Page
- About Bulk Empire Section

  - The home page provides background information about Bulk Empire and a summary of the services that are offered to the user. This section is the first point of visual contact for the user so it is important that the benefits and values of joining Bulk Empire is included. The about us section will also allow the user to understand the reasoning behind the initiation of Bulk Empire due to the COVID-19 pandemic.
  - Below the background information of the company, a button is also displayed which takes the user to the sign-up form to enter a giveaway provided by Bulk Empire.
  - The home page also includes two images of individuals who are weightlifting as a visual indicator to motivate the user to initiate a change in their lifestyle.

![Home Page](/documentation/screenshots/bulk-empire-home.jpg)

  - When viewing the home page on laptops, the content is structured in a way where the images overlap slightly to fit the content on the screen without altering the layout majorly.

![Home Page-Laptop View](/documentation/screenshots/laptop-home-page.jpg)

  - When viewing the home page on mobile and tablets, only one of the two images is displayed. The choice of image was due to the high visual motivation it promotes to the user. The text and sign-up button is pushed down below the image for easy readability.

![Home Page-Mobile View](/documentation/screenshots/mobile-home-page.jpg)

### Workouts Page
- Home Workouts Section

  - The workouts page provides the user one of many weekly workout routines they can engage in using gym equipment provided by Bulk Empire.
  - The details of each daily workout are structured around a center image of an individual exercising at home. This structure allows the user to follow the workout without any confusion and the image is present to motivate the user to exercise at home.

![Workouts Page](/documentation/screenshots/bulk-empire-workouts.jpg)

  - When viewing the workouts page on smaller/medium screen sizes, the image is placed in the center of the page and the text is adjusted to be structured at the top and bottom of the image, vertically aligned.

![Workouts Page-Small/Medium Screen Size](/documentation/screenshots/mobile-tablet-workouts.jpg)

### Memberships Page
- Membership Plans Section

  - The memberships page provides details of all Bulk Empire membership plans from silver to platinum and all the benefits that are included in each one. The price is also indicated below each plan.
  - Below the membership plans, the various gym equipment provided with each plan is also listed. This is beneficial to the user and the organisation as they do not have to purchase separate equipment from another company/retailer.

![Memberships Page](/documentation/screenshots/bulk-empire-memberships.jpg)

  - When viewing the membership page on screen sizes smaller than desktop, the membership plans are structured to be pushed down to adjust to the space available on the page.

![Memberships Page-Medium Screens](/documentation/screenshots/laptop-memberships.jpg)

![Memberships Page-Small Screens](/documentation/screenshots/mobile-memberships.jpg)

### Sign Up Page
- Giveaway Form

  - The giveaway/sign up form allows the user to enter a competition held by Bulk Empire to win a free personal training session. The user is required to fill in each input field using their contact details such as first name, last name and email address. As well as this, the user will also be able to specify why they should win the giveaway and choose their favourite workout if they have one. 
  - A background image of two individuals engaged in a personal training session is displayed behind the sign-up form. This is a visual indicator to the user that Bulk Empire is determined to help its clients with reaching their fitness goals and achievements. 

![Sign Up Page](/documentation/screenshots/bulk-empire-signup.jpg)

  - When viewing the sign-up page on smaller screens, the width of the form and its content is decreased to fit the available space on the screen.

![Sign Up Page-Smaller Screens](/documentation/screenshots/signup-mobile-tablet.jpg)

### Hidden Pages
- Sign Up Confirmation Page

  - One page that does not appear on navigation bar is the sign up-confirmation page that users can access once they have entered the giveaway by completing the form.
  - A thank you for participating message is displayed on the screen. This indicates confirmation to the user that they have successfully entered the giveaway, whilst also providing information on future contests and the quality of rewards the user can potentially acquire.
  - A background image of a client and a trainee exercising together is present to display to the user the morals and goals of Bulk Empire. This is a common design element used across the website.

![Form Submit Page](/documentation/screenshots/bulk-empire-formsubmit.jpg) 

  - When viewing the form submit page on smaller screens, the text content is compressed to fit on the screen whilst still being readable.

![Form Submit-Smaller Screens](/documentation/screenshots/mobile-tablet-formsubmit.jpg)

## Future Improvements
- Media Elements
  - The current version of the website includes limited media elements such as images. It would be ideal to have more media content such as workout tutorials in the format of videos or audio players. 

- Workout Challenges and Classes Schedule
  - It would be motivating and beneficial to users wanting to join Bulk Empire to include a workout challenges and classes schedule. This could provide information on the diversity of workout classes taught by personal trainers and challenges existing Bulk Empire members have engaged in for successful personal achievements and goals. 

## Testing 
After developing the initial layout of the website for desktop/larger screens, the website went through rigorous testing utilising Google Chrome's developer tools to create a fully responsive website for different screen sizes. The site was continuously tested by applying styling and checking the application of the changes made using a live server window. Every page was organised and structured carefully from header to footer for a variety of displays:

- Desktop Computer: 1920 x 1080p
- HP EliteBook 840 G4: 1366 x 768p
- iPad Pro: 1024 x 1366p
- iPhone 5/SE: 320 x 568p

The website was also tested on devices using other browsers:

- iPhone 11 Pro Max: 414 x 896p
  - iOS Safari
- Desktop Computer: 1920 x 1080p
  - Microsoft Edge
- iPad Air: 820 x 1180p
  - Mozilla Firefox
- Laptop: 1280 x 800p
  - Mozilla Firefox

### Bugs 
- Fixed Bugs
  - When creating the sign-up button on the home page, there was a small issue with its interactivity. This was due to the button not being in its own parent element. To fix this, I placed the button inside a parent div element to position it below the company background text. 
  - After I was designing my first wireframes on Balsamiq, it was uploaded onto GitHub. However, the wireframes were not displaying properly so I had to rename the wireframes and uploaded my second wireframes file.
    - [First Wireframes File](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/wireframes/bulkempire-wireframes.pdf) 
    - [Second Wireframes File](https://github.com/legenduzair/bulk-empire-MS1/blob/main/documentation/wireframes/bulkempire-wireframes-1.pdf)
  - When designing my website to be fully responsive, I had positioned most of my content using absolute positioning which caused many issues of elements overlapping when reducing the screen size. To resolve this, I learned to utilise flexbox CSS layout to position my content the way I preferred.

## Validator Testing 
 - HTML
   - No errors were displayed when running each code through the NU HTML Checker.
     - [Home Page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Flegenduzair.github.io%2Fbulk-empire-MS1%2Findex.html)
     - [Workouts Page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Flegenduzair.github.io%2Fbulk-empire-MS1%2Fworkouts.html)
     - [Memberships Page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Flegenduzair.github.io%2Fbulk-empire-MS1%2Fmemberships.html)
     - [Sign Up Page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Flegenduzair.github.io%2Fbulk-empire-MS1%2Fsignup.html)
     - [Form Submit Page](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&doc=https%3A%2F%2Flegenduzair.github.io%2Fbulk-empire-MS1%2Fformsubmit.html)
  
- CSS
   - No errors were displayed when running the CSS code through the official (Jigsaw) validator.
     - [CSS Code Check](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flegenduzair.github.io%2Fbulk-empire-MS1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- Lighthouse 
   - For the deployed site, I generated a lighthouse report through Google Chrome's developer tools for both desktop and mobile versions.
      - Desktop Report:

      ![Desktop Lighthouse Report](/documentation/screenshots/lighthouse-bulk-empire.jpg)

      - Mobile Report: 

      ![Mobile Lighthouse Report](/documentation/screenshots/lighthouse-bulk-empire-mobile.jpg)

## Deployment
- The site was deployed to GitHub pages. The steps to deploy are as follow:
  - In the GitHub repository, navigate to the settings tab.
  - On the left, select pages from the settings options.
  - From the source section drop-down menu, select Branch and then Main.
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - [Bulk Empire](https://legenduzair.github.io/bulk-empire-MS1/)

## Credits

### Content 
- The materials found on [w3Schools](https://www.w3schools.com/) and [Stack Overflow](https://stackoverflow.com/) were used when inputting and editing HTML and CSS to my code to help me overcome any minor bugs and issues.
- The text for all of the pages on the site was created by myself. 
- The two materials used to learn and implement CSS flexbox and grid were the [Flexbox Website](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) and a series of YouTube tutorials created by [Kevin Powell](https://www.youtube.com/watch?v=hwbqquXww-U).
- The icons used on the workouts and sign-up pages were taken from [Font Awesome](https://fontawesome.com/).
- The fonts used in the implementation of the website were taken from [Google Fonts](https://fonts.google.com/).
- HTML and CSS were the languages used to write the code used to design the website.

### Media
- All images used on the website were taken from [Pexels](https://www.pexels.com/) and [Tiny PNG](https://tinypng.com/) was used to compress and optimise the images.

### Honorable Mentions
This project was completed due to the support of many individuals:
- [Matt Boden](https://github.com/MattBCoding)
- [Richard Wells](https://github.com/D0nni387)
- The code institute Slack community

