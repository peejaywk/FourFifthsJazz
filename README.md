# Four Fifths Jazz Ensemble

[Visit Website](https://peejaywk.github.io/FourFifthsJazz/)

![alt text](/assets/images/am-i-responsive-capture.png "Responsive design image")

This is a website for a fictitious jazz ensemble called Four Fifths Jazz who is based in the UK. Four Fifths Jazz is a small ensemble consisting of five 
members who as well as writing and performing their own music cover most of the popular jazz repertoire. The main aims of the website are:
* Promote the latest single
* Encourage visitors/fans to book tickets to their upcoming concerts
* Advertise that the ensemble is available for weddings / parties / corporate events and other private functions
* Allow visitors/fans to learn more about the ensemble 

The name and members of the ensemble have been created solely for the purpose of this project and are entirely ficticious.

## Table of Contents

[User Experience (UX)](#userexperience)

[Features](#features)

[Technologies Used](#technologies)

[Testing](#testing)

[Deployment](#deployment)

[Credits](#credits)


<a name="userexperience"></a>
## User Experience (UX)

* User Stories
    * As a new user, I want a clear layout so I can easily navigate the site.
    * As a new user, I want to read about the band and their infuences to get a better understanding of who they are and what music they perform.
    * As a user, I want to see when the band are next playing to I can easily book tickets.
    * As a user, I want links to the band social media accounts so I can easily stay up to date on any news.
    * As a user, I want links to any music released on popular streaming platforms so I can listen to their music in my own time.
    * As a potential client, I would like contact information so I can make enquiries about booking the ensemble.
    * As a potential client, I would like to see a typical set list so I can see if it would be suitable for my event.
    * As a band member, I want to promote our latest single to increase the number of downloads/listens on Spotify.
    * As a band member, I want to advertise up coming concerts to increase sales of tickets.
    * As a band member, I want to promote the band for private hire to increase bookings.

<a name="features"></a>
## Features

### Common Features Across All  Pages

* Header
    * The header will be in a fixed postion at the top of the screen and will not scroll with the page contents. This allows visitors to easily navigate the site even when they have scrolled to the bottom of a page.
    * The header will include links to all the site pages (Home, About & Contact). These will be positioned to the right of the logo.
    * On hovering over the navigation links with the mouse they will change colour indicating to the user that they are clickable (desktop only).
    * On mobile devices the navigation links will collapse into a hamburger menu.
    * The logo for the ensemble will be positioned to the left and it will also be a link back to the home page.
    * The colours have been chosen to compliment the hero image on the main page.
    * On the right hand side of the header there will be a 'bookings' button that users can click if they want to book the ennsemble. To attract the attention of the user this will be a bold colour.
* Footer
    * The footer will be located at the bottom of each page and will scroll with the page contents.
    * A disclaimer will be positioned to the left of the footer stating that this website is for education purposes only.
    * Social media links and other contact information will be positioned to the right of the footer.
    * Social media links will be represented by icons for each site and will increase in size when the user hovers over them.

### Individual Page Features

* Home Page
    * The top two thirds of the page will feature an image of the ensemble. Over the image and positioned top the top left will some text and a link promoting the ensembles latest release on Spotify.
    * Below the image and positioned on the center of the page will be a brief description of the ensemble detailing who they are and what they have to offer to potential clients.
    * At the bottom of the page will be information on any upcoming concerts. These will be split into individual containers and will reposition depending on the viewing device.
* About Page
    * At the top of the page will be another image of the ensemble. The aim is to attract the users attention to encourage them to read more about the ensemble.
    * Below the main image will five sections providing the user will all the information they need on the enseble. These sections are:
        * About Us - A more detailed version of the text on the home page.
        * Ensemble Members - A bried statement from each member saying who they are etc.
        * Influences - Aims to give the users a sense of the type of music they can expect from the ensemble when considering them for a booking.
        * What We Do - A sales pitch detailing services offered (Concerts/Weddings/Parties/Corporate Events)
        * Set List - Typical set list
* Contact Page
    * At the top of the page will be some instructions of how to contact the enseble. This will be via the form displayed on the page or via the email link provided.
    * The contact form will be below the text and will ask for the users contact details and a description of their enquirey.
    * Below the form will be a sumbit button.
    * This page can also be accessed by clicking on the 'booking' button located in the main header.

<a name="technologies"></a>
## Technologies Used 
* This website uses HTML and CSS programming languages.
* [Bootstrap 4.5.3](https://getbootstrap.com/)

<a name="testing"></a>
## Testing

### HTML Validation
To validate the HTML the online [W3C Markup Validation Service](https://validator.w3.org/) was used. Each of the three pages was tested using this online tool.

#### Home Page ([W3C Validation Report](assets/documents/testing/HomePageNu-HtmlChecker.pdf))
On first testing the home page the validation tool came back with some warnings regarding possible misuse of the aria-label. 
On investigation the label was in the wrong element - it was in the *i* element used for the Font Awesome icon instead of the *a* element for the social media link. Moving the aria-label into the correct element removed the warning when the page was checked a second time.

The validation tool also highlighted an empty heading - this heading was removed from the code.

#### About Page ([W3C Validation Report](assets/documents/testing/AboutPageNu-HtmlChecker.pdf))
Contained the same warnings as seen when testing the home page - the footer code was common across all pages. Applied the same corrections as detailed above.

#### Contact Page

### CSS Validation

<a name="deployment"></a>
## Deployment
This project was developed using [GitPod](https://gitpod.io/) with [Github](https://github.com/) used for version control and deployment.

The instructions below detail the steps to deploy this website to GitHub pages:

1. Login to [Github](https://github.com/)
2. Select **peejaywk/FourFifthsJazz** from the list of repositories.
3. Select **Settings** from the menu near the top of the screen.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** select the **Master Branch** from the drop-down menu.
6. The page is automatically refreshed on selecting Master Branch. The website is now deployed to Github pages.
7. Scroll back down to the **GitHub Pages** section and copy the link to the deployed website. **Note:** it can take several minutes for the site to be deployed by GitHub.


<a name="credits"></a>
## Credits
### Code
Bootstrap navigation element

### Media
* Unsplash [Home Page Background Image](https://unsplash.com/photos/VAu2j8My3-0). Credit: [Sam Browne](https://unsplash.com/@samjbrowne)
* Unsplash [About Page Background Image](https://unsplash.com/photos/xj7l5o8bTzI). Credit: [Sam Browne](https://unsplash.com/@samjbrowne)
* Unsplash [About Page - About Us Image](https://unsplash.com/photos/k4MQU76YTUI). Credit: [Sam Browne](https://unsplash.com/@samjbrowne)
* Unsplash [About Page - About Us Image](https://unsplash.com/photos/bjgMU-viIzA). Credit: [Alasdair Elmes](https://unsplash.com/@alelmes)
* Pixabay [About Page - Ella Fitzgerald](https://pixabay.com/photos/ella-fitzgerald-portrait-1946-1275553/)
* Iconspng [About Page - Louis Armstrong](https://www.iconspng.com/image/48640/louis-armstrong)
* Wikipedia [About Page - Dinah Washington](https://commons.wikimedia.org/wiki/File:Dinah_Washington_1962.jpg). Credit: Associated Booking Corporation/photo by James Kriegsmann, New York
