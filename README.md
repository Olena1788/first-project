

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
# Bangor Garden Club

Bangor Garden Club is a site that aims to promote environmental causes and motivate people to learn from experienced gardeners as well as pass along own knowledge and know-how to new generations of gardeners. The site will be targeted towards people who love gardening and look for a way to socialise.
Bangor Garden Club will be useful for gardeners who want to find join the club to participate in projects, share their ideas and knowledge with others.

# User Stories

**Client Goals**
- To be able to view the site on a range of device sizes.
- To make it easy for potential members to find out what the garden club is and how to join it.
- To allow people to be able to contact the garden club to ask further questions.

**First Time Visitor Goals**
- I want to find out what Bangor Garden Club is and how I can join it.
- I want to be able to navigate the site easily to find information.
- I want to be able to find their social media profiles.

**Returning Visitor Goals**
- I want to find information on what the  current projects are and what educational programs are available .
- I want to be able to see the dates for upcomming meetings of the club members.

**Frequent Visitor Goals**
I want to be able to give and ask advice on plants care.

# Design 
## Color scheme?????

## Typography
Font-family " Libre Franklin, Arial, Helvetica" was used throughout the website.

## Imagery
The images were used from https://unsplash.com/. 

## Wireframes
Wireframes were created for mobile, tablet and desktop.

Home Page Wireframe

Gallery Page Wireframe

Signup Page Wireframe

## Features
The website is comprised of three pages, which are accessible from the navigation menu (home page, gallery page and signup page).

**All Pages on the website have:**

- A responsive navigation bar at the top right corner which allows the user to navigate through the site also the same image of flowers is used as a background  to maintain consistency throughout the site.

- A footer which contains social media icon links to facebook, instagram and twitter. Icons were used to keep the footer clean and they are universally recognisable. The links will open to a new tab to allow easy navigation for the user. The footer is useful to the user as it is a form of encouragement for them to keep connected via social media.

**Home Page**

Club's logo is in the center to draw users' attention. Section containing information about the club with its contact details, address and open times appears when the page is scrolled down.
Map section goes below section with clubs' information. It shows the users the location of the club.

**Gallery page**

Gallery will provide the user with supporting images to see what the club does and its members' accomplishments.

**Signup page**

This page will allow the user to get signed up to the club by submitting their full name and email address.

**Features left to implement**
- Separate page to be added which will comprise of blocks of information about ecology meetings and programs to engage cildren and teens.
- Separate page for the members to view club members' events and blogs.
- Exchange/Giveaway page - This page would enable club's members to see the information about plants exchange and giveaways events that take place in garden club. 

## Accessibility
The site is accessible friendly due to the use of descriptive alt attributes on images, information for screen readers where there are footer icons used and no text, ensuring that there is a sufficient colour contrast throughout the site and menus are accessible by marking the current page as current for screen readers.

# Technologies Used

The following technologies were used to create and test the website:
- HTML - HyperText Markup Language to create the structure of the website content.
- CSS - Cascading Style Sheet Language to provide style to the website.
- Balsamiq to create wireframes.
- TinyPNG - to compress images.
- Gitpod - to create cloud based Integrated Developement Environment.
- GitHub - to provide software development to store files.
- Git - to do version control system.
- Google Dev Tools - To troubleshoot and test features, resolve issues with responsiveness and styling.
- Favicon.io - to create Favicon.
- Font Awesome - For the iconography on the website.
- Am I Responsive? - to show the website landing page responsiveness on different devices.
- README Markdownguide - to use tips for creation of README.md
- CSS Jigsaw - to validate CSS code.
- HTML Vallidator - to validate HTML code.
- LiveBrowserStack - to check the compatability of website.
- Freeformatter - to validate HTML code.


# Deployment & Local Development
## Deployment
Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
2. Find the repository for this project.
3. Click on the Settings link.
4. Click on the Pages link in the left hand side navigation bar.
5. In the Source section, choose main from the drop down select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

## Local Development
**How to Fork**
To fork the .... repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, .....
3. Click the Fork button in the top right corner.

**How to Clone**
To clone the ..... repository:

1. Log in (or sign up) to GitHub.
2. Go to the repository for this project, kera-cudmore/Bully-Book-Club.
3. Click on the code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' into the terminal and then paste the link you copied in step 3. Press enter.

## Testing

Testing was ongoing throughout the entire build. I utilised Chrome developer tools while building to pinpoint and troubleshoot any issues as I went along.

The following issues were raised ......

# W3C Validator
The W3C validator was used to validate the HTML on all pages of the website. It was also used to validate CSS in the style.css file.

# Jigsaw W3 Validator
Jigsaw W3 Validator was used to validate CSS code.

- Home Page HTML
- Gallery Page HTML
- Signup Page HTML

# Solved Bugs

# Known Bugs












# A
## A
### A
**A**



## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](https://github.com/lucyrush/readme-template/blob/master/media/love_running_nav.png)

- __The landing page__

  - The landing includes an image of flowers as a background with text overlay to allow the user to see the information about the club. 
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![Landing Page](https://github.com/lucyrush/readme-template/blob/master/media/love_running_landing.png)

- __Club Ethos Section__

  - The club ethos section will allow the user to see the benefits of joining the Love Running meetups, as well as the benefits of running overall. 
  - This user will see the value of signing up for the Love Running meetups. This should encourage the user to consider running as their form of exercise. 

![Club Ethos](https://github.com/lucyrush/readme-template/blob/master/media/love_running_ethos.png)

- __Meetup Times section__

  - This section will allow the user to see exactly when the meetups will happen, where they will be located and how long the run will be in kilometers. 
  - This section will be updated as these times change to keep the user up to date. 

![Meetup Times](https://github.com/lucyrush/readme-template/blob/master/media/love_running_times.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/lucyrush/readme-template/blob/master/media/love_running_footer.png)

- __Gallery__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/lucyrush/readme-template/blob/master/media/love_running_gallery.png)

- __The Sign Up Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Sign Up](https://github.com/lucyrush/readme-template/blob/master/media/love_running_signup.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 