# Rolling Echoes Band Page

Rolling Echoes is a website that brings the virtual stage to life for our fictional band. This repository serves as the backstage pass to the web code that powers our official band page.

The fictional band page for Rolling Echoes is designed for fans, followers, and anyone interested in exploring the world of Rolling Echoes. It serves as an online platform where people can dive into the latest updates, music releases, tour information, and immerse themselves in the unique musical blend of country, indie rock, and singer-songwriter vibes that define the band's sound. The site is created to provide an engaging and interactive experience for individuals who appreciate the music and want to connect with the band's journey.

Visit the deployed site: [Rolling Echoes](https://elindalenback.github.io/Project1-band/music.html)

![Rolling Echoes](docs/readme_images/amiresponsiverollingechoes.png)

## Site Owner Goals for Rolling Echoes Band Page

**1. To Engage Fans:**
Provide fans with immersive information about Rolling Echoes, focusing on the band's musical journey and the unique fusion of country, indie rock, and singer-songwriter vibes.

**2. Showcase Music and Updates:**
Deliver clear and concise updates on the latest music releases, tour dates, and information about the band its the members.

**3.User-Friendly Experience**
Design a website that is easy to navigate, fully responsive, and reflects the band's style. Use appropriate colors and imagery to create an online space that resonates with the band's identity and invokes a sense of connection with the audience.

**4. Connect Fans with Local Scenes:**
Enable fans to discover local scenes by providing information about venues, events, and opportunities to experience Rolling Echoes live. Facilitate connections with the band's music beyond the digital space.

**5. Community Engagement:**
Offer a sign-up option for the Rolling Echoes Newsletter to keep fans in the loop about exclusive content and updates.

## User Experience (UX)

### User Stories

#### First-time User

- As a first-time fan, I want to understand the musical journey of Rolling Echoes and discover the unique blend of country, indie rock, and singer-songwriter vibes that define the band's sound.
- As a first-time fan, I want to navigate the band page intuitively, creating a positive and engaging experience as I explore the latest updates and music releases.
- As a first-time fan, I want to explore Rolling Echoes' content without the need to sign up or register, allowing me to get a feel for the band's style.

#### Returning User

- As a returning fan, I want to easily navigate to the latest music releases.
- As a returning fan, I want to discover upcoming tour dates and venues to plan my attendance at Rolling Echoes' live performances.

#### Dedicated User

- As a dedicated fan, I want to sign up for the Rolling Echoes newsletter to receive exclusive updates about new music, tour announcements, and behind-the-scenes content.
- As a dedicated fan, I want to contribute by sharing my experiences, suggesting ideas, and connecting with fellow fans in the Rolling Echoes community.

## Design

### Colour Scheme

I have chosen my colors to evoke a sense of the band and optimize the user experience and accessibility. The colors I've used are listed below, along with their respective placements.

- #000000 & #ffffff are used for the sites text.
- #31572c, #fe654f & # dce2aa are the main colors I have chosen, using them rotationally for backgrounds and headings.
- The green color is also used for buttons - going from shades dark to light.
- #fe654f is used in the band name logo to make a bold first impression. It is also used in the nav and icons for social media icons in footer.

Additionally, I've extracted the blue color (#baf0f9) from the header picture to maintain consistency across the music and tour pages, as well as in the footer, ensuring a cohesive overall styling.

![Color Scheme](docs/readme_images/recolor.png)

![Color Scheme Header](docs/readme_images/header.png)
![Color Scheme Header](docs/readme_images/footer.png)
**#baf0f9 color for header and footer**

### Typography

*Google Fonts fas used to import the fonts.*

For the Band Name Logo in the header, I opted for the 'Lobster Two' font with a fallback of sans-serif for versatility. This choice is consistently extended to the band members section and the 'Thank you' message in the feedback.html page. This intentional selection aims to emphasize a direct and cohesive visual connection with the essence of the band throughout the website.

![Lobster Two](docs/readme_images/lobster.png)

For the body text, I've implemented the sans-serif font 'Montserrat.' I chose a sans-serif font as it enhances readability on screens. The fallback font in this case is, of course, sans-serif, ensuring a consistent and visually pleasing presentation across various devices.

![Montserrat](docs/readme_images/montserrat.png)

## Wireframes

Wireframes were produced using Balsamiq.

 <details>

 <summary>Desktop Wireframe</summary>

![Desktop Wireframe](docs/wireframes/rolling-echoes-desktop.png)
 </details>

 <details>
    <summary>Mobile Wireframe</summary>

![Mobile Wireframe](docs/wireframes/rolling-echoes-phone.png)
 </details>

## Features

The website has 4 pages. One home page, one Tour page, one Music page, and one Thank you page. All pages are responsive and have:

A favicon in the browser tab.

![Favicon](docs/readme_images/browser-tab.png)

The home, music, and tour page also have:

The name of the band at the top of every page and a navigation bar to easily navigate on the site. On mobile devices the navigation bar is displayed as a drop down toggle. The band name also works as a link to go back to the Home page. 
  
![Header](docs/readme_images/header-nav.png)
![Header Mobile](docs/readme_images/nav-mobile.png)

A footer with icons and links to social media pages. All links opens in new tabs. 

![Footer](docs/readme_images/footer.png)

## The Home Page
The home page for Rolling Echoes displays a big picture of the band. And the first section contains an introduction to the band. 

![Homepage](docs/readme_images/home-page.png)

### The Band Members
The second section contains pictures of the band members with short accompanying text.

When hoovering over the pictures on a laptop they scale up slightly. This feature is added to keep the user engaged on the site.

![Band members and introductions](docs/readme_images/band-members.png)

### Sign Up Form
The last section of the Home page contains a sign up form where the users can sign up to a newsletter to resieve the latest information from the band.

![Sign up form](docs/readme_images/newsletter.png)

## Feedback page

When clicking the submit button on the form the site redirects the user to a feedback page. This is to keep the user infromed that their inforation has been correctly sent and improve their user experience.

![Thank you message on feedback page](docs/readme_images/feedback.png)

## The Tour Page

This page contains a short text and about the live experience with the band. 

![The Tour Page](docs/readme_images/tour-page.png)

### The Tour Dates

This section contains images of the citys where the band will performe. Each picture contains the country, city, date, venue, and time. When a picture/location is hoverd on a laptop it scales up to improve user experience and to indicate that it is a clickable link. The link redirects the user to a ticket sight.

![Tour dates - not hoverd](docs/readme_images/tour-close-up.png)
Not hovered

![Tour dates - hoverd](docs/readme_images/tour-feature-hover.png)
Hovered

## The Music Page

The Music Page first section contains a short text about the latest releases. Then it displays a video segment where the bands latest music video is supposed to be.

![Music landing page](docs/readme_images/music-landing-page.png)

### The Albums

After this there is an Albums section where the bands latest albums are displayd. The images of the albums are accompanied with a "Listen-Button" whith a link that redirects the user to Spotify.

![Album Section](docs/readme_images/album-page.png)

## Other Feauters

- The buttons change color when hoverd.
  
- The pages in the navbar have both hover and when you enter one of the pages this icon/name is then underlined and slightly changed in color. 
  
- On larger screens/laptops there is a "Scroll Back to Top" feature added in the form of an arrow. When clicked the user will be scrolled back to the top of the page. It also has a hover effect to indicate that the user is holding the mouse over something clickable.

![Scroll back to top arrow](docs/readme_images/back-to-top.png) When not hoverd.

![Scroll back to top arrow - hoverd](docs/readme_images/back-to-top-hover.png) When hoverd.
  
**The aforementioned elements are implemented to enhance user interaction and improve overall user experience.**

## Features left to impliment
Currently, the "Subscribe To Our Newsletter" form is not functioning correctly as the submitted information has no designated destination. In the future, my goal is to implement a properly working form that efficiently processes and stores the submitted data.

## Testing 

### Validator Testing

- #### HTML
  - No errors were returned when passing through the official W3C Markup Validator
    - [W3C Validator Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Faliokeeffe.github.io%2Fmindyoga%2Findex.html)

- #### CSS
  - No errors were found when passing through the official W3C CSS Validator
    - [W3C CSS Validator Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Faliokeeffe.github.io%252Fmindyoga%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

- #### Accessibility
  - The site achieved a Lighthouse accessibility score of 100% which confirms that the colours and fonts chosen are easy to read and accessible
  
![Lighthouse testing](docs/readme_images/light-house-test.png)


### Form Testing
- The form has been tested to ensure it would not submit without the required input fields being filled in (full name and email address).

### Links Testing
- All navigation links were tested manually to ensure the user is directed to the correct section of the website.
- Social Media links in the footer of each page were tested manually to ensure they direct the user to the correct page and open in a new tab. 
- All links to other sites where tested manually to ensure they direct the user to the correct page and open in a new tab.

### Browser Testing
- The Website was tested on Google Chrome, Firefox, Microsoft Edge, Safari browsers with no issues noted.
    
### Device Testing
- The website was viewed on a variety of devices such as Desktop, Laptop, iPhone 8, iPhoneX and iPad to ensure responsiveness on various screen sizes. The website performed as intended. The responsive design was also checked using Chrome developer tools across multiple devices with structural integrity holding for the various sizes.
- I also used the following website to test responsiveness:
    - [Am I Responsive](http://ami.responsivedesign.is/?url=https%3A%2F%2Faliokeeffe.github.io%2Fmindyoga%2F)


### Friends and Family User Testing
Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Fixed Bugs

#### Embedded CSS in YouTube Iframe

**Issue:** The `<iframe>` from YouTube had embedded CSS, failing the validation test.

**Resolution:** Transferred the embedded styles to an external CSS file for better organization and maintainability.

#### Button Validation Issue

**Issue:** Utilized buttons with a `<a>` link nested inside, but the validator did not pass. Attempted nesting a `<button>` within a link, but the problem persisted.

**Resolution:** After research, replaced the `<button>` with a `<span>` and added additional styling (e.g., `display: inline-block;`). This adjustment passed the validation test.

#### Header Styling

**Issue:** Attempted to decrease the size of the header, resulting in unpredictable styling issues.

**Resolution:** Adjusted the background picture to a color matching the top of the image. Implemented additional styling to ensure a seamless appearance.

### Typing Error in CSS Class

**Issue:** Made a typing error in a CSS class.

**Resolution:** Corrected the typing error to ensure proper styling and functionality.

### Known Bugs

HTML Smooth Scroll does not work on Safari browser.

## Technologies Used

### Languages

- HTML5
- CSS

### Frameworks - Libraries - Programs Used

- [Am I Responsive](http://ami.responsivedesign.is/) - Used to verify responsiveness of website on different devices.
- [Balsamiq](https://balsamiq.com/) - Used to generate Wireframe images.
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - Used for overall development and tweaking, including testing responsiveness and performance.
- [Font Awesome](https://fontawesome.com/) - Used for Social Media icons in footer and icons in nav-bar.
- [GitHub](https://github.com/) - Used for version control and hosting.
- [Google Fonts](https://fonts.google.com/) - Used to import and alter fonts on the page.
- [TinyPNG](https://tinypng.com/) - Used to compress images to reduce file size without a reduction in quality.
- [W3C](https://www.w3.org/) - Used for HTML & CSS Validation.

## Deployment

The project was deployed using GitHub pages. The steps to deploy using GitHub pages are:

1. Go to the repository on GitHub.com
2. Select 'Settings' near the top of the page.
3. Select 'Pages' from the menu bar on the left of the page.
4. Under 'Source' select the 'Branch' dropdown menu and select the main branch.
5. Once selected, click the 'Save'.
6. Deployment should be confirmed by a message on a green background saying "Your site is published at" followed by the web address.

The live link can be found here - [Rolling Echoes](https://elindalenback.github.io/Project1-band/music.html)

## Credits

### Content
All content on this site was created with AI.
- Chat GPT for text
- DALL E 2 for pictures

### Media

All images and videos were sourced from the below websites with thanks to the below amazing photographers

- [Pexels](https://www.pexels.com/)
  - Cesar G
  - Muhammed Zahid Bulut
  - Giovanni Calia
  - Esther
  - Rijan Hamidovic

- Youtube video used to display the music video feature was the amazing[
Rick Astley - Never Gonna Give You Up (Official Music Video](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

### Resources Used

- Inspiration for header with navigation bar with drop down toggle - [Code Institute](https://codeinstitute.net/)s 'Love Running Project'
- Inspiration for footer with social media icons - [Code Institute](https://codeinstitute.net/)s 'Love Running Project'
- Help and inspiration was found on [W3Schools](https://www.w3schools.com/)
- Form to subscribe to Newsletter was found on [W3Schools](https://www.w3schools.com/howto/howto_css_newsletter.asp)
- The Scroll Back To Top Arrow was created using this youtube video [DARKCODE](https://www.youtube.com/watch?v=Vef9bxTilCU)

## Acknowledgments

My mentor Jubril for his support and advice.

My fellow student Anton Eriksson
