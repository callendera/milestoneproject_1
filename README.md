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
        * The original website is there for the user to return to when the finish with wikipedia
        * Upon scrolling down slightly the user is shown a 'Meet The Guys' section
        * The section is highlighted with pictures of each band member, a short bio for each, and a link to Read More.
        * after clicking the link to Read More each button leads the user to another seperate tab that opens each members wikipedia pages.
        * When the user is finished with each page they can come directly back to where they started the bio.
    
    * Check out pictures of the band
        * Upon making it to the landing page
        * There is a link provided in the NavBar called 'Photos'
        * After clicking that link the user is directed to the 'Photo Gallery'
        * In the Photo Gallery the pictures are displayed on a Carousel.
        * The carousel is set to slide the images on its own, but can also be manipulated to skip ahead to the next or show the previous image
        * Both options are shown using an arrow on the left and right side of the carousel.
    
    * See the band live
        * After coming to the webpage's landing page
        * The navbar gives a link to the 'Events' section
        * Upon clicking on that link you are directed to the '2019 concert dates'
        * Scroll down slightly and a timeline appears that lets the user soo the dates and places for each concert.
        * Under the place the event is being held is a link that says 'Buy Tickets!'
        * Click the link and a seperate tab will open and give the user a dirrect website to purchase tickets.
    
    * Plan a Private event 
        * There are 2 seperate routes to take to book the band for a private event 
            * NavBar
                * Upon coming to the landing page in the NavBar it gives the opton to 'Book Now' 
                * If you click on this button, it will open a Modal.
                * The screen behind the modal fades
                * There is an input field for a name, company name, email, date, time, place, and description.
                * All of these options are required except the company name.
                * When you try to send the form it will pop up notifications for the one that are left blank or improperly filled in.
                * After you have the appropriate information in each blank and you hit the book button the form will close and bring you back to the website in the spot where you left off.
            * Jumbotron
                * In the section following the timeline is a Jumbotron with an option for the user to book a private event as well. 
                * The same modal pops up there as well with all of the same functionality. 
        * reasoning for 2 sections
            * The users main goal may be to come to the site and book the event, so I made the option available as soon as you come to the landing page.
            * After scrolling throught the site for someone who may just be there to listen to music or check out pictures, booking the band may come as an after thought. so after the user looks at the event section the idea to plan an event and to book the band may be more prevelant after checking out the site.
    
    * Check out Social Media
        * If the user is there to look at the site i provided the social media links at the bottom to encourage the user to scroll the entire site to see what we have to offer
        * Upon clicking any of the 3 social media links it opens a seperate tab that leads them directly to the specific social media page.

## Manual Testing 

### Desktop, Tablet, and Mobile
All features were tested on Google Chrome, Internet Explorer, and Firefox. Mobile/Tablet features were tested on Apple and Samsung devices. Everything was tested using a wide range of screensizes.

* NavBar
    * Fixed to the top of the page so, to navigate throughout the site 
    * Appears with the intended 'red.jpg' background and font style 'Permanent Marker'
    * Displays NavBrand labeled 'The Monkees' when clicked it links back to the Landing page
    * The NavItems appear in order: Home | Music | Bio | Photos | Events
        * They have the color of an off-white until hovered over, they turn into a brighter white to match the NavBrand to let the user know it can be clicked. 
        * When any of the NavItems are clicked they navigate you to the correct place on the page.
            * Home --> Landing Page
            * Music --> Audio and Video
            * Bio --> Bio and Meet The Guys
            * Photos --> Carousel
            * Events --> 2019 Concert Dates, Plan an event
        * All NavItems displayed appear in a Navbar Toggler starting at 576px
            * The Items listed above are displayed in the same order when the toggler smoothly drops down.
            * After clicking the toggler and selecting the section the user is interested in visiting the toggler remains open until it is closed by clicking the toggler again.
    * On the right of the NavBar text appears that advertises to book an event stating 'Weddings? Holiday Parties? Book Now!'.
        * This text appears in italics and in off-white, the 'Book Now!' is in green.
        * 'Book Now!' turns to a darker green when hovered to let the user know it can be clicked.
            * After clicking the 'Book Now!' a modal opens.
            * The screen behind the modal darkens to exemplify the modal as a focal point.
        * This part of the Navbar disapears starting at 768px.
            * Making that disapear makes the navbar look better in the smaller screen sizes.
