# My 1st Milestone Project

## Check out my website [here]( https://callendera.github.io/milestoneproject_1/)

## Objective
My 1st Milestone Project is to used to display my skills learned in the following sections: 
HTML Fundamentals, CSS Fundamentals, and User Centric Frontend Developement.

## Project Description and UX
My webpage is a band website for The Monkees (1960s Rockband). 
The main goal of the webpage is to attract fans and prospective fans, 
inviting them to check out audio and video on the site along while providing
them with the ability to book the band for private events and to come see The Monkees live on tour. 
Within the site you will see audio and video sections, a photo gallery, 
a bio of the band and its' members, upcoming concerts/tours, contact info, social media links, 
and a way for the user to book the band for events. 


The site is functional on all screen sizes allowing for a vast variety of fan base to visit the page.
My process for providing a user friendly website was based solely on making the website as simple as possible.
With The Monkees being a 1960s rock group and the growing popularity amoung young people with this style of music, 
a wide fan base needs to be focused on. The simplicity of the webpage allows for the older fans to be able to navigate smoothly, 
while the wide range of responsive design allows for the younger fan base to have easy access on any device. 

* As an old fan of The Monkees tv show and band, I want to listen to some audio and watch a video of the group, so I visit the site's Landing page and use the navbar to direct me to the 'Music' section
* I am a prospective fan of The Monkees, I want to see them live and check out their social media pages, so I visit the Events link on the Landing page and buy tickets then click on the Social Media links provided at the bottom of the page. Both social media links and the 'buy tickets' buttons take me to a seperate page so I can easily come back to the main website. 
* I am currently a fan, I am planning an event and need entertainment, in the navigation bar and at the end of the page I have the option to book the band. Both buttons open into the same modal where I can fill out a form. After the form is completed and filled out with appropriate info it will send an automatted email to The Monkees. 
* I am trying to find more information on the band itself and its members. After visiting the landing page i use the navigation bar to take me to the Bio section. There I find a short bio for the overall band and for each band member with buttons gicing me the option to read more. these links open a seperate tab so I can always go right back to the original website.
* I'd like to see some photos of the band. After visiting the landing page I can click on the Photos option in the navigation bar where im then led to a Carousel that highlights the photo gallery. The carousel slides on its own so I don't have to accelerate it manually, but I have the ability to if I want to. I also have the option to go back to the previous image.

### Original Mockup

