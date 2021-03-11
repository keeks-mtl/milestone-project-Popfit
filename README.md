# Popfit

## Goal for this project

Welcome from Popfit! This class based gym is the perfect setting to sweat and have fun in East London. On the 
site you will find relevant information you need as a visitor in an easily navigatable design. 

A intuitive user experience is important which is why users will find all the information they are looking for 
in a clear way. 

#Table of Contents
 
## UX

## User Goals

- Website with important information
- Contact info about the gym
- Form to submit your info
- A website that caters to desktop, tablet & mobile
- Visual elements that catch your eye 
- See schedule of classes & descriptions

## User Stories
- As a user, I want to easily find contact information of the gym.
- As a user, I want to find information of prices for gym services.
- As a user, I want to become a member online. 
- As a user, I want to see when there are classes to see if it fits my schedule. 
- as a user, It is important that I can navigate the website and find what I'm looking for. 
- As a user, I want the website to be easy to navigate.
- As a user, I want there to be social media links that open in separate tabs. 
- As a user, i want the website to be intuitive as they will increase the chance of my booking there. 
This site is designed for people looking for gym classes. The people who visit are looking for information on either the gym or the classes themselves.
- As  a user, I want to find the gym, so I can attend the class.
- As an information seeker, i'm looking for general information about the gym, so i can make a decision. 
- As a user, I want to know more about gym procedures

## Site owners Goals
- Attract new members.
- Differenciate my self from other gyms.
- Increase class bookings.
- Increase video traffic.

Share links to any wireframes, mockups, diagrams etc. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.
### wireframes
> - [Wireframes](wireframes/popfit-wireframe.pdf): A 5 page website.

## User Requirements and Expectations

### Requirements
- Easy to navigate by using the navigation menu
- Relevant content about classes
- Appealing visual elements
- Easy to fill forms
- Clear information about prices and classes

### Expectations
- Clear information about opening hours
- The navigation links work properly so I go where I want to go. 
- Clicking links take me to where I'm supposed to go, and social media links open in a seperate browser


## Design Choices
The gym is a fun gym that is marketed toward women, so I made my design choices to cater to a fun & femininine 
market. I attempted to create a website that felt free & fun and not too rigid. The colour choices where 
centered around [colorspace](https://mycolor.space/) to find the complementary colour palettes that worked well.

## Fonts 
I wanted a overall cohesive feeling to the website so I decided not to use multiple fonts.
I wanted something that was contemporary but also familiar so I chose a font from [Google Fonts](https://fonts.google.com/)
that was popular and noticeable. 

## icons
I chose not to use many icons in the website so that everything is clear and familiar to the user. 
Users are very familiar with the social media icons and the main navigational icons so those where
the only ones I used because they allowed less text to be written. I wanted icons that helped make 
the content more conscise and didnt' distract from the information. The most important that will 
probably be seen the most is the hamburger icon that will make navigation more simple on mobile 
devices. 

## Colours
--- describe my colour theme 
--- describe what the colours whill be used for and their hex numbers.
--- talk about colours and contrast

# Wireframes
- talk about what you used and how you went about choosing your layout.

Link - desktop
Link - tablet
Link - Mobile

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
## Navigation
- what you used and why (bootstrap & responsive)
- hamburger icon for mobile (because)
- fixed navbar ( fixed to top and always seen & easy navigation)

## Jumbotron
- 100% width
- illicit feeling of working out and images of users goals.
-responsive

## Aboutus
- information about gym 
- text to illicit imagery of being in a gym
- information about promotion

## Cards (Main info people look for)
- clear and crisp imagery
- info & links to relevant section
- responsive to devices

## pricing
- clear pricing info
- ability to make choices
- relevant info depending on pricing categories

## schedule
- info on classes clear & easy to read
- responsive to devices
- linked to information on the classes held at that time

## classes
- Allow user to get a feel of the classes and what they entail
- imagery to get a feel
- not busy

## Sign
- ability to give information 
- validation
- structured clearly

### Existing Features
- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- *gym location
- password validation
- send form details
- aria label everything
- interactive map for location
- direct payment application
- direct booking which links to database with class availabilities
- GDPR law info
- direct links and login to videos

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

### languages
- HTML
- classes
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.

### Libraries & frameworks
- Font Awesome
- [Bootstrap](https://getbootstrap.com/)
- Google Fonts

### Tools
- W3C Html validator
- w3c css validator 
- git
-gitpod
-Balsamic

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately
 believe that the site works well. Essentially, in this part you will want to go over all of your user stories 
 from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward 
 way for the users to achieve their goals.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is 
relevant. A particularly useful form for describing your testing process is via scenarios, such as:

### Navigation bar
- Make sure it's fixed at top (and why it helps)
- On every page every link should take you to where you are supposed to go. 
- on mobile devices the navbar should turn to hamburger so it's visible and drop-down menu should appear so 
sections can be chosen

- Implementation
-- what i used to make navbar & why
-- What i played around with to get it to look the way i wanted
-- what is hidden in the hamburger/mobile Implementation

-test
-- clicked on every link on every page
-- tried in different browsers

-Verdict
-- passed all the tests after fiddling

### Modals
-plan
-- wanted a modal to pop up to choose a pricing option
-- For it to be clearly laid out

-Implementation
-- bootstrap
-- no javascript yet
-- used colours that went with website so it didn't feel seperate 
-- overwrote bootstrap css to go with website

- test
-- tested modal on different devices
-- tested on different browsers
-- make sure buttons work (both submit and close)
-- make sure link works
-- make sure all required fields are required before it can be submitted

-verdict
-- the modal opened up when right button clicked
-- and the formatting worked across multiple devices

### Contact form

-plan
-- include contact form
-- clearly & logically laid out
-- crisp and not busy
-- required bits necessary
-- want form to give feedback that form was submitted

-Implementation
-- created signup.Html
-- used bootstrap
-- form styled in accordance with website

- test
-- tested form with validator and saw that label & input didn't correlate
-- made sure all required fields were filled in
-- fixed problem with radio coding so they worked correctly
-- added placeholders for Date of birth section because one main visible label
-- had to research how to make it accesible because of labelling decision
-- info not sent because has been covered in course yet

-verdict
-- form worked and looked the way i wanted accross all devices
-- isn't sent correctly yet because hasn't been covered in course

## Bugs
### section
#### Bug
#### fix


## Deployment

This section should describe the process you went through to deploy the project to a hosting platform
 (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the 
development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits
### content - media -inspiration

I have used the following websites to get info for my website

- [Accessibleweb](https://accessibleweb.com/tips-tools-tutorials/font-awesome/ )
    - How to make Fontawesome icons accesible.
- [selbekk](https://www.selbekk.io/blog/2019/08/how-to-make-your-footer-stick-to-the-bottom-of-your-page/)
    - How to get footer to remain at bottom of page when not a lot of content. 
- [Pixabay](https://pixabay.com/)
    - watercolour for safety message
- [Unsplash](https://unsplash.com/)
    - stock images for cards & headers
- [Pexels](https://www.pexels.com/)
    - stock images for cards & headers
- [Popfit Website](https://popfitmethod.com)
    - description of the classes when they had them & homepage information 

### Acknowledgements

- I received inspiration for this project from X