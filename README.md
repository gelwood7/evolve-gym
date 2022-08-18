![Evolve Gym image](/assets/images/Evolvebanner.JPG)

# Table of Contents

1. Overview

2. User Experience Design (UX)
    - User
    - Structure
    - Design
        - Colour Scheme
        - Typography
        - Imagery
        - Wireframes
        - Differences to Design

    - Future Releases

3. Features

4. Technologies

5. Testing
    - Test Strategy
    - Summary
    - High Level Test Cases
    - Out of Scope
    - Test Results
    - Testing Issues

6. Deployment

7. Credits

# Overview

![Only the fittest will survive - Charles Darwin](/assets/images/ReadmeQuote.JPG)

The Evolve gym website was designed with a primary purpose of a business website to showcase the gym and get membership. It's goal, is to acheive this by providing a positive user experence where the user has a 'one-stop shop' for everthing required to set and acheive their goals, state of the art Evolve gym, enthusiastic staff, science based workouts, diet and nutritional advise. Providing this additional information gives the site 'stickyness' so that the user will bookmark and return to the site may times for the content increaseing the possibilty of signing up!

The website is fully responsive and can be viewed across all devices.

![Images- of website on different devices from desktop to mobile phone](/assets/images/EvolveResponsive2.jpg)

Click [here](https://gelwood7.github.io/evolve-gym/) for the live website.

# User Experience Design (UX)

## User Stories

### First Time User
- As a first time user, I want to know this is a fittness website.
- As a first time user, I want to navigate easily through the site.
- As a first time user, I want to see what the gym looks like.
- As a first time user, I want to know the opening times, cost and location.
- As a first time user, I want to be able to make someone contact me about membership.  

### Returning User
- As a returning user, I want to avail of the science based workouts, diet and nutritional content.
- As a returning user, I want to join the gym.

## Structure

- The layout of the pages will be unclutered and intuitive as to what each page and section is about.
- Elements such as images and text will be reduced in size according to viewport to ensure readability and easy of navigation on mobile devices.
- The navigation bar will be visable on all pages.
- The content of the pages will:
    1. Showcase what the gym looks like and equipment available.
    2. Show the user the opening times and location.
    3. Present science based workouts for different muscle grups.
    4. Provide video, text and links to information on diet, nutrition and supplements (may not be included in inital release).
    5. Show the membership types and costs.
    6. Allow the user to submit a form with name and email address to be contacted by a menmber of the Evolve team.
    7. Show the user the form has been received, thank them and confirm they will be contacted ASAP.

## Design

- Colour Scheme
- Typography
- Imagery
- Wireframes
    1.  Home Page  
        ![Wireframe of Home page on desktop and mobile phone](/assets/images/Wireframe-Home.jpg)

    2.  Opening Hours and Location  
        ![Wireframe of Opening Hours and Location page on desktop and mobile phone](/assets/images/Wireframe-Where-When.jpg)
    
    3.  Workouts  
        ![Wireframe of Workouts page on desktop and mobile phone](/assets/images/Wireframe-Workouts.jpg)

    4.  Diet and Nutrition  
        ![Wireframe of Diet and Nutrition page on desktop and mobile phone](/assets/images/Wireframe-Diet-Nutrition.jpg)
    
    5.  Sign Up  
        ![Wireframe of Sign Up page on desktop and mobile phone](/assets/images/Wireframe-Sign-Up.jpg)


- Differences to Design

Testing
- Strategy
- Summary
- Test Cases
- Out of Scope
- Test Results  

Lighthouse Results - Desktop  
![Image of test results from lighthouse for desktop](/assets/images/Evolve-Lighthouse-Desktop.JPG)

Lighthouse Results - Mobile Phone  
![Image of test results from lighthouse for mobile](/assets/images/Evolve-Lighthouse-Mobile.JPG)

W3 HTML Valdation Result  
![Image of test results W3 HTML Valdator](/assets/images/W3-HTML-Validation.JPG)

W3 CSS Valdation Result  
![Image of test results W3 CSS Valdator](/assets/images/W3-CSS-Validation.JPG)


- Testing Issues
























Welcome gelwood7,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file, or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **September 1, 2021**

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
