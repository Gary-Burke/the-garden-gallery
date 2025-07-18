# The Garden Gallery

The Garden Gallery is small business, that operates from a private property in Radefeld Germany. The aim of the business is to organize social events, where a group of people sign up for a tour of the french styled garden. After the tour, they will be introduced to an art gallery, where they can make purchases. The goal of this website, is to increase their online presence and draw more people on a regular basis to their events.

The live website can be viewed here: [The Garden Gallery](https://gary-burke.github.io/the-garden-gallery/)

![Am I Responsive image of the website](documentation/readme/the-garden-gallery-responsive.png)

---

## User Experience

### User Stories

- As a potential new visitor, I would like to see a home page, that describes exactly what the event is about and what the entrance fees are.

- As a potential new visitor, it would be helpful if there were links with an image for guidance, to navigate to separate dedicated pages, which showcases the garden and the galley.

- As a garden enthusiast, I want to see a few pictures, showcasing the Garden and what to expect from attending the event.

- As an art enthusiast, I want to see a few pictures, showcasing the Gallery with multiple artwork.

- As a customer, there should be easily accessible and visible buttons throughout the website, where I can effortlessly register for an event.

- As a customer, I would like to see some sort of confirmation upon successful registration.

- As a potential visitor, there needs to be a clear and easily accessible contact section.

- As a potential visitor, it would be helpful to have a consistent and clear navigation system throughout the website.

## Design

### Typography

I have used [Google Fonts](https://fonts.google.com/) for this project and chose the following two fonts:

- **Great Vibes:** Used for all the main headings in the website. In order to accomodate the idea of the business, I opted for a artistic floral type of design. This font fit that criteria perfectly, aesthetically pleasing, yet still simple enough to read easily.

- **Nunito:** Used for all other text in on the website. It provides a great blend of complementing the heading but with a stark enough contrast to make reading easy.

![Screenshot of fonts used](documentation/readme/fonts.png)

### Colour Scheme

When thinking of the word "Garden", the colour green automatically comes to mind. Therefore, I used [Coolors](https://coolors.co/palette/1c7c54-73e2a7-def4c6-1b512d-b1cf5f) to find a green colour palette that resemblances this thought and feeling of nature.

Here is a visual representation of the overall colour scheme of the website:
![screenshot of the colour scheme used](documentation/readme/colour-scheme.jpg)

### Accessibility Considerations

In order ensure proper contrast and accessibility between the colours for readability, I used [webaim](https://webaim.org/resources/contrastchecker/) to check and adjust the colour variations accordingly.

In order to test and ensure that there is an adequate contrast between the two fronts, I used [fontjoy](https://fontjoy.com/).

### Wireframes

For this project I used Balsamiq to plan and draft the wireframes.

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

  - The navbar is placed at the top of webpage with a fixed position. This gives the user the ease of navigation throughout the website, regardless of where thez are on a page. The navbar is identical on all pages.
  - The active page is highlighted and a hover effect appears, when hovering over the navigation items. There is also a call to action button, located at the end of the nav items with its' own hover styled effect.
    ![Screenshot of navbar](documentation/readme/features-navbar.png)

- **The Home page**

  - The landing page displays a beautiful garden as a hero image, which is the foundation of the business. Within view is also the section, which describes what the business is about and how much the entrance fees to these meetings are.
  - There is another strategically placed call to action button, which allows the user to register for these events. I have decided to add two cards with navigation buttons here, taking the user directly to the garden and the gallery pages respectively.
    ![Screenshot of home page](documentation/readme/features-homepage.png)

- **The Garden Page**

  - The Garden page contains a few photos of the garden, which the meetings will revolve around. It showcases the different features, styles and angles of the scenes.
  - This is done with the Bootstrap grid system and arranges the pictures based on the screen breakpoints (repsonsiveness). There are rounded borders and sufficient gaps between the photos, to give it a clean styled look.
    ![Screenshot of garden page](documentation/readme/features-garden.png)

- **The Gallery Page**

  - The Gallery page contains a few photos of the various art, that has been displayed or still is being displayed at the gallery.
  - As with the Gallery page, this is done with the Bootstrap grid system and arranges the pictures based on the screen breakpoints (repsonsiveness). The same styles have been used as with the Gallery page.
    ![Screenshot of gallery page](documentation/readme/features-gallery.png)

- **The Registration Page**

  - A simple yet neat form has been used and styled in accordance with the rest of the website's overall design.
  - Only essential contact and personal information is required in addition to the choice of which event the user wants to attend.
  - All the input fields have a required attribute and input types, for example the email and phone number fields. Upon successful registration, a confirmation message will appear, which gives the user clarity and it is accompanied by a home button.
    ![Screenshot of registration page](documentation/readme/features-registration.png)

    ![Screenshot of success page](documentation/readme/features-success.png)

- **Footer**

  - The footer contains the contact us section and as with the navbar, is identical on all the pages.
  - It contains the address, the phone number as well as an email address.
    At the vey bottom, one can easily find all the relevant social media icons, which will open the websites on a new page.
    ![Screenshot of footer](documentation/readme/features-footer.png)

- **404 Page**

  - In the event of a 404 error, a suitable message will appear with a button to navigate the user back to the home page.
  ![Screenshot of 404 page](documentation/readme/features-404.png)


### Future Features

- **Online Store**

  - It would be a great business venture, to create an online e-commerce store, where users can buy the art and view it online, without having to attend the event itself.

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

-  [favicon.io](https://favicon.io/emoji-favicons/tulip)
   - The emoji graphics are from the open source project Twemoji. The graphics are copyright 2020 Twitter, Inc and other contributors. The graphics are licensed under CC-BY 4.0.
-  [Am I Responsive](https://ui.dev/amiresponsive)
   - This resource was used to generate a design responsive screenshot for the README document of The Garden Gallery.

## Deployment

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
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. Once clicked, you should now have a copy of the original repository in your own GitHub account!


### Local VS Deployment

There are no differences between the local and deployed version of the site.

## Testing

- For all testing, please refer to the [TESTING.md](TESTING.md) file.

## Credits

### Code Used

- The only additional code copied and used was the JavaScript code to ensure the Bootstrap mobile navbar collapses when navigating to in-page links. This code was copied from the CI Boardwalk Games project.

### Content

- The text of this website has been written personally by me. Although this location and concept for this business idea is real, it remains nonetheless a fictitious website.

### Media

- All the images have been personally provided by Sylvia Weber, the hostess of this Garden Gallery.

### Mentor
- My mentor, Tim Nelson, helped me quite a bit with the README document. He explained what is needed, why it is needed and what needs to be changed, especially in regards to the deployment and testing sections.
- He also advised me on adding the 404 page to my project. 
