# Title
Purpose:

Aim:

![Responsive Mockup](./assets/images/readme/responsive-mockup.jpeg)

## 1. Design and Development

For the design of this website, the 5 pillars of User Experience Design (UXD) were used to cover the strategy, scope, structure, skeleton and surface to make sure the design is intuitive, simple and enjoyable.

### 1.1 Strategy

The target user audience…

Interviews and workshops with users and stakeholders were conducted to understand their requirements and perspectives.

Research was conducted …

### 1.2 Scope

From the research and interviews conducted with the target audience and stakeholders, user stories were created to determine the flow of the app. The focus was put on the following user stories:

![User Stories 1 - 3](./assets/images/readme/user_story_1_2_3.jpeg/)
![User Stories 4 - 5](./assets/images/readme/user_story_4_5.jpeg/)

### 1.3 Structure

From the user stories, content, data, features and functionality can be determined.

**For the content:**


**For the data:**


**For the features / functionality:**


### 1.4 Skeleton

When the structure of the app, information and features had been determined, a wireframe for each view could be created:

![]()

### 1.5 Surface

**Colour Palette**

![Colour Palette](./assets/images/readme/readme-color.jpeg)

- The website's primary colours are (from left to right) #13443E, #EFEFEF, #F4D1AF and #E86E4C as seen in the picture above. They were derived using the online tool [colormind](http://colormind.io/), to make sure they complement and contrast. The colors are all nuances of green or orange, to mirror nature and enhance the connection with the being green.
- #13443E is used for headlines and text throughtout the quiz, unless a hyperlink, and as a border colour to emphasise buttons or sections of text. On hover and selection, all buttons turn the colour #13443E to show they are active. It is also used, in conjunction with an opacity of 0.5, as an overlay when the instructions pop-up is active.
- #EFEFEF is used as the main background colour for the webpage, the instructions pop up and on buttons. On selection or hover on buttons, the text is changed to #EFEFEF to contrast with it's background.
- #F4D1AF is used as a contrasting background color for the question and results sections.
- #E86E4C is used minimally to highlight links away from the quiz. It is a brighter colour to contrast with the green.

**Typography**
- Quicksand is used for headings and header elements. The fallback font is sans serif.
- Dosis is used for all other text elements including paragraphs, button labels, lists, etc. The fallback font is sans serif.
- Both fonts are from Google Fonts.

## 3. Features

### 3.1 Existing Features

The features deployed for this website are as follows:

<insert feature descriptions and images>

### 3.2 Future Features

In addition to the features deployed, some features that could be deployed in a future release are:
- <list future features>

## 4. Testing

### 4.1 Initial Developer Testing

<introduce developer testing>

The development of this app was conducted on Google Chrome, therefore extensive testing was conducted on this browser. This was used as a benchmark against Firefox and Safari.

The elements of testing conducted on each browser are:
<insert list of testing performed and why - see example below>
- User Experience - what does the quiz look like; is the flow through the quiz the same; are all elements where they are expected?
- Functionality - do the buttons work as expected; does the question counter count?
- Performance - how responsive is the site?
- Other - this includes spelling and grammatical errors.

The user experience is consistent on Chrome, Firefox and Safari. The instruction videos in Safari do not load - this bug has been captured.

Responsive design is important, CSS code had to be amended and adjusted to make sure the app could work on a number of devices. There were a number of user experience bugs that were produced when testing. These have now been fixed in the code.

### 4.2 Validator Testing

Using tools such as W3C validator, Jigsaw and Lighthouse gives visibility of any code, scripts or elements that are causing any errors. The results for the site are as follows:

**HTML**
- <insert report number> errors were returned when passing through the official [W3C validator](<insert link to report>)

**CSS**
- <insert report number> errors were found when passing through the official [(Jigsaw) validator](<insert link to report>)

**Performance**
- Results can be seen through the official [Lighthouse](<insert link to report>) report.

As part of the performance test through Lighthouse, some changes were made:
- Accessibility (aria-label) tags were implemented on all buttons to improve the score from 82 to 100.
- The cache policy was amended to increase the length of number of seconds the browser should cache the resource.
- The image file sizes needed to be compressed so reduce the impact on performance. This was successfully done using [tinyPNG](https://tinypng.com/).

### 4.3 User Testing
This app has been tested by a small group of 5 users in which some feedback was captured in the design and some errors in functionality and spelling were corrected.

UI improvements made:
- <list any improvements to UI that were made here>

Errors / bug fixes:
- <list errors/bugs that were found, what the problem was and how they were fixed>

### 4.4 Unfixed Bugs

- <list unfixed bugs here>

## 5. Deployment

This website was deployed using GitPages and following the below steps:

GitHub pages deployment
1. Log in to GitHub
2. In the Repository section, select the project repository that you want to deploy
3. In the menu located at the top of this section, click 'Settings'
4. Select 'Pages' on the left-hand menu - this is around halfway down
5. In the source section, select branch 'Master' and save
6. The page is then given a site URL which will be seen above the source section, it will look like the following:

![](./assets/images/readme/github_deployment.jpeg/)

Please note it can take a while for this link to become fully active.

*Forking the GitHub Repository*

To make changes to this repository without affecting it, a copy can be made by 'Forking' it. This ensures the original repository remains unchanged.
1. Find the relevant GitHub repository
2. In the top right corner of the page, click the Fork button (under account)
3. The repository has now been 'Forked' and you have a copy to work on

*Cloning the GitHub Repository*

Cloning a repository will allow a local version of the repository will be downloaded so can be worked on. Cloning is also a great way to backup work.
1. Find the relevant GitHub repository
2. Press the arrow on the Code button
3. Copy the link that is shown in the drop-down
4. Now open Gitpod & select the directory location
5. In the terminal type 'git clone' & then paste the link copied from GitHub
6. Press enter and a local clone will be created.

## 6 Credits

### 6.1 Content

Logos and Fonts:
- The fonts were taken from [GoogleFonts](https://fonts.google.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

Tutorials and support:
- General guidance, information and limitations on elements, attributes, and methods from [w3schools](https://www.w3schools.com/default.asp) and [MDN Web Docs](https://developer.mozilla.org/en-US/)
- <insert list of tutorials followed>
- The many people who 'beta tested' the quiz app.

### 6.2 Media

Any photos used throughout the app are stock imagery from the following services:
- [unsplash](https://unsplash.com/)
- [FreeImages](https://www.freeimages.com/)
- [PikWizard](https://pikwizard.com/)

<insert any other media used throughout the app/site here>

### 6.3 Research

As mentioned in the design section, competitor research was conducted. These are credited below:
- <insert list of research links>

### 6.4 Special Thanks
