![Snowdonia Cottage Breaks](/assets/readme-images/sb.PNG)

![Snowdonia Cottage Breaks](/assets/readme-images/mockup.PNG)

# Snowdonia Breaks

This website is intended to provide a captivating user experience for prospective customers of a holiday cottage based in Snowdonia, North Wales.  This in turn should lead to frequent conversions for our client Snowdonia Breaks.   

The goal is to showcase the product in its best light to attract the maximum number of guests.  The website seeks to do this by providing a minimal and natural look, yet with a strong presence and demonstration of the holiday experience.

----

# UX
## Who is the audience?

Individuals who are seeking self-catering accommodation in Snowdonia, North Wales.   Typical customers include groups of hikers/climbers, people who want to book a break and those who wish to explore what Snowdonia has to offer.   As a holiday cottage this property will have extra appeal for those actively seeking a traditional holiday cottage that can sleep up to 14 guests.

## The site owner

The owner seeks to obtain the maximum number of conversions to fill out the annual booking calendar.  The owner wishes to develop the brand image and increase demand for their accommodation.   The owner wishes to obtain contact details of site visitors in order to form a mailing list.  

## Typical user stories to expect:

1.  As a member of a climbing group, I want to find suitable accommodation on the 1st of May that can house 8 climbers.  It needs to be within our budget and the hope is for the overall trip to be a memorable one, with some interesting facilities local to the accommodation.  The hope is that this will make it a good proposition for all, be able to relax properly at the end of each day which will add value to our climbing trip.

1.  As a family of 5, we are looking for an ideal getaway for half term.  We’d like the children to be able to have fun outside the accommodation, with plenty to do in the area.  As parents we wouldn’t mind a bit of luxury either.  This would make it a family break to remember.

1.  As a retired couple we are looking for a self-catering cottage to spend a couple of weeks relaxing and exploring the Snowdonia region.  We would like to book something tonight so that we can plan for the getaway therefore we would like to check availability and make a reservation.

1.	As a customer looking for a suitable accommodation to host my husband’s 60th birthday party in a private setting.  I would like to hear of any experiences others have had before committing.  We would like to bring as many people as possible and would like to be able to cater for them all.  We also have a number of other requirements, so I’d like to be able to contact the owner before placing a booking. 


There seems to be a significant variance in the potential stories that we can expect.  This suggests that we should try to maintain some neutrality while focusing on the service itself and the value propositions of it.  

## The Strategy Plane

We wanted this website to showcase the accommodation in its best light to help the audience visualise the holiday experience.  This will require little distraction from the product and focus on aiding visualisation of the experience.  A call to action will need to be intuitive and readily available for the users at any given point during their exploration of the website.   

Website user objectives:

* Find the ideal destination for their holiday that meets the group’s needs.
* Secure accommodation within their budget, in the dates required.
* See description and photographs of the accommodation facilities.
* Find out more about facilities and special interests local to the accommodation.
* View previous guest experiences
* Contact the accommodation owner

Website owner objectives: 

* Obtain maximum number of conversions to fill up the booking calendar
* Build an online presence.
* Increase brand awareness and demand for the property.  
* Obtain contact details of site visitors to form a mailing list.

Feasibility chart:

![Feasibility chart](/assets/images/feasibility-chart.png)

The project appears to lack in feasibility in some areas, I’d attribute these to current time constraints and capacity to deliver on some (Accessibility, SEO, demonstrating availability, increasing brand awareness).  Overall the project has a good viability score so we should be able to deliver on the key objectives.

## The Scope Plane

I have decided to include these features as priorities:

*	Navigation bar across the top with internal links 
*	Home page with hero image and accommodation overview
*	The Cottage page with descriptions and gallery features
*	The Local Area page with summary of local attractions and a location map
*	Contact/booking page to contact the owner and/or place a booking/check availability. Option to receive promotional emails when entering email into contact form.
*	Footer to include social media links
*	Prominent call to action available on each page to contact owner, or place booking.

## The Structure Plane

The header is to include a navigation bar to the following internal pages:

*	Home
*	The Cottage
*	The Local Area
*	Contact Us

The navigation bar will also include a Book Now option which will take the user to an external bookings platform.

The header will also include a Snowdonia Breaks logo on the top left.

### Home

