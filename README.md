# Survival Guild

[View the live project here](https://irishbecky91.github.io/survival-guild/)

## Table of contents
1. [Introduction](#Introduction)
2. [UX](#UX)
    1. [Ideal User Demographic](#Ideal-User-Demographic)
    2. [User Stories](#User-Stories)
    3. [Development Planes](#Development-Planes)
    4. [Design](#Design)
3. [Features](#Features)
    1. [Design Features](#Design-Features) 
    2. [Existing Features](#Existing-Features)
    3. [Features to Implement in the future](#Features-to-Implement-in-the-future)
4. [Issues and Bugs](#Issues-and-Bugs)
5. [Technologies Used](#Technologies-Used)
     1. [Main Languages Used](#Main-Languages-Used)
     2. [Additional Languages Used](#Additional-Languages-Used)
     3. [Frameworks, Libraries & Programs Used](#Frameworks,-Libraries-&-Programs-Used)
6. [Testing](#Testing)
     1. [Testing.md](TESTING.md)
7. [Deployment](#Deployment)
     1. [Deploying on GitHub Pages](#Deploying-on-GitHub-Pages)
     2. [Forking the Repository](#Forking-the-Repository)
     3. [Creating a Clone](#Creating-a-Clone)
8. [Credits](#Credits)
     1. [Content](#Content)
     2. [Media](#Media)
     3. [Code](#Code)
9. [Acknowledgements](#Acknowledgements)
***

## Introduction

This comprehensive website was made to provide information regarding a fictional zombie apocalypse infecting 95% of the world's population. The target audience is the people of Ireland, one of the few remaining infection-free zones. 

<details>
<summary>Map of Infected Zones</summary>

![Map showing Infected Zones](assets/readme-files/infected-zones.png)

</details>

The idea for the site is based upon a fictional story, created by the developer. In this fictional world, COVID-19 has mutated upon coming into contact with a fungus named Ophiocordyceps unilateralis (Nicknamed the "Zombie Ant Fungus") in Southern Thailand. This combination has produced a group of infected individuals who resemble zombies with a hive mentality and a hunger for flesh. The mutation has spread to all corners of the globe save for a few infection-free zones, one of which is Ireland.

This website was made for the first of five Milestone projects required to complete the Diploma in Software development (eCommerce Applications) program at The Code Institute. 

The main requirements of this project are to build a responsive and static front-end site to present useful information to users using all the technologies learned so far, namely HTML5 and CSS3. The site is to contain no less than three pages.

[Back to top ⇧](#Survival-Guild)

## UX
### Ideal User Demographic
The ideal user for this website is:
* Current user
* New user
* Survivalist

### User-Stories
#### Current User Goals
1. As a current user, I want to see regular updates to the information and breaking news on the home page as the situation develops.
2. As a current user, I want to easily navigate through the site and access the information I require with ease.
3. As a current user, I want to easily navigate to content I have previously viewed within a small number of steps.

#### New User Goals
1. As a new user, I want to easily navigate the entire site intuitively. 
2. As a new user, I want the information I seek to be easily accessible and relevant.
3. As a new user, I want attractive and relevant visuals and colour schemes that work with the content.

#### Survivalist Goals
1. As a survivalist, I want to factually correct and relevant information.
2. As a survivalist, I want the information I seek to be easily accessible and relevant.
3. As a survivalist, I want to see instructional images and/or videos with user controls relevant to the information.

### Development-Planes
To create a comprehensive website that answers the above user stories and identifies the functionality of the site, the developer must develop all aspects of the fictional world for which the website is being created for. This includes a background story, a breaking news feed, survival information and creating a how-to-guide to defend against infected individuals.

#### Strategy
Strategy incorporates user needs as well as product objectives. This website will focus on the following target audience, divided into three main categories:
- **Roles:**
    - Current users
    - New users
    - Experienced survivalists
    - Beginner survivalists

- **Demographic:**
    - All ages
    - Irish or residing in Ireland
    - Beginner to experienced Preppers/Survivalists

- **Psychographic:**
    - Lifestyles:
        - Interest in Nature
        - Active
    - Personality/Attitudes:
        - Outgoing
        - Focused
        - Creative
    - Values:
        - Environmentally friendly
        - Sense of community

The website needs to enable the **user** to:
- Retrieve the desired information:
    - Survival/hunting/gathering guide
    - Camp building and fortification guide
    - Backpack essentials
    - Tips and techniques for defending against the Infected
    - Recommended equipment (hunting/tools/weapons/armor/etc.)
    - Report suspected cases for a referral.
    
The website needs to enable the **site manager** to:
- Gather reports of suspected cases for a referral.
- Gather entries for the competition draw.
    
With the above information in mind, a strategy table was created to show the trade-offs between what is important and what is viable with the following results.


<details>
<summary>Strategy Plane - Viability/Feasibility Table</summary>

![Strategy Table](assets/readme-files/strategy-table.png)

</details>


#### Scope
The scope plane is about defining requirements based on the goals established on the strategy plane. Using the information in the strategy plane, the identified required features have been broken into the following two categories.
- Content Requirements:
    - The user will be looking for:
        - Information on the global situation
        - Survival tips
        - Camp setup tips
        - Recommendations for equipment
        - Tips and techniques for killing the Infected
        - Backpack essentials
- Functionality Requirements:
    - The user will be able to:
        - Be able to easily navigate the site to find the information they require.
        - Be able to contact the site to report possible cases of infection.

#### Structure
The information above was then organized in a hierarchical tree structure, a site map, showing how users can navigate through the site with ease and efficiency, with the following results:


<details>
<summary>Site Map</summary>

![Site Map](assets/readme-files/sitemap.png)

</details>


#### Skeleton
Wireframes were made to showcase the appearance of the site pages while keeping a positive user experience in mind. The wireframes were created using a desktop version of [Balsamiq](https://balsamiq.com/).


<details>
<summary>Balsamiq Wireframes</summary>
    
![Site Wireframes](assets/readme-files/wireframe-all-pages.png)

</details>    


In addition to this, concept art was made using [Figma] (https://www.figma.com/) to showcase the appearance of the home page. The concept art made some improvements upon the initial wireframes with regards to layout and features. but stayed mostly true to the original design.


<details>
<summary>Figma Concept Art</summary>

![Homepage Detailed Wireframe](assets/readme-files/figma-homepage-mobile.PNG)
![Homepage Detailed Wireframe](assets/readme-files/figma-homepage-desktop.PNG)

</details>


### Design
#### Colour Scheme
Using the [Colourmind](http://colormind.io/template/material-dashboard/) colour palette generator, the colour scheme chosen is based on the colour Hazard Yellow. This is complemented by a very light green colour named Snow Drift, a light green close to Spring Rain, a red colour close to Deep Chestnut, and a medium-dark shade of cyan. The deep checstnut colour's opacity was altered to produce a lighter shade for the background (#E2DDDC).

This colour palette was chosen based on the colour Hazard Yellow, which is used on all hazardous materials and signs. The colour represents the danger presented by the infected individuals in the fictional story.

All content text is charcoal-coloured {#383838) as this colour compliments the other colours on the site while still taking into account those who may be visually impaired.


<details>
<summary>Colour Palette</summary>

![Colour Palette](assets/readme-files/colour-palette.png)

</details>


#### Typography
The typography pairing used on the site are [Open Sans](https://fonts.google.com/specimen/Open+Sans?query=open), [Special Elite](https://fonts.google.com/specimen/Special+Elite?query=speci) and [Oswald](https://fonts.google.com/specimen/Oswald?query=osw), imported from [Google Fonts](https://fonts.google.com/). A backup of Sans-Serif had been applied in case of import failure.

Special Elite was chosen for the title on the header, with a slogan underneath using the font Oswald. Oswald will be used for headings, with Open Sans being used for standard text.

#### Imagery
The selected imagery has been sourced and created from various sites. Fake news reports and Twitter feeds will feature on the home page in a news feed style setup. 

Images of "The Infected" have been sourced from a freelance concept artist, [Soufiane Idrassi](https://www.artstation.com/cgsoufiane), through the website [Art Station](https://www.artstation.com/). 

Various images, found in the [readme-files](assets/readme-files) folder, have been gathered for use across the site. These range from images of weapons to camping equipment.

[Back to top](#Survival-Guild)

## Features
### Design Features
Each page within the site has a consistent and responsive navigation system. The details of features on the site are detailed below.
- For larger screen sizes:
    - The **Header** is across the top of the page. It is not static as this would cover too much of the screen. A back-to-top button was implemented instead so users can access the navigation bar quickly.
    - The **Navigation Bar** is positioned directly below the header. The navigation bar is only used for screen sizes larger than 1200px. It is then replaced by a hamburger menu.
- For smaller screen sizes:
    - The **Navigation Bar** collapses into a **Hamburger Menu** that, when clicked or tapped, opens a sidebar which shows the navigation options.

<dl>
    <dt><a href="index.html" target="_blank" alt="Survival Guild Home Page">Home Page</a></dt>
    <dd>
        The <em>Home Page</em> is a single scroll page with the mamin content divided into two columns on larger screens, shifting into a single column on smaller screens.
    </dd>
        <ul>
            <li>
                <em>Header</em> - The header width is 100% of the screen size and is 120px high. The text is centered and coloured hazard yellow (#EED202). 
            </li>
            <li>
                <em>Introduction</em> - This text only section introduces the user to the site. 
            </li>
            <li>
                <em>Competition Banner</em> - Covering 100% of the width of the screen, the competition banner is not static and moves with the page. Clicking on the image will bring you directly to the Competition Page.
            </li>
            <li>
                <em>Content</em> - The World News section is a text only column to the left of the screen on larger screen sizes. Below this is the Twitter Feed, a heading and image only column, which is another column kept to the right of the screen on larger screen sizes. The News Feed section, a text and image column, keeps to the right on larger screen sizes. On smaller screen sizes, each section expands and becomes a single longer column. The order from top to bottom is World News, News Feed, and finally the Twitter Feed section. 
            </li>
            <li>
                <em>Footer</em> - The footer stays at the bottom of the screen at all times, on all screen sizes. Each social media link opens in a new tab. Additionally, each social media link opens a zombie related link on each respective website; eg. the Facebook icon links to [The Facebook group for The Zombie Survival Guide book](https://www.facebook.com/TheZombieSurvivalGuide/)
            </li>
            