* Modal
    * The Modal is triggered after either the Navbar button or the button in the Jumbotron is clicked.
    * The Modal, like described above, appears and darkens the screen behind it.
    * The structure is as follows:
        * Modal Title 'Book Us For Your Event Today!'
        * In the top right corner there is an 'X' to close out the modal.
        * There is an input section for your Name with a placeholder that says 'First and Last', this section is required.
        * There is an input for your company name with a placeholder that says 'Optional', this section is not required.
        * There is an input section for your Email with a placeholder that says '@email.com', this section is required, and it must have the structure of a real email.
        * There is an input section for the address of the event with a placeholder that says 'Address', this section is required.
        * There is an input section for the date of the event with a placeholder that says '08/10/2019' to provide appropriate structure, this section is required.
        * There is an input section for the time of the event with a placeholder that says '12:00am EST' to provide appropriate structure, this section is required.
        * There is an input section for details of the event with a placeholder that says 'Please provide a short description of your event', this section is required.
        * At the bottom of the Modal there is a button that says 'Book'
            * If the user hits the button without filling in the blanks with the appropriate content, the modal will pop up a warning message beside the blank that needs attention.
            * After all of the blanks are filled with the appropriate information the modal will close out, then the modal will send the info to The Monkees email and the user would be notified with a confirmation email officially scheduling the event.
* Home/Landing page
    * The Home page only has a black and white background picture (monkees.jpg) of the band as a whole.
        * There are 3 different background images that change according to screen size, because the image for the desktop view wasn't as flattering on smaller screen sizes. 
        * At 992px a more size fitting back ground appears as expected.
        * At 576px a different background image appears there as well that fits the screensize better as well.
* Music/Video
    * The next section as you're scrolling is the Music and Video section
        * Music
            * There are 4 different audio control bars
            * Each bar has a title of the song above it, volume control, play/pause, skip to certain parts of the song, and a way for the user to download the audio.
            * After testing each control bar: they all work as expacted
        * Video
            * There is one video displayed on the screen, the video takes up the majority of the viewport as intended. This size adjusts well to different screen sizes.
            * The embedded video was taken for Youtube, to allow the user to have more videos pop up to let them to visit The Monkees Youtube channel.
            * The video has pause/play, volume control, and skip to different parts of the song.
            * After testing out each of these controls they worked as expected.
* Bio/Meet The Guys
    * This section displays a background image of a 1970s TV to exemplify that The Monkees got their start on a television show of the same name. The image adjusts well to each screen size.
        * Bio
            * This section give a short overview/introduction to the band. 
            * The text is white with an Opaque Overlay on the background image to make the words standout from the picture.
            * At the end of the text, there is a button that says 'read more' this allows the user to visit the band's wikipedia page in a seperate tab.
        * Meet The Guys
            * In this section there 4 pictures displaying headshots of each of the band's members with there name and a short bio attached bellow it.
            * Each bio also has a button attached to it to allow the user to visit the individual wikipedia page in a seperate tab as well.
* Photo Gallery
    * The title Photo Gallery is underlined by a block divider and another block divider marks the bottom of the carousel.
    * The carousel slides through 8 photos
    * The images needed to be resized based on the screensize. 
    * The carousel also has 'previous' and 'next' controls to allow the user to accelerate or go back throught the images.
    * Upon testing the carousel is works as expected on all screensizes. The next arrow was pressed and moved through the images in the correct order and the same was repeated with the previous wiht the same outcome.