The home page will include a hero image along with a centered title with caption placed onto the hero image.  Below the hero image there will be a 3 column layout to prompt the user to proceed to 1. The Cottage page, 2. The Local Area page, 3.  The Contact/bookings page.

### The Cottage

This will provide a description of the features of the accommodation, supported by gallery elements.  The gallery elements will be a combination of static images and a carousel. 

### The Local Area

This will be modelled from the structure of the Cottage page, but will include an overview of some local attractions supported by gallery elements. 

### Contact Us

This page will feature a form to contact the owner to make an enquiry, with the option to opt in to promotional emails when supplying their email.  A book now button will also be prominent on this page and will direct the user to an external bookings platform. 

## The Skeleton Plane

Here are the initial wireframes produced for this project:

[Landing page - desktop and tablets](https://github.com/D-Lawson/milestone-project-1/blob/7e9481273f52e128f77a4f526c4b049397f54257/assets/wireframes/sb-desktop-tablets.png)

[Landing page - mobile](https://github.com/D-Lawson/milestone-project-1/blob/7e9481273f52e128f77a4f526c4b049397f54257/assets/wireframes/sb-mobile.png)


## The Surface Plane 

Here are some of the styling rules that has been defined to date: 

### Fonts/typography

**Nanum Myeongjo bold 700** from Google Fonts has been identified as suitable for h1 headings throughout this project.   

### Colours

A hex colour of #16293F has been identified as suitable for headers, footers, fill colours within containers.

Hex colour #D6C37F has been identified as suitable for body text.  Also for the main logo font text.  A white/light colour shall be used for other headings.

It is to be ensured that other colouration is compatible with the above colours.

### Buttons

Generic bootstrap buttons have been deemed suitable, providing that the styling is overridden using the colours that are compatible with #16293F

----

# Features

## Existing Features

*	Nav bar containing navigation button elements and business logo.  The navbar uses bootstrap classes and also some custom CSS.  A logo was crafted using relative positioning to the text.  The navbar contains a toggler button that allows the user to navigate on mobile, a Book now call-to-action button at all times with a fixed header so that the user can book at any point.  Book now button refers the user to an external booking platform.
*	Hero image with a bootstrap jumbotron added for the callout information. Call to action button (Book Now) visible within the jumbotron.  Some graphical elements placed with precision within the callout for a bespoke design.  Callout with transparent background to partially see the hero image.
*   Section for Cottage overview containing two bootstrap grid columns, one with a jumbotron for text with a header and FontAwesome icon, one container for an image adjacent. Custom CSS applied for styling and responsiveness.
*   Section containing accommodation features in a single column with an unordered list, wrapped around a testimonial image floated right.  Custom CSS applied with red coloured bullets for the list.
*   Section for The Local Area containing two bootstrap grid columns with a jumbotron in each column, one for text and one for an image adjacent. Custom CSS applied.
*   Contact Us section containing a call to action to check availability and Book Now. Contact form inserted with modal popup upon submit to thank for the response.  Background image placed within the form container.
*   Bootstrap Scrollspy deployed to highlight the active section in the nav bar. Deployed bootstrap JavaScript to enable this.
*   Video embedded via YouTube iframe containing an example of the Snowdonia experience.
*   Footer section containing additional contact information and also social media links.
*   Elements made responsive throughout.
*   Meta tags inserted for description, keywords, author, theme-color for search engine optimisation.

## Features Left to Implement

*   Image carousel to be inserted once enough images can be obtained from the owner to form a carousel gallery feature.
*   Location map to be embedded with a Google maps iFrame
*   New navigation item that links to additional information in a separate scrolling page about the cottage, the local area special interests, local history links to local attractions websites. 

----

# Technologies Used

*   GitHub was used to host my repository and deploy the website onto Github Pages.   GitPod was used as a workspace to develop the website.
*   Google Chrome was used as my primary browser for the development, including Dev Tools and Lighthouse. I used chrome on android mobile to aid development of responsiveness.
*   [Bootstrap](https://getbootstrap.com/docs/4.6/) version 4.6 used for Nav, Jumbotron, some styling, and a button.
*   FontAwesome version 5.15.3 is used for the logo icon, scroll down icon, heading icons and contact icons.
*   Google Fonts to import font styles into the CSS.  The CSS2 API was used.
*   Javascript and jQuery bootstrap library used to deploy the bootstrap Scrollspy
*   Adobe XD was used to produce the wireframes.
*   Adobe Photoshop was used to manipulate some images and graphical elements
*   Favicon.io was used to generate the page icon set
*   [A11Y](https://color.a11y.com/) was used to test colour contrasts for sufficient accessibility.
*   [Optimizilla](https://imagecompressor.com/) was used as it allowed me to choose the degree of compression to be applied.
*   The W3C validation tools were used to validate HTML and CSS

----

# Testing

## Testing against user stories:


1.  As a member of a climbing group, I want to find suitable accommodation on the 1st of May that can house 8 climbers. It needs to be within our budget and the hope is for the overall trip to be a memorable one, with some interesting facilities local to the accommodation. The hope is that this will make it a good proposition for all, be able to relax properly at the end of each day which will add value to our climbing trip.
    1. The The call-to-action link can take the user to an external booking platform checkfront.com to check availability and also the prices for the desired dates.  There are references to the local mountain range and walks in the local area.   A list of facilities is clear within the accommodation section with photographs to demonstrate the environment they will be able to relax in at the end of a busy day.  They have the option to receive promotional emails in the future if they decide to re-visit the area and wish to seek discounted offers.

1.	As a family of 5, we are looking for an ideal getaway for half term. We’d like the children to be able to have fun outside the accommodation, with plenty to do in the area. As parents we wouldn’t mind a bit of luxury either. This would make it a family break to remember.
The website states how many beds capacity it has and a descriptions of the facilities, photos of the accommodation, reference to a children’s play area and things to do locally.   There is reference to the luxury aspects of the accommodation.  The user gets a choice of placing a booking or contacting the owner with any queries. 
    1. The website states how many beds capacity it has and a description of the facilities, photos of the accommodation, reference to a children’s play area and things to do locally.   There is reference to the luxury aspects of the accommodation.  The user gets a choice of placing a booking or contacting the owner with any queries. 

1.	As a retired couple we are looking for a self-catering cottage to spend a couple of weeks relaxing and exploring the Snowdonia region.  We would like to book something tonight so that we can plan for the getaway therefore we would like to check availability and make a reservation.
The website features things to do locally in Snowdonia and also a great illustration of the Snowdonia experience in the embedded video.   There is a prominent call-to-action button so that the user can check availability and book their holiday immediately at any point during their viewing of the website.
    1. The website features things to do locally in Snowdonia and also a great illustration of the Snowdonia experience in the embedded video.   There is a prominent call-to-action button so that the user can check availability and book their holiday immediately at any point during their viewing of the website.

1.	As a customer looking for a suitable accommodation to host my husband’s 60th birthday party in a private setting.  I would like to hear of any experiences others have had before committing.  We would like to bring as many people as possible and would like to be able to cater for them all.  We also have a number of other requirements, so I’d like to be able to contact the owner before placing a booking. 
The website features the number of bed capacity and also references a testimonial from a customer.  The user can also access social media accounts to further assess the suitability of the accommodation.  They want to cater for a big group and the website references the facilities in detail and demonstrates its capacity to cater for a big group.  The contact form will allow them to contact the owner with any queries they have and can contact them directly.
    1. The website features the number of bed capacity and also references a testimonial from a customer.  The user can also access social media accounts to further assess the suitability of the accommodation.  They want to cater for a big group and the website references the facilities in detail and demonstrates its capacity to cater for a big group.  The contact form will allow them to contact the owner with any queries they have and can contact them directly.

## Manual testing procedures

My manual testing procedures for this project were as follows:

1. #### Test on different browsers at different screen widths for responsiveness – Chrome, Chrome for Android, Samsung Internet Edge, Firefox

##### Website tested on all these browsers and was satisfied that it resembled the intent when developing on Chrome desktop.  I adapted the screen width manually on the desktop browsers to seek anomalies and I also used the scaling tool on DevTools; I was satisfied that there are no events that can affect the user experience.  The mobile browsers Chrome and Samsung were also consistent with the intent at the development stage.   

2. #### Functional testing of the website link buttons, form and video embed

##### All website features tested after deployment and they functioned as intended.  Links were live and opened in new tabs, the form submission returned successfully from the Code Institute form service and also activated the ‘thank you’ modal.   The video embed plays as intended and is responsive.

3. #### Check the problems tab in GitPod workspace

##### Back end anomalies reported. No relevant problems.

4. #### Test with Devtools Lighthouse

Lighthouse desktop report came out favourably:

![LH Desktop report](/assets/readme-images/lh-desktop.PNG)

Recommendations for best practices are related to external library dependency:

![LH Desktop best practices](/assets/readme-images/desktop-best-practices.PNG)

Lighthouse mobile report came out with actionable recommendations.  The unused CSS also seemed to be external:

![LH mobile recommendations](/assets/readme-images/ih-mobile.PNG)

![LH mobile report](/assets/readme-images/mobile-performance1.PNG)

Images were reduced further upon recommendation although they had already been compressed.  This resulted in a slight improvement in the performance score.

![LH mobile correction](/assets/readme-images/ih-mobile-2.PNG)

![LH mobile correction2](/assets/readme-images/mobile-performance2.PNG)

Recommendations for mobile best practices were also related to external library dependency:

![LH mobile issues](/assets/readme-images/mobile-best-practices.PNG)

5. #### W3 Validation tool for HTML

The HTML validation tool returned with two warnings that are not relevant in the context of the page:

![W3 Validator HTML report](/assets/readme-images/w3-html.PNG)

6. #### W3 Validation tool for CSS

The CSS validator returned 2 errors and many warnings associated with external library dependency:

![W3 Validator CSS report](/assets/readme-images/w3-css.PNG)

7. #### A11Y Color Contrast Accessibility Validator

Addressed two color contrast issues into compliance:

![A11Y Correction 1](/assets/readme-images/colour-contrast1.PNG)

![A11Y Correction 2](/assets/readme-images/colour-contrast2.PNG)


## Other testing considerations

In relation to x-small screens there has been an ok result on normal browsers but the callout section has somehow rendered differently on some third party web apps such as http://ami.responsivedesign.is/

----

# Deployment

The website has been deployed using GitHub pages with the master branch of my repository.  I used the following settings:

![Pages Deployment](/assets/readme-images/github-pages-deployment.PNG)

----

# Credits

## Content

* Text content obtained from snowdoniabreaks.co.uk at the approval of the website owner

## Media

* Several images obtained from snowdoniabreaks.co.uk at the approval of the website owner
* The Dinas Dinlle image was taken by myself.
* Snowdon image obtained from stock photograph website [Free Images](https://www.freeimages.com/photo/snowdon-yr-wyddfa-1377605)
* The hiker graphic in the callout was obtained from stock photograph website - [Nice PNG](https://www.nicepng.com/maxp/u2q8o0w7q8w7w7r5/) 
* The trees graphic in the callout was obtained from stock photograph website- [Pixabay](https://pixabay.com/vectors/palm-trees-beach-silhouette-5733403/) 
* Snowdonia video obtained from [YouTube](https://www.youtube.com/watch?v=4yf-axuPuLo) 
* Lake image for the form background obtained from [Pixabay](https://pixabay.com/photos/lake-reflection-mountains-panorama-1616160/)

## Acknowledgements 

* Code Institute's LMS provided me with a great foundation to the way I have approached this project. I made use of teachings from UX to coding.
* A README structure template provided by Code Institute was followed to structure this README file. 
* My mentor Guido Cecilio for providing me with feedback with layout options.  Also for prompting me and assisting me to upgrade my version of Bootstrap, Javascript and jQuery for wider use of classes, and on the deployment of the textarea element to replace an input element within the form.  Feedback on general coding good practices and cleanliness of code.  Adapting the imported iframe code to include an attribute for improved video responsiveness. Assisting me to correct the structuring of relative directories after deployment of the website.
* General bootstrap documentation for classes and their behaviour
* Code snippet used to inspire my colouring of bullets from [W3 Schools](https://www.w3schools.com/howto/howto_css_bullet_color.asp)
* Followed instructions to deploy Scrollspy from [W3 Schools](https://www.w3schools.com/bootstrap/bootstrap_scrollspy.asp) 
* Followed instructions to centre the modal popup from [StackOverflow](https://stackoverflow.com/questions/39627549/how-to-center-modal-to-the-center-of-screen )