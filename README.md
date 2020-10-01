# CIS3344: Client-Side Scripting for the Web 

Please visit my website to preview all lab projects: http://cis-iis2.temple.edu/Spring2020/CIS3344_tug93819/index.html

**Note**: Code has not been posted because some labs require my database password to access Temple University's database server which students should **not** share.
* All labs can be accessed by clicking the labs tab & then by clicking on the links at the end of each lab description on the right hand side.
_______________________________________________________________________________________________________________________________________

**Lab 1 - HTML & CSS Home Page**

I made this assignment to gain some experience working with HTML, CSS, and publishing to my new website. In this assignment, I created my website that was used throughout the semester. I designed a small 4 page website using HTML and CSS.

**Preview:** This lab contains the backbone pages of my website: 

- Home - Welcome page with a description on what this website is for and some contact information.
- About Me - A little bit about me and my hobbies.
- Portfolio - Contains my resume
- Labs - Contains descriptions of each lab, including my level of experience, and what I liked/disliked about each project.                                       
_______________________________________________________________________________________________________________________________________

**Lab 2 – Responsive Web Design (Form Page with Theme)**

I made this assignment to gain some experience working with HTML, CSS, and building a Responsive Web Design that allows the site to be displayed properly on multiple screens and devices. The assignment involved implementing a “single-page design” where the page contains several “virtual pages” inside a single physical page. 

**Preview:** The theme I picked for this lab was to make a fan page about the popular sitcom FRIENDS. The page contains many sections that can which can be accessed by clicking on the tabs in the navigation bar. The page contains:
- Information about the show
- A form that asks fans’ questions about the show. Once the user has filled the form out, I will receive an email with their name, email, and the answers they selected.
- Lastly, there is a photo gallery showing the main characters in the show.
_______________________________________________________________________________________________________________________________________

**Lab 3 – JavaScript (Dating Website)**

I made this assignment to gain some experience working with JavaScript to make a Web page interactive. The assignment involved creating an interactive online dating application that displays information about the users seeking other companions.

**Preview:** A user can either select male or female to view different dating profiles. Each profile contains a description of the person and a like or pass button. Once the user likes a profile, the page will make a list at the top of the screen. The user can also pass a profile once the page displays all profiles, and pass a profile they have already liked. Lastly, the user can search profiles by state.
_______________________________________________________________________________________________________________________________________

**Lab 4 - Javascript (Dating Website - Using Local Storage)**

I made this assignment to gain some experience working with JavaScript for form validation and dynamic displays. In this assignment I modified the online dating application I created in the previous lab (Lab 3–JavaScript) and added more functionality to it.

**Preview:** The added functionality to this lab allows the user to create their own profile, preview it, and modify it. Each tab (create profile & preview/modify) validates all entries in each text box. A user can also view other profiles and search profiles by state (similar to the previous lab). Any profile that the user likes will be displayed in the Modify Likes List tab if they decide to, unlike a profile later on. Similarly, any profile passes will be displayed in the Passed Profiles tab if they would like to unpass a profile later on. All likes/unlikes and pass/unpasses are updated using local storage.
_______________________________________________________________________________________________________________________________________

**Lab 5 – JQuery, AJAX, and Web APIs (Dating Website - Using Database)**

This assignment was made to gain some experience working with JQuery, AJAX, and a Web API. I created a RESTful Web API in ASP.NET Core that was used by a client-side Web application written in JQuery.

**Preview:** This lab is the same as Lab 4 & 5 with some few changes. It uses MS SQL Server database to store login information, dating profiles already in the database and newly created profiles, and member accounts. Each member’s login will be compared with the members stored within the database. Also, all new members’ information along with their username and password will be stored in the database.A user can either type the gender or the city and state to search profiles. 

**Note:** PuTTY was used to access Temple University server remotely, this lab will **not** work if PuTTY is not running.
_______________________________________________________________________________________________________________________________________

**Tutorial/Final Project (Food Ordering Site using Svelte)**

This was a partner project. The goal of this assignment was to gain some experience doing some research, learn about new emerging technologies in client-side Web application development, and teach others about what my partner and I learned. We built a Web application that demonstrates technology topic and a step-by-step tutorial to teach others aspects of the new technology. The tutorial included code samples and explanations of terms and concepts used.

Preview: 
Project has 2 parts:
- Tutorial Page - This site contains a tutorial of the steps required for anyone that would like to make the same exact project.
- Svelte Food Ordering Page - This is the page that contains the finished product. The framework that my partner and I selected is called Svelte. We selected a food truck on Temple University's campus called Haalal and made a food odering site for it. The site includes a menu of options that the user can select from ,and as they select their food items, their bill is generated in real time. The user can then submit their order which gets saved in the university's database server. The user can also select View Past Orders to see where they are in the queue if they would like to know how many people are in front of them. 

**Note:** This site uses a Web API which needs to be running through Visual Studio along with PuTTY that was used to access Temple University server remotely. If these two
          things are not running, the orders will **not** be saved to the database and the user will **not** be able to display past orders. 
_______________________________________________________________________________________________________________________________________

**Lab 6 – Web API Research (OpenWeatherMap)**

I made this assignment to gain more experience working with JQuery, AJAX, and Web APIs, and learn about a Web API on my own. In this assignment, I did some research to learn about the Web API of my choice, and demonstrated my knowledge of using the services provided by the Web API.   

**Preview:** The page uses a Web API called OpenWeatherMap which gives users access to weather around the world. User can different tabs to search:
- Current Weather: By city
- Weekly Forecast: By zip code
- Weather by Latitude & Longitude: By latitude & longitude
- Weather In Different Languages for Specified Number of Days: User will need zip code, the amount of days they would like to see the weather for, and there preferred language by abbreviation. (The page as different language abbreviations have been listed for user to refer to.)

**Note:** The page will show validation for each input if the user enters anything incorrectly.