![Original Mockup](https://user-images.githubusercontent.com/44679141/58180020-56c1ba80-7c77-11e9-90ec-4a2995a62b07.png)
 
### Revamped Mockup
 
 ![Revamped Mockup](https://user-images.githubusercontent.com/44679141/58180080-70fb9880-7c77-11e9-9a51-c0e9b527e8a2.png)
 
### Site Map

![Site Map](https://user-images.githubusercontent.com/44679141/58179881-0a767a80-7c77-11e9-89a2-ffc8b708211c.png)


## Features

### Existing Features
* Landing / Home page
    * Navbar - Includes: Band title, Home | Bio | Events | Music | Video| Photos, and an option to book a private event. It is fixed at the top of the page to allow the useer to navigate throughout the site without scrolling back to the top.
        * The 'Book Now!' link opens into a Modal that allows the user to book the band for a private event without having to leave the page or section they are curently on. Towards the bottom of the page bellow the '2019 Concert Dates' section there is also a Jumbotron with a button that also leads to the same Modal.
* Audio and Video 
    * The Audio section contains 4 audio controls linked to 4 of the band's most popular songs
    * The Video section consists of one iconic video linked through Youtube, so the user can access more videos if they would like to watch more through the same site.
* Bio 
    * Snippet of text explaining how the band came about and their start on the tv show 'The Monkees' 
        * -text taken from https://www.8notes.com/biographies/monkees.asp-. 
    * Includes a 'Meet the Guys' section with a short bio of each band member. 
        * Each part includes a 'Read More' button linked to Wikipedia pages where the text is also from.
* Photo Gallery
    * The 'Photo Gallery' section is displayed as a sliding carousel.
* Events
    * This section shows the 2019 Tour Dates displayed on a Timeline along with a button to allow the user to purchase tickets to the concerts displayed. 
* Contact Us / Social Media Links
    * The 'Contact Us' section is to allow the user a way to reach out to the band directly.
    * The social media links give the user a way to connect with the band indirectly by following them via their personal social media accounts.

### Features Left to Implement
* What's New
    * This feature would include new music, video, upcoming events and social media updates. 

## Tools/Technologies
* [Cloud9](https://c9.io/login)
    * Cloud9 hosted my Workspace for this project
* [Git](https://git-scm.com/)
    * used to push and commit any and all changes to my repository on GitHub
* [Bootstrap](https://getbootstrap.com/)
    * Provided my buttons, modal, carousel, Navbar, and basic grid structure 
* [JQuery](https://jquery.com/)
    * The project uses JQuery for DOM manipulation (Ex: Modal)
* [JavaScript](https://www.javascript.com/)
    * Bootstrap4 provided this project with certain JavaScript extensions for functionality (Ex: Modal)

## Testing
### Automated Testing
* Validation Services
    * [W3C Markup Validator](https://validator.w3.org/) was used to validate my HTML code.
    * [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) was used to validate CSS code.

### UX stories testing
* As a user I want to: 
    
    * Listen to music and videos
        * After coming to the landing page
        * In the NavBar there is an option for 'Music'
        * After clicking link I am redirected to the 'Music' and 'Video' section of the page.
        * There are 4 options for songs. Each has functional controls: Play/Pause, jump to different parts of song, volume controls, and an option to download the audio. Each works as expected.
        * There is 1 video available, appears to be a Youttube video. Has functional control: play/pause, jump to different parts of video, volume controls, full-screen option, a way to share the video, get more info on the video, and an option to watch later. All options and controls are completely functional. 
        * When the video is finished, more videos of The Monkees pop up to encourage the user to visit their YouTube channel.
    
    * Learn more about the band and its members
        * After coming to the landing page 
        * In the Navbar there is an option for 'Bio'
        * After clicking link I am directed to a bio of the band as a whole. 
        * The short bio is concluded with a link Button encouraging the reader to Read More
        * If the user clicks the Read More button it will will open a seperate tab to the wikipedia page for the monkees. 
        * the original website is there for the user to return to when the finish with wikipedia
        * Upon scrolling down slightly the user is shown a 'Meet The Guys' section
        * The section is highlighted with pictures of each band member, a short bio for each, and a link to Read More.
        * after clicking the link to Read More each button leads the user to another seperate tab that opens each members wikipedia pages.
        * When the user is finished with each page they can come directly back to where they started the bio.
    
    * Check out pictures of the band
        * Upon making it to the landing page
        * there is a link provided in the NavBar called 'Photos'
        * after clicking that link the user is directed to the 'Photo Gallery'
        * In the Photo Gallery the pictures are displayed on a Carousel.
        * the carousel is set to slide the images on its own, but can also be manipulated to skip ahead to the next or show the previous image
        * both options are shown using an arrow on the left and right side of the carousel.
    
    * See the band live
        * after coming to the webpage's landing page
        * the navbar gives a link to the 'Events' section
        * upon clicking on that link you are directed to the '2019 concert dates'
        * scroll down slightly and a timeline appears that lets the user soo the dates and places for each concert.
        * under the place the event is being held is a link that says 'Buy Tickets!'
        * click the link and a seperate tab will open and give the user a dirrect website to purchase tickets.
    
    * Plan a Private event 
        * there are 2 seperate routes to take to book the band for a private event 
            * NavBar
                * upon coming to the landing page in the NavBar it gives the opton to 'Book Now' 
                * if you click on this button, it will open a Modal.
                * the screen behind the modal fades
                * there is an input field for a name, company name, email, date, time, place, and description.
                * all of these options are required except the company name.
                * when you try to send the form it will pop up notifications for the one that are left blank or improperly filled in.
                * after you have the appropriate information in each blank and you hit the book button the form will close and bring you back to the website in the spot where you left off.
            * Jumbotron
                * in the section following the timeline is a Jumbotron with an option for the user to book a private event as well. 
                * The same modal pops up there as well with all of the same functionality. 
        * reasoning for 2 sections
            * The users main goal may be to come to the site and book the event, so I made the option available as soon as you come to the landing page.
            * after scrolling throught the site for someone who may just be there to listen to music or check out pictures, booking the band may come as an after thought. so after the user looks at the event section the idea to plan an event and to book the band may be more prevelant after checking out the site.
    
    * Check out Social Media
        * if the usert is there to look at the site i provided the social media links at the bottom to encourage the user to scroll the entire site to see what we have to offer
        * upon clicking any of the 3 social media links it opens a seperate tab that leads them directly to the specific social media page.
    
    * ANY AND ALL BUTTONS AND LINKS
        * have a hover transition that slightly change the color to a darker green (if already green) or a brighter white (if already white) when the mouse is hovered over the link or button
        * this lets the user know that is is able to be clicked 