# The Garden Gallery

Developer: Gary Burke ([Gary-Burke](https://www.github.com/Gary-Burke))

[![GitHub commit activity](https://img.shields.io/github/commit-activity/t/Gary-Burke/the-garden-gallery)](https://www.github.com/Gary-Burke/the-garden-gallery/commits/main)
[![GitHub last commit](https://img.shields.io/github/last-commit/Gary-Burke/the-garden-gallery)](https://www.github.com/Gary-Burke/the-garden-gallery/commits/main)
[![GitHub repo size](https://img.shields.io/github/repo-size/Gary-Burke/the-garden-gallery)](https://www.github.com/Gary-Burke/the-garden-gallery)

## Introduction ##

The Garden Gallery is a small business that operates from a private property in Radefeld, Germany. The business aims to organize social events, where a group of people sign up for a tour of the French-style garden. The tour is designed to be interactive, where visitors can not only view the style of the garden but also learn new techniques regarding garden styling and maintenance, as well as share tips and tricks within the group. After the tour, they will be introduced to an art gallery, where numerous art pieces from local artists will be on display. The visitors will then be allowed to make purchases, if they wish to. 

The main goal of this website is to increase their online presence and draw more people on a regular basis to their events, so that they can sell more merchandise and create a larger group of followers.

The live website can be viewed here: [The Garden Gallery](https://gary-burke.github.io/the-garden-gallery/)

![Am I Responsive image of the website](documentation/readme/the-garden-gallery-responsive.png)

---

## User Experience

### User Stories

- As a potential new visitor, I would like to see a home page that describes exactly what the event is about and what the entrance fees are.

- As a potential new visitor, it would be helpful if there were links with an image for guidance, to navigate to separate dedicated pages, which showcase the garden and the gallery.

- As a garden enthusiast, I want to see a few pictures, showcasing the Garden and what to expect from attending the event.

- As an art enthusiast, I want to see a few pictures, showcasing the Gallery with multiple artworks.

- As a customer, there should be easily accessible and visible buttons throughout the website, where I can effortlessly register for an event.

- As a customer, I would like to see some confirmation upon successful registration.

- As a potential visitor, there needs to be a clear and easily accessible contact section.

- As a potential visitor, it would be helpful to have a consistent and clear navigation system throughout the website.

## Design

### Typography

I have used [Google Fonts](https://fonts.google.com/) for this project and chose the following two fonts:

- **Great Vibes:** Used for all the main headings in the website. In order to accommodate the idea of the business, I opted for an artistic floral type of design. This font fits that criteria perfectly, aesthetically pleasing, yet still simple enough to read easily.

- **Nunito:** Used for all other text on the website. It provides a great blend of complementing the heading but with a stark enough contrast to make reading easy.

![Screenshot of fonts used](documentation/readme/fonts.png)

### Colour Scheme

When thinking of the word "Garden", the colour green automatically comes to mind. Therefore, I used [Coolors](https://coolors.co/palette/1c7c54-73e2a7-def4c6-1b512d-b1cf5f) to find a green colour palette that resembles this thought and feeling of nature.

Here is a visual representation of the overall colour scheme of the website:
![screenshot of the colour scheme used](documentation/readme/colour-scheme.jpg)

### Accessibility Considerations

In order to ensure proper contrast and accessibility between the colours for readability, I used [webaim](https://webaim.org/resources/contrastchecker/) to check and adjust the colour variations accordingly.

To test and ensure that there is an adequate contrast between the two fronts, I used [fontjoy](https://fontjoy.com/).

### Wireframes

For this project, I used Balsamiq to plan and draft the wireframes.

 <details><summary>The Home Page (<em>Click to expand the wireframe</em>)</summary>

![Home Page wireframe](documentation/readme/wireframe-home.png)
</details>

<details><summary>The Registration Page (<em>Click to expand the wireframe</em>)</summary>

![Registration Page wireframe](documentation/readme/wireframe-registration.png)
</details>

<details><summary>The Garden Page (<em>Click to expand the wireframe</em>)</summary>

![Garden Page wireframe](documentation/readme/wireframe-garden.png)
</details>

<details><summary>The Gallery Page (<em>Click to expand the wireframe</em>)</summary>

![Gallery Page wireframe](documentation/readme/wireframe-gallery.png)
</details>

## Features

### Current Features

- **Navigation Bar**

  - The navbar is placed at the top of the webpage with a fixed position. This gives the user the ease of navigation throughout the website, regardless of where they are on a page. The navbar is identical on all pages.
  - The active page is highlighted and a hover effect appears when hovering over the navigation items. There is also a call to action button, located at the end of the nav items, with its own hover-style effect.
 ![Screenshot of navbar](documentation/readme/features-navbar.png)

- **The Home page**

  - The landing page displays a beautiful garden as a hero image, which is the foundation of the business. Within view is also the section, which describes what the business is about and how much the entrance fees to these events are, providing the user with immediate essential information.
  - There is another strategically placed call to action button, which allows the user to register for these events. I have decided to add two cards with navigation buttons here, taking the user directly to the garden and the gallery pages, respectively.
 ![Screenshot of home page](documentation/readme/features-homepage.png)

- **The Garden Page**

  - The Garden page contains a few photos of the garden, which the events will revolve around. It showcases the different features, styles and angles of the scenes and provides the user with a better concept regarding what type of Garden to expect.
  - This is done with the Bootstrap grid system and arranges the pictures based on the screen breakpoints (responsiveness). There are rounded borders and sufficient gaps between the photos to give it a clean, styled look.
 ![Screenshot of garden page](documentation/readme/features-garden.png)

- **The Gallery Page**

  - The Gallery page contains a few photos of the various art that has been displayed at the gallery and in doing so, provides the user with a better visual understanding of what to expect.
  - As with the Garden page, this is done with the Bootstrap grid system and arranges the pictures based on the screen breakpoints (responsiveness). The same styles have been used as with the Gallery page.
 ![Screenshot of gallery page](documentation/readme/features-gallery.png)

- **The Registration Page**

  - A simple yet neat form has been used and styled to align with the rest of the website's overall design, giving the user an effortless process to register.
  - Only essential contact and personal information is required in addition to the choice of which event the user wants to attend.
  - All the input fields have a required attribute and input types, for example, the email and phone number fields. Upon successful registration, a confirmation message will appear, which gives the user clarity and it is accompanied by a home button.
 ![Screenshot of registration page](documentation/readme/features-registration.png)
 ![Screenshot of success page](documentation/readme/features-success.png)

- **Footer**

  - The footer contains the contact us section and as with the navbar, it is identical on all the pages and provides the user with all the necessary contact information at a glance.
  - It contains the address, the phone number and an email address.
 At the very bottom, all the different social media icons are displayed, which will open the sites on a new page.
 ![Screenshot of footer](documentation/readme/features-footer.png)

- **404 Page**

  - In the event of a 404 error, a suitable message will appear with a button to navigate the user back to the home page.
 ![Screenshot of 404 page](documentation/readme/features-404.png)


### Future Features

- **Online Store**

  - It would be a great business venture to create an online e-commerce store, where users can buy the art and view it online, without having to attend the event itself.

- **Hover effect images**

  - It would look intriguing if a user could hover over an image and then it becomes larger. This would apply to the Gallery and the Garden pages, respectively.

## Tools & Technologies

| Tool / Tech | Use |
| --- | --- |
| [![badge](https://img.shields.io/badge/Markdown_Builder-grey?logo=markdown&logoColor=000000)](https://markdown.2bn.dev) | Generate README and TESTING templates. |
| [![badge](https://img.shields.io/badge/Git-grey?logo=git&logoColor=F05032)](https://git-scm.com) | Version control. (`git add`, `git commit`, `git push`) |
| [![badge](https://img.shields.io/badge/GitHub-grey?logo=github&logoColor=181717)](https://github.com) | Secure online code storage. |
| [![badge](https://img.shields.io/badge/VSCode-grey?logo=htmx&logoColor=007ACC)](https://code.visualstudio.com) | Local IDE for development. |
| [![badge](https://img.shields.io/badge/HTML-grey?logo=html5&logoColor=E34F26)](https://en.wikipedia.org/wiki/HTML) | Main site content and layout. |
| [![badge](https://img.shields.io/badge/CSS-grey?logo=css&logoColor=1572B6)](https://en.wikipedia.org/wiki/CSS) | Design and layout. |
| [![badge](https://img.shields.io/badge/GitHub_Pages-grey?logo=githubpages&logoColor=222222)](https://pages.github.com) | Hosting the deployed front-end site. |
| [![badge](https://img.shields.io/badge/Bootstrap-grey?logo=bootstrap&logoColor=7952B3)](https://getbootstrap.com) | Front-end CSS framework for modern responsiveness and pre-built components. |
| [![badge](https://img.shields.io/badge/Balsamiq-grey?logo=barmenia&logoColor=CE0908)](https://balsamiq.com/wireframes) | Creating wireframes. |
| [![badge](https://img.shields.io/badge/Font_Awesome-grey?logo=fontawesome&logoColor=528DD7)](https://fontawesome.com) | Icons. |
| [![badge](https://img.shields.io/badge/W3Schools-grey?logo=w3schools&logoColor=04AA6D)](https://www.w3schools.com) | Tutorials/Reference Guide |
| [![badge](https://img.shields.io/badge/StackOverflow-grey?logo=stackoverflow&logoColor=F58025)](https://stackoverflow.com) | Troubleshooting and Debugging |
| [![badge](https://img.shields.io/badge/Gimp-grey?logo=gimp&logoColor=181717)](https://www.gimp.org/) | Image Manipulation |
| [![badge](https://img.shields.io/badge/Autoprefixer-grey?logo=autoprefixer&logoColor=CE0908)](https://autoprefixer.github.io/) | Parses CSS and adds vendor prefixes |

### Additional Tools

- [favicon.io](https://favicon.io/emoji-favicons/tulip) 
  - The emoji graphics are from the open source project Twemoji. The graphics are copyright 2020 Twitter, Inc and other contributors. The graphics are licensed under CC-BY 4.0.
- [Am I Responsive](https://ui.dev/amiresponsive) 
  - This resource was used to generate a responsive design screenshot for the README document of The Garden Gallery.
- [grammarly](https://app.grammarly.com/)
  - Used to check spelling and grammar of paragraphs in general, as well as README and TESTING documents.

## Development Process

### GitHub Projects

> [!Note]
> I did not use GitHub initially to document and track my user stories. For documentation purposes, I have transferred all of my user stories to my project in GitHub, hence no history or track record between creating and closing them.

GitHub Projects was the tool used for the planning and tracking of the website's development. Two projects were created, one for the user stories and one for bugs. Both can be viewed by clicking this link [GitHub Projects](https://www.github.com/Gary-Burke/the-garden-gallery/projects) 

![GitHub Projects screenshot](documentation/readme/gh-projects.png)

![GitHub Projects screenshot](documentation/readme/gh-issues-user-stories.png)

![screenshot](documentation/testing/gh-issues-bugs.png)

### MoSCoW Prioritization

I have listed my Epics into User Stories for prioritization and implementation purposes. In addition to the User Stories, I also applied the "MoSCoW" prioritization method with corresponding labels to them, within the Issues tab.

- **Must Have**: Critical tasks that need to be met for the project to pass.
- **Should Have**: These are valuable features, but not critical.
- **Could Have**: Nice to haves, but don't have a crucial impact.
- **Won't Have**: Not part of the current phase of the project but may be considered for future features.

## Deployment

### GitHub Pages

The site was deployed to GitHub Pages. The steps to deploy are as follows:

- In the [GitHub repository](https://github.com/Gary-Burke/the-garden-gallery), navigate to the Settings tab 
- From the source section drop-down menu, select the **Main** Branch, then click "Save".
- The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://gary-burke.github.io/the-garden-gallery)

### Local Deployment

This project can be cloned or forked in order to make a local copy on your own system.

#### Cloning

You can clone the repository by following these steps:

1. Go to the [GitHub repository](https://github.com/Gary-Burke/the-garden-gallery) 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or GitHub CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash or Terminal
5. Change the current working directory to the one where you want the cloned directory
6. In your IDE Terminal, type the following command to clone my repository:
  - `git clone https://github.com/Gary-Burke/the-garden-gallery.git`
7. Press Enter to create your local clone.

Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/Gary-Burke/the-garden-gallery)

Please note that in order to directly open the project in Gitpod, you need to have the browser extension installed.
A tutorial on how to do that can be found [here](https://www.gitpod.io/docs/configure/user-settings/browser-extension).

#### Forking

By forking the GitHub Repository, we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original owner's repository.
You can fork this repository by using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Gary-Burke/the-garden-gallery)
2. At the top of the Repository (not top of page), just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!


### Local VS Deployment

There are no differences between the local and deployed versions of the site.

## Testing

- For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Credits

### Content

| Source | Notes |
| --- | --- |
| [Chris Beams](https://chris.beams.io/posts/git-commit) | "How to Write a Git Commit Message". |
| [Markdown Builder](https://markdown.2bn.dev) | Help generating Markdown files. |
| [Boardwalk Games](https://github.com/Code-Institute-Solutions/boardwalk-games-v1-sourcecode/blob/main/02-08-the-endgame-finishing-up/02-08-02b-html-and-css-validation/index.html) | Code Institute walkthrough project, copied JavaScript code to ensure the Bootstrap mobile navbar collapses when navigating to in-page links. |
| [stackoverflow](https://stackoverflow.com/) | Used for troubleshooting, debugging and coding solutions |

### Media

| Source | Notes |
| --- | --- |
| [favicon.io](https://favicon.io) | Generating the favicon |
| [Font Awesome](https://fontawesome.com) | Icons used throughout the site |
| Sylvia Weber | She provided all images used for the garden and the art, as she is the owner. |
| Gary Burke | The text of this website has been written personally by me. Although the location and concept for this business idea exist, it remains nonetheless a fictitious website. |
| [chatGPT](https://chatgpt.com/) | Used to rewrite the paragraph content to have a more professional tone. |

### Acknowledgements

### Mentor

- I would like to thank my Code Institute mentor, [Tim Nelson](https://www.github.com/TravelTimN), for the support throughout the development of this project, especially regarding the README and TESTING documents.
- I would like to thank the [Code Institute Slack community](https://code-institute-room.slack.com) for their suggestions and feedback.
- I would like to thank Kay, my cohort facilitator at the Code Institute, for sharing valuable resources regarding this project and providing me with answers as I needed clarification.