* Events
    * In this section The title '2019 Concert Dates' is illuminated on a background with an Opaque Overlay. The image is a 1970s tour bus and the image adjusts well with each screen size.
    * After scrolling past the initial page, the Time Line appears in order of Upcoming Concerts. 
    * The timeline is arranged by date with the City and place for each concert. 
    * A link button is also placed after each place to allow the user to buy the tickets in a seperate tab. 
    * All timeline items are centered, except on Mobile view, those are placed to the left for a better UX.
* Jumbotron
    * The Jumbotron is showed on a slightly transparent background to make it stand out a bit. 
    * The heading should stand out to any user trying to plan an event. 'Planning an Event?' and then 'Book Us Today' with a button.
    * The Button opens the same Modal that is described above! 
* Contact Us
    * This section is just a series of texts giving the user a way to email, call, or mail the band.
    * Text adjusts based on differing screen sizes.
* Social Media
    * Beneath the Contact us section are 3 symbols for their social media links
    * Each one has a hover transition, when not hovered the icon is green (uniform witht the other buttons, symbols, etc.), after being hovered the icon smoothly changes to a darker green color.
    * Upon clicking any of the 3 icons the particular social link is opened into a seperate tab.

### Bugs Discovered

* Solved Bugs
    * Hidden Navbar Toggler
        * Starting at 576px the Navbar Toggler was supposed to appear, the area was able to be clicked allowing the menu to drop down, but no toggler icon would appear. 
        * initially I thought it was a Z-Index problem, upon further examination and trial-error that was discovered to not be the problem. I then realized I had added no color to the Navbar (ex: navbar-dark or navbar-light)
        * after adding navbar-dark the Toggler icon appeared and was fully functional as expected.
    * Background image cut off behind Navbar
        * I changed the height of the Navbar to reveal the cut off image.
            * Created a better UX
    * Alignment issues in Mobile View
        * After adding the Carousel, the alignment on Mobile view caused everything to be pushed to the left.
        * I used css style code:
        ```
        * {
            background: #000 !important;
            color: #0f0 !important;
            outline: solid #f00 1px !important;
        }
        ```
        This set of code blacks out the entire wesite except for images and words, it outlines everything to show what is not aligned.
        * The Viewport Width needed to be adjusted for the carousel on each screensize to prevent alignment problems.
    * CSS Grid system 
        * Initially I did not use the grid system correctly, placed containers inside of rows etc.
        * This caused a blank white space to appear at the bottom of webpage.
        * After sorting that out and replacing those containers with rows, the problem resolved.

### Further Testing

* Asked fellow students and mentor to look at my webpage on a range of devices to report any bugs found.

## Deployment

1. I logged into my GitHub
2. Navigated to my GitHub repository
3. Clicked on my 'milestoneproject_1' 
4. Beneath the repository name click the 'Settings' button
5. I scrolled down to the 'GitHub Pages' section 
6. I then selected the 'Master Branch' located under the 'Source' section
7. Finally I hit save
8. My site was published at https://callendera.github.io/milestoneproject_1/
9. After it was deployed I had to change all of the file paths to be relative rather than absolute


## Credits

### Content
* The text from the Bio section was from [The 8Notes Article Here]( https://www.8notes.com/biographies/monkees.asp) 
* The info in my Meet The Guys section was from Wikipedia articles as follows [Peter Tork]( https://en.wikipedia.org/wiki/Peter_Tork), [Davy Jones]( https://en.wikipedia.org/wiki/Davy_Jones_(musician)), [Micky Dolenz]( https://en.wikipedia.org/wiki/Micky_Dolenz), [Mike Nesmith]( https://en.wikipedia.org/wiki/Michael_Nesmith)

### Media
* The photos used in my webpage were from Google Images, and the GitHub repo provided by The Code Institute
* The audio files also came from the same GitHub repo 
* The video was taken from Youtube

### Acknowledgements
* I recieved inspiration for this project from The Code Institute's Guidlines for Milestone Project 1, 
* Anna_Lead (Slack), 
* my mentor Sandeep Aggarwal, 
* and my previous mentor Ravi Lakhotia.

















   