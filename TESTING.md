# Testing

> [!Note]
> Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| root | [404.html](https://github.com/Gary-Burke/the-garden-gallery/blob/main/404.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://gary-burke.github.io/the-garden-gallery/404.html) | ![screenshot](documentation/testing/validator-404.png) | No errors or warnings |
| root | [gallery.html](https://github.com/Gary-Burke/the-garden-gallery/blob/main/gallery.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://gary-burke.github.io/the-garden-gallery/gallery.html) | ![screenshot](documentation/testing/validator-gallery.png) | No errors or warnings |
| root | [garden.html](https://github.com/Gary-Burke/the-garden-gallery/blob/main/garden.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://gary-burke.github.io/the-garden-gallery/garden.html) | ![screenshot](documentation/testing/validator-garden.png) | No errors or warnings |
| root | [index.html](https://github.com/Gary-Burke/the-garden-gallery/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://gary-burke.github.io/the-garden-gallery/index.html) | ![screenshot](documentation/testing/validator-index.png) | No errors or warnings |
| root | [register.html](https://github.com/Gary-Burke/the-garden-gallery/blob/main/register.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://gary-burke.github.io/the-garden-gallery/register.html) | ![screenshot](documentation/testing/validator-register.png) | No errors or warnings |
| root | [success.html](https://github.com/Gary-Burke/the-garden-gallery/blob/main/success.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://gary-burke.github.io/the-garden-gallery/success.html) | ![screenshot](documentation/testing/validator-success.png) | No errors or warnings |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [styles.css](https://github.com/Gary-Burke/the-garden-gallery/blob/main/assets/css/styles.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://gary-burke.github.io/the-garden-gallery) | ![screenshot](documentation/testing/validator-css.png) | All warnings were checked and can be safely ignored. Such as for the Bootstrap and Font Awesome libraries, vendor extensions added by Autoprefixer, the Google Fonts import and CSS variables that are not checked. |


## Responsiveness

I've tested my deployed project to check for responsiveness issues by using Google Chrome Dev Tools.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/testing/responsiveness-mobile-home.png) | ![screenshot](documentation/testing/responsiveness-tablet-home.png) | ![screenshot](documentation/testing/responsiveness-desktop-home.png) | Works as expected |
| Garden | ![screenshot](documentation/testing/responsiveness-mobile-garden.png) | ![screenshot](documentation/testing/responsiveness-tablet-garden.png) | ![screenshot](documentation/testing/responsiveness-desktop-garden.png) | Works as expected |
| Gallery | ![screenshot](documentation/testing/responsiveness-mobile-gallery.png) | ![screenshot](documentation/testing/responsiveness-tablet-gallery.png) | ![screenshot](documentation/testing/responsiveness-desktop-gallery.png) | Works as expected |
| Registration | ![screenshot](documentation/testing/responsiveness-mobile-register.png) | ![screenshot](documentation/testing/responsiveness-tablet-register.png) | ![screenshot](documentation/testing/responsiveness-desktop-register.png) | Works as expected |
| Success | ![screenshot](documentation/testing/responsiveness-mobile-success.png) | ![screenshot](documentation/testing/responsiveness-tablet-success.png) | ![screenshot](documentation/testing/responsiveness-desktop-success.png) | Works as expected |
| 404 | ![screenshot](documentation/testing/responsiveness-mobile-404.png) | ![screenshot](documentation/testing/responsiveness-tablet-404.png) | ![screenshot](documentation/testing/responsiveness-desktop-404.png) | Works as expected |

## Browser Compatibility

I've tested my deployed project on three different browsers to check for compatibility issues.

| Page | Chrome | Firefox | Edge | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/browsers/chrome-home.png) | ![screenshot](documentation/browsers/firefox-home.png) | ![screenshot](documentation/browsers/edge-home.png) | Works as expected |
| Garden | ![screenshot](documentation/browsers/chrome-garden.png) | ![screenshot](documentation/browsers/firefox-garden.png) | ![screenshot](documentation/browsers/edge-garden.png) | Works as expected |
| Gallery | ![screenshot](documentation/browsers/chrome-gallery.png) | ![screenshot](documentation/browsers/firefox-gallery.png) | ![screenshot](documentation/browsers/edge-gallery.png) | Works as expected |
| Register | ![screenshot](documentation/browsers/chrome-register.png) | ![screenshot](documentation/browsers/firefox-register.png) | ![screenshot](documentation/browsers/edge-register.png) | Works as expected |
| Success | ![screenshot](documentation/browsers/chrome-success.png) | ![screenshot](documentation/browsers/firefox-success.png) | ![screenshot](documentation/browsers/edge-success.png) | Works as expected |
| 404 | ![screenshot](documentation/browsers/chrome-404.png) | ![screenshot](documentation/browsers/firefox-404.png) | ![screenshot](documentation/browsers/edge-404.png) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](documentation/testing/lighthouse-mobile-home.png) | ![screenshot](documentation/testing/lighthouse-desktop-home.png) |
| Garden | ![screenshot](documentation/testing/lighthouse-mobile-garden.png) | ![screenshot](documentation/testing/lighthouse-desktop-garden.png) |
| Gallery | ![screenshot](documentation/testing/lighthouse-mobile-gallery.png) | ![screenshot](documentation/testing/lighthouse-desktop-gallery.png) |
| Register | ![screenshot](documentation/testing/lighthouse-mobile-register.png) | ![screenshot](documentation/testing/lighthouse-desktop-register.png) |
| Success | ![screenshot](documentation/testing/lighthouse-mobile-success.png) | ![screenshot](documentation/testing/lighthouse-desktop-success.png) |
| 404 | ![screenshot](documentation/testing/lighthouse-mobile-404.png) | ![screenshot](documentation/testing/lighthouse-desktop-404.png) |

## Defensive Programming

Defensive programming was manually tested with following criteria and outcome:

| Page | Expectation | Test | Result | Screenshot |
| --- | --- |  --- |  --- |  --- |
| Registration Form | Feature is expected to prevent an empty form from being submitted. | Attempted to submit the form when all fields were left blank. | Form submission was blocked, as expected. | ![screenshot](documentation/defensive/form-first-name.png) |
| | Feature is expected to ensure a last name is entered. | Attempted to submit the form without adding a last name. | Form submission was blocked, as expected. | ![screenshot](documentation/defensive/form-last-name.png) |
| | Feature is expected to ensure an e-mail is entered. | Attempted to submit the form without adding an e-mail address. | Form submission was blocked, as expected. | ![screenshot](documentation/defensive/form-email-1.png) |
| | Feature is expected to enforce valid input for the email field. | Entered invalid data, i.e. did not add the @ sign. | Error message was displayed accordingly, and submission was blocked. | ![screenshot](documentation/defensive/form-email-2.png) |
| | Feature is expected to ensure a phone number is entered. | Attempted to submit the form without adding a phone number. | Error messages were displayed appropriately, and submission was blocked. | ![screenshot](documentation/defensive/form-phone.png) |
| | Feature is expected to ensure the user chooses an event. | Attempted to submit the form without selecting an event. | Error messages were displayed appropriately, and submission was blocked. | ![screenshot](documentation/defensive/form-select.png) |
| Social Links | Feature is expected to open each social media platform in a new tab. | Clicked each social media icon respectively. | Confirmed that each link opened correctly and in a new tab. | ![screenshot](documentation/defensive/social-links.png) |
| 404 Error Page | Feature is expected to display a 404 error message for broken links or non-existing pages. | Typed in an invalid URL (e.g., `/dream`) to test the outcome. | An appropriate 404 error page was displayed as expected. | ![screenshot](documentation/defensive/404.png) |

## User Story Testing


| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a new visitor | I would like to see a home page, that describes exactly what the event is about and what the entrance fees are | so that I can know what to expect and how much it costs. | ![screenshot](documentation/features/feature01.png) |
| As a new visitor | it would be helpful if there were links with an image for guidance, to navigate to separate dedicated pages | which showcases the garden and the gallery. | ![screenshot](documentation/features/feature02.png) |
| As a new visitor | there should be easily accessible and visible buttons throughout the website  | so that I can effortlessly register for an event. | ![screenshot](documentation/features/feature03.png) |
| As a new visitor | I would like to see some sort of confirmation upon successful registration | so that I can be sure that it was successful. | ![screenshot](documentation/features/feature04.png) |
| As a new visitor |  there needs to be a clear and easily accessible contact section | so that I can get further information if needed. | ![screenshot](documentation/features/feature05.png) |
| As a new visitor | it would be helpful to have a consistent and clear navigation system throughout the website | so that I don't get lost or confused between pages. | ![screenshot](documentation/features/feature06.png) |
| As a garden enthusiast | I want to see a few pictures, showcasing the Garden | so that I can be well prepared | ![screenshot](documentation/features/feature07.png) |
| As an art enthusiast | I want to see a few pictures, showcasing the Gallery with multiple artwork | so that I can better understand the range of art. | ![screenshot](documentation/features/feature08.png) |

## Bugs

> [!Note]
> I did not document my bugs on GitHub initially. After the first discussion session with my mentor, Tim Nelson, he showed me this method of using GitHub to track your bugs. For documentation purposes, I have transferred all of my bugs to my project in GitHub afterwards, hence no history or track record between creating and resolving them.

### Fixed Bugs

[![GitHub issue custom search](https://img.shields.io/github/issues-search?query=repo%3AGary-Burke%2Fthe-garden-gallery%20label%3Abug&label=bugs)](https://www.github.com/Gary-Burke/the-garden-gallery/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

I've used [GitHub Issues](https://www.github.com/Gary-Burke/the-garden-gallery/issues) to track and manage bugs and issues during the development stages of my project.

All previously closed/fixed bugs can be tracked [here](https://www.github.com/Gary-Burke/the-garden-gallery/issues?q=is%3Aissue+is%3Aclosed+label%3Abug).

![screenshot](documentation/testing/gh-issues-bugs.png)

### Unfixed Bugs

- There are no remaining bugs or problems that I am aware of in this project and website. 
- Eventhough thorough testing was executed, the possibility remains that there could still be some error or bug, that has not been discovered yet.

