# Welcome to Kingdom Of Shadows!

This website is designed for a [tattoo studio](https://denysrudenko.github.io/Project-1/).

## Introduction
**Kingdom of Shadows** is a tattoo studio that provides a variety of services for the clients. The owner is a talented experienced artist, who now wants to attract clients via the Internet. As we know, having a website is not a key to successful growth, but excellent presentation is. So for me as a developer, it is extremely important to define the philosophy of the business and present the work of the studio.

![website preview](assets/images/dm/1.png)

## Table of Contents 

# Table of Contents
- [1. Who will be interested in visiting the website?](#interested)
    - [User experience:](#user-exp)
    - [User Goals:](#user-goals)
    - [User Expectations:](#user-expectations)
    -	[Colour scheme and font](#color-scheme)
    - [Audio/video controls](#audio-video)
    - [Site skeleton (wireframes)](#wireframes)
    - [Introduction page](#introduction-page)
    - [Result](#result)
- [2. Features](#features)
- [3.Technologies used](#technologies-used)
- [4.Testing](#testing)
- [5.Bugs](#bugs)
- [6. GitHub](#git)
- [7. Information](#acknowledgement)
- [8. Future](#future)

  
<a name="interested"></a>
# 1. Who will be interested in visiting the website?
  [Go to the top](#table-of-contents)
* potential clients of the studio 
* people looking for inspiration and new technics 
* professionals working in the same industry 
* people, who want to learn more about the technology of tattooing 


<a name="user-exp"></a>
## 1.1 User experience 
   [Go to the top](#table-of-contents)

In the modern world, respectful businesses must have an on-line page to grow. This especially applies to the tattoo salons, because it is a number one wish for the clients to assure themselves that their expectations meet the reality. 


<a name="user-goals"></a>
## 1.2 User Goals
  [Go to the top](#table-of-contents)

My main goal during the project was creation of the strong image of the studio, creating a portfolio to back up the description and giving an overview of the tattooing process. 

<a name="user-expectations"></a>
## 1.3 User Expectations
   [Go to the top](#table-of-contents)

The website contains information about the studio, background of the artist and detailed description of the styles he uses, services available there, feedback from the clients, contact info. Here is what user is able to do within the website:
* all pages are easily accessible 
* the interface is easily navigated 
* responsive design for all screen/device sizes
* links to the messengers to contact the studio

<a name="color-scheme"></a>
## 1.4 Color Scheme
  [Go to the top](#table-of-contents)

![Home page](./assets/images/dm/2.png)


The choice of the color scheme for the website promoting a business like this plays a huge role in creating the image of the studio in the user's eyes. In this design I used Webkit to adjust colors.I styled the scroll bar and made a lot of hover effects.

Example:
* background: -webkit-linear-gradient(#bba14f, #f7ef8a, #d2ac47, #edc967);
   -webkit-background-clip: text;
   -webkit-text-fill-color: transparent;


<a name="audio-video"></a>
## 1.5 Audio-Video-Images
  [Go to the top](#table-of-contents)

Informative and qualitative content for business is one of the best ways to present the work it does. Examples of the work for tattoo saloons are the bridge between clients and business, since many people decide to attend a studio based on the already made designs. My mission was to provide visitors with high resolution pictures that can be seen and analyzed by the client making a decision. It was also important to display as many different pictures of tattoos as possible, to show diverse designs that artists can do.

What did i do?
* Each background image was edited with width and height.
* Each background image was styled with a different style.
* The text of background images were moved for the user's accessibility.

![1920px](./assets/images/background/about-us.png)

![950px](./assets/images/background/about950.jpg)

<a name="wireframes"></a>
## 1.6 Site Skeleton
  [Go to the top](#table-of-contents)

[Wireframe](https://wireframe.cc/) was used to create wireframes of the website. This was very useful as you can quickly make an example of your website.

<a name="introduction-page"></a>
## Introduction Page

### Desktop
   [Go to the top](#table-of-contents)

* Home page

![home](./assets/images/dm/3.png)

![home2](./assets/images/dm/4.png)

* Gallery page

![gallery](./assets/images/dm/5.png)

* Contact page

![contact](./assets/images/dm/6.png)

### Mobile
   [Go to the top](#table-of-contents)

* Home page

![home](./assets/images/dm/7.png)

* Gallery page

![contact](./assets/images/dm/9.png)

* Contact page

![contact](./assets/images/dm/8.png)

<a name="result"></a>
## Result

### Desktop

* Home page

![home](./assets/images/dm/home.jpg)

* Gallery page

![home](./assets/images/dm/gallery.jpg)

* About page

![home](./assets/images/dm/about.jpg)

* Contact page

![home](./assets/images/dm/contact.jpg)

### Mobile

* Home page

![home](./assets/images/dm/home1.jpg)

* Gallery page

![home](./assets/images/dm/gallery1.jpg)

* About page

![home](./assets/images/dm/about1.jpg)

* Contact page

![home](./assets/images/dm/contact1.jpg)


  <a name="features"></a>
# 2. Features
  [Go to the top](#table-of-contents)
 ### All 4 pages:

#### Header contains:
* Logo
* Social links
* Menu button

#### Social links:  
Social media links (for Facebook, Instagram and WhatsUp) are placed at the top and the bottom of each page in the header and footer. All the links open in a new tab. In mobile version the top social links are disabled by using:
* display: none;

I decided to place them there, because I was trying to make a similar design as [here](https://dribbble.com/shots/11360956--84-2-Shots-for-Practice/attachments/2973440?mode=media).

Back to home link provided at each page at the top left corner. This allows the user to access the home page in one click.



#### Navigation bar: 
Placed at the top right corner in the menu button. I read a lot of material to develop it, taken from one of the examples [here](https://freefrontend.com/css-hamburger-menu-icons/). The style of code was changed and edited for my purposes. There was a lot of work making that without JavaScript.

#### Languages:
Website contain 2 different languages:
* English
* Ukrainian

#### Drop down menu bar: 
Slided from the left side and contains :
* Home
* Gallery
* About us
* Contact us

#### Logo:
Tattoo Studio is placed on the top left corner and has an active selector which changes the color.

#### Background color:
Background color of the header is transparent.
### Home page:
- Artist image is included right below the menu bar to highlight that this website provides a tattoo sketches. 
- The page contains 3 blocks of information : "Tattoo Studio in Kyiv", "Garanties", "Feedback".
 Each block contains information about it and image/video provided.
- An external link "SCHEDULE AN APPOINTMENT" provided, so interested users can apply for a tattoo session. The link has a hover effect.


### Gallery page:
- Gallery image right below the menu bar.
- Page contains one block with 8 photos of tattoos.

### About us page:
- Gallery image just below the menu bar.
- Page contains two blocks of information.
- 1st block of information is about the artist "Alexandr Simakov"
- 2nd block of information is about "Instruments and materials"

### Contact us page:
- Page contains one block with 2 different sections.
- 1st section is a form, where the user can add his information about them and apply for a session.
- 2nd section is location information with map, address and contact details.
- If user wants to send an email they can press a link with an email.Look at the photo bellow:

![email](./assets/images/dm/10.png)
![email](./assets/images/dm/12.png)

* Unfortunately the map details I hide at mobile version due to lack of time to style and finish the project till 30th of June.

- The form use the method="POST" action="https://formdump.codeinstitute.net/"

![form](./assets/images/dm/11.png)

I made a "WhatsUp" link at the top and at the bottom page to help users to contact the artist of the studio the fastest way. If a user clicks on that link, they immediately are redirect to "WhatsUp" chat.

Look at the pictures below:

![whatsapp](./assets/images/dm/20.png)

"Open xdg-open" this means that google chrome asking you a permission
to open an application on Ubuntu/Debian operating systems.
<a name="technologies-used"></a>
# 3. Technologies Used
  [Go to the top](#table-of-contents)

* [HTML5](https://en.wikipedia.org/wiki/HTML5) (markup language) was used for structuring and presenting content of the website.

* [CSS3](https://en.wikipedia.org/wiki/CSS) (Cascading Style Sheets) was used to provide the style to the content written in a HTML.

* [Wireframe](https://wireframe.cc/) was used to create wireframes of the website.

* [Google Fonts](https://fonts.google.com/) was used to import font-family 'Krona One' into style,css file and which was used throughout the pages of the website.

* [Adobe Photoshop](https://www.adobe.com/uk/products/photoshop.html) was used to resize some of the site images and style them.

* [Font Awesome](https://fontawesome.com/) was used to import icons to the sites.

* [Chrome](https://www.google.com/intl/en_uk/chrome/) was used to debug and test the source code using HTML5 as well as to test site responsiveness.

* [Github](https://github.com/) was used to create the repository and to store the project's code after pushed from Git.

* [Visual Studio](https://code.visualstudio.com/) was used as code generator. I installed ssh for comfortable work.

* Extensions for visual studio, see the photo below:

![extensions](./assets/images/dm/13.png)


# 4. Testing
  [Go to the top](#table-of-contents)

## 4.1 Testing using tools

### 4.1.1 Google Developer Tools
I make use of google developer tools (Chrome DevTools). 

### 4.1.2 Responsive Tools

In order to make sure that design web pages are responsive, [Am I Responsive](http://ami.responsivedesign.is/) page was used to check it. 
Also checked with a mobile phone Huawei p40 lite.

### 4.1.3 W3C Validator Tools

[W3C Markup](https://validator.w3.org/#validate_by_input+with_options) was used to check for any errors with my HTML pages.

See the pictures below:

![html](./assets/images/dm/14.png)
![html](./assets/images/dm/15.png)
The HTML checker notified me an error in my index.html page at the start of the project, in short words i remember that for "section" i should use h1 - h6 headings, only "div" elements could be fine without headings. Also i had a problem in my contact-us.html with a form. I forgot to make "for" attribute in label for "subject" input. 

[W3C CSS Validation](https://jigsaw.w3.org/css-validator/) was used to check for any error within my css file. I have no errors but I have warnings because of "-Webkit ''. Like it says in the documentary over [here](https://developer.mozilla.org/en-US/docs/Web/CSS/::-webkit-scrollbar)

* ::-webkit-scrollbar is only available in Blink- and WebKit-based browsers (e.g., Chrome, Edge, Opera, Safari, all browsers on iOS, and others). A standardized method of styling scrollbars is available with "scrollbar-color" and "scrollbar-width".

which i have done all over the project with the hover effects for text, footer logos and scrollbar. I decided to keep it, but I understand this is the rule for future development. I noticed that issue at the end of the project work, so i keep that in mind.

See the pictures below:

![css](./assets/images/dm/16.png)
![css](./assets/images/dm/17.png)
![css](./assets/images/dm/18.png)
![css](./assets/images/dm/19.png)

## 4.2 Tests

My problem with the whole project was that all images were a big size. For that reason whole pages take a while to load. All depends on the user's internet speed. So the percentage of performance is highly variable.
To solve that problem read the "Future".

See the picture below:

![test](./assets/images/dm/21.png)

# 5. Bugs
 [Go to the top](#table-of-contents)

  ### Solved bugs
- The main problem for me was making the website responsive. I took a big jump ahead for developing this website. So it took a lot of time actually.
- I also discovered they use percentage for images, there is a better way to make it responsive. For the whole project I was making the property in pixels, and only at the end I changed to percentage. 
- At the start of the project I deployed the slideshow in the "Feedback" section, but when I tried to make it responsive the whole slideshow broke down.
The width was measured in pixels, using a math formula I was changing the size of the screen to make it responsive, but when I tried to change it to percentage the whole slideshow broke down.

See the gif bellow:

![test](./assets/images/dm/22.gif)

I couldn't fix it, so I got rid of it. I'm sure, for the working slideshow I needed to add overflow: hidden

- The other bugs I had were publishing Ukrainian language html files on github. There was a problem with a path. The solution for it was editing the path as "../../example/example.png" 

- I'm sure there are a lot of other bugs in my css code that I couldn't see, because of my experience of web developing. I'm sure that the whole code of css could be written in a shorter version.

 <a name="git"></a>
# 6. GitHub
  [Go to the top](#table-of-contents)

The web was deployed to GitHub pages:
- Sharing of mine profile here - https://github.com/DenysRudenko
- The live link can be found here - (https://denysrudenko.github.io/Project-1.-Tatto-studio./)

  <a name="info"></a>
# 7. Information
 [Go to the top](#table-of-contents)
### Code
* The main image above the nav bar came from the Love Running project
* The code for the menu button came from https://freefrontend.com/css-hamburger-menu-icons/ and was edited for my purposes.
* The design idea for the main image and navigation bar was taken from https://dribbble.com/shots/11360956--84-2-Shots-for-Practice/attachments/2973440?mode=media
* The design idea for pages was taken from https://www.goodkindtattoo.com/
* The icons in the footer and contact page came from [Font Awesome](https://fontawesome.com/)
* For README.md file, reference of https://github.com/dhakal79/Portfolio-project-MS1/edit/master/README.md and from my teacher in Kyiv Politehnic Insitute https://github.com/GasperPaul/university-tools-installer 
* Photos are made by Igor Nykytyn, talanted photographer https://instagram.com/igor_nik_photo?igshid=YmMyMTA2M2Y=
* Help with a photo designs Anton Skokivsky https://instagram.com/a.skokivskyi?igshid=YmMyMTA2M2Y=
* A big thank you to mentor Marcel Mulders for tips and for supporting a project I made.


<a name="#future"></a>
# 8. Future
[Go to the top](#table-of-contents)

### Web Security
* There is need to make some security analysis, in order to put in on the internet.

### Loading
* The problem with a big picture weight could be fixed by loading animation at the start with a help of JavaScript.

### Chat
* The great idea is to add a live chat menu box.

### Animations
* There could be nice animations with photos.

### Parcing
* Should be created a file with information about parcing for other developers.

### Font style
* There could be more improvements with a font and also added font for Ukrainian language.



  











