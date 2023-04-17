# Testing

Return back to the [README.md](README.md) file.

In this section I will be providing evidence to show that:
- The project **features** work as intended
- The **users** can achieve their goals
- The project is **responsive** across different devices and screen sizes
- The project is **compatible** across different web browsers
- The project uses **valid code** according to standard practice
- The project passes audits for **performance, accessibility, best practices and SEO** (using Lighthouse by Chrome Developer Tools)

## Code Validation

I will use this space to discuss code validation of my code files (where applicable).
I will not validate external libraries/frameworks, such as imported Bootstrap, Materialize, Font Awesome, etc.

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

I validated each of the live pages using the deployed URL. This gave me a custom URL for each page which I have included in the documentation below. This will make it easier to return to each page when validating again in future.

| Page | W3C URL | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ftarahwaters.github.io%2Fmilestone-project1%2Findex.html) | ![screenshot](documentation/testing/validation-html-home.jpg) | Pass: No Errors |
| About | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ftarahwaters.github.io%2Fmilestone-project1%2Fabout.html) | ![screenshot](documentation/testing/validation-html-about.jpg) | Pass: No Errors |
| Contact | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ftarahwaters.github.io%2Fmilestone-project1%2Fcontact.html) | ![screenshot](documentation/testing/validation-html-contact.jpg) | Pass: No Errors |
| Redirect (confirmation) | [W3C](https://validator.w3.org/nu/?doc=https%3A%2F%2Ftarahwaters.github.io%2Fmilestone-project1%2Fredirect.html) | ![screenshot](documentation/testing/validation-html-redirect.jpg) | Pass: No Errors |

### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate my CSS file.

The deployed URL was used to validate the CSS since a single file was used for the project. This gave a custom URL which is included and can be used for future validation. Evidence from the direct code input validation was also included.

| File | Jigsaw URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [Jigsaw - deployed link](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Ftarahwaters.github.io%2Fmilestone-project1) | ![screenshot](documentation/testing/validation-css-deployed-link.png) | The errors shown are from imported Boostrap styling. The warnings are from Bootstrap and also **-webkit-fill-available** is a vendor extension |
| style.css | [Jigsaw - direct input link](https://jigsaw.w3.org/css-validator/#validate_by_input)  |![screenshot - direct input](documentation/testing/validation-css-code.png)  | Pass: No Errors |

## Browser Compatibility

The live/deployed site was tested on multiple browsers to check for compatibility issues.

The following popular browsers were tested:
- [Chrome](https://www.google.com/chrome)
- [Firefox (Developer Edition)](https://www.mozilla.org/firefox/developer)
- [Edge](https://www.microsoft.com/edge)
- [Safari](https://support.apple.com/downloads/safari)
- [Brave](https://brave.com/download)
- [Opera](https://www.opera.com/download)

| Browser | Screenshot | Notes |
| --- | --- | --- |
| Chrome | ![screenshot](documentation/testing/compatibility-chrome-home.png) | Works as expected |
| Firefox | ![screenshot](documentation/testing/compatibility-firefox-home.png) | Works as expected |
| Edge | ![screenshot](documentation/testing/compatibility-edge-home.png) | Works as expected |
| Safari | ![screenshot](documentation/testing/compatibility-safari-home.jpeg) | Works as expected |
| Brave | ![screenshot](documentation/testing/compatibility-brave-home.png) | Works as expected |
| Opera | ![screenshot](documentation/testing/compatibility-opera-home.png) | Works as expected |

## Manual Testing

| Feature | Expect | Action | Result |
| --- | --- | --- | --- |
| **Home Navbar Button** | When clicked the home page will open | Clicked Home on the Nav bar | Home page opened when clicked |
| **About Navbar Button** | When clicked the about page will open | Clicked Home on the Nav bar | Home page opened when clicked |
| **Contact Navbar Button** | When clicked the contact page will open | Clicked Home on the Nav bar | Home page opened when clicked |
| **Summit logo / Brand name on Navbar** | When clicked the home page will open | Clicked the logo or brand name on the Nav bar | Home page opened when clicked |
| **Menu Item Button** (screens less than 1400px width) | When clicked the menu item list will open and drop down | Clicked the menu button | Menu list opened |


## Responsiveness

I have tested my deployed project on multiple devices to check for responsiveness issues.

| Device | Screenshot | Notes |
| --- | --- | --- |
| **Small Mobile** 320x734 (DevTools) | ![screenshot](documentation/testing/responsive-mob-small-320px.png) | Works as expected |
| **Medium Mobile** 375x374 (iPhone SE using DevTools) | ![screenshot](documentation/testing/responsive-mob-iphoneSE.png) | Works as expected |
| **Large Mobile** 412x915 (Samsung s20 Ultra) | ![screenshot](documentation/testing/responsive-mob-samsung-s20-ultra.png) | Works as expected |
| **Tablet** 786x734 | ![screenshot](documentation/testing/responsive-tablet-768px.png) | Works as expected |
| **Laptop** 1024x734 | ![screenshot](documentation/testing/responsive-laptop-1024px.png) | Works as expected   |
| **Large Laptop** 1440x734 | ![screenshot](documentation/testing/responsive-laptop-lg-1440px.png) | Hero-image cover text smaller than expected here but only minor issue |
| **Desktop** 1920x1080 | ![screenshot](documentation/testing/responsive-desktop-1920px.png) | Works as expected |
| **4K Monitor** 2560x1506 | ![screenshot](documentation/testing/responsive-4k-2560px.png) | Works as expected |

## Lighthouse Audit

I have tested my deployed project using the Lighthouse Audit tool to check for any major issues.

| Page | Size | Screenshot | Notes |
| --- | --- | --- | --- |
| Home | Mobile | ![screenshot](documentation/testing/lighthouse-mob-home.jpg) | Some warnings for performance due to sizing of images but also some external code errors that could not be helped |
| Home | Desktop | ![screenshot](documentation/testing/lighthouse-desktop-home.jpg) | Some warnings for performance due to sizing of images but also some external code errors that could not be helped |
| About | Mobile | ![screenshot](documentation/testing/lighthouse-mob-about.jpg) | Some warnings for performance due to sizing of images but also some external code errors that could not be helped |
| About | Desktop | ![screenshot](documentation/testing/lighthouse-desktop-about.jpg) | Good scores |
| Contact | Mobile | ![screenshot](documentation/testing/lighthouse-mob-contact.jpg) | Good scores |
| Contact | Desktop | ![screenshot](documentation/testing/lighthouse-desktop-contact.jpg) | Some warnings for performance due to sizing of images but also some external code errors that could not be helped |
| Redirect | Mobile |  ![screenshot](documentation/testing/lighthouse-mob-redirect.jpg) | Some warnings for performance due to sizing of images but also some external code errors that could not be helped |
| Redirect | Desktop |  ![screenshot](documentation/testing/lighthouse-desktop-redirect.jpg) | Some warnings for performance due to sizing of images but also some external code errors that could not be helped |

## User Story Testing

| User Story | Screenshot | Notes |
| --- | --- | --- |
| As a new site user, I would like to find out more about the services offered. | ![screenshot](documentation/testing/user-story-company-summary.jpg) | A summary of the service the company provides is highlighted on the Home page. |
| As a user I want to find this information easily, without too many clicks needed. | ![screenshot](documentation/testing/user-story-homepage.jpg) | Navigation between pages is clear via the navbar menu and a contact form is accessible on each page. |
| As a user I want to know the experience level of the consulting team and their backgrounds.| ![screenshot](documentation/testing/user-story-team-details.jpg) | The About page gives details of each team member and their backgrounds. |
| As a user I want to be reassured that the team are trustworthy, have a positive reputation and a track record of successful candidates. | ![screenshot](documentation/testing/user-story-reviews.jpg) | 'What are people saying?' section is accessible from the Home page where users can read reviews from previous clients. |
| As a user I want to get in touch with the company easily and securely, without needing to commit or pay anything upfront. | ![screenshot](documentation/testing/user-story-contact-form.jpg) | There is a contact form accessible at the bottom of each page for easy sign-up. |
| As a user I want to be able to find the company contact details and social links easily. | ![screenshot](documentation/testing/user-story-social-links.jpg)  ![screenshot](documentation/testing/user-story-easy-submit-details.jpg) | The Contact page is accessible via the navbar menu (as expected) and there are social links in the footer of each page. |
| As a user I want reassurance that my enquiry will be answered quickly and the process is straight-forward. | ![screenshot](documentation/testing/user-story-submit-confirmation.jpg) | The Redirect page post contact form submission gives the user a time frame of when their enquiry will be answered. |
| As a user I want to the option of opting in / out of receiving newsletters and advice by email when submitting my details. | Unable to achieve at this time - See **Future Features**. | X |
| As a user I want to view this information smoothly on preferably either a mobile device or tablet, with the option of also a desktop. | ![screenshot](documentation/readme/am-i-responsive-summit-careers.png)| The site has a responsive layout accessible from different popular devices and browsers. |
| As a site owner I want users to find out about our services and team | ![screenshot](documentation/testing/user-story-team-details.jpg) | There is information about the company and its team acccessible from the Home and About page. |
| As a site owner I want users to submit their contact details and arrange schedule a meeting with us. | ![screenshot](documentation/testing/user-story-get-in-touch.jpg) ![screenshot](documentation/testing/user-story-contact-form.jpg) | Contact form is accessible at the bottom of each page as per the client's specifications and the button 'Get in touch' will take the user straight to the form. |
| As a site owner I want users to know the positive success we have had with other clients and the process involved when working with us | ![screenshot](documentation/testing/user-story-reviews.jpg) | The Review section of the Home page gives details of positive feedback from other clients, but the Study Abroad page was intended to outline the company's process in more detail (unable to achieve at this time, but a part of **Future Features**.)

## Bugs

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

It's very important to document any bugs you've discovered while developing the project.
Make sure to include any necessary steps you've implemented to fix the bug(s) as well.

For JavaScript and Python applications, it's best to screenshot the errors to include them as well.

**PRO TIP**: screenshots of bugs are extremely helpful, and go a long way!

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- JS Uncaught ReferenceError: `foobar` is undefined/not defined

    ![screenshot](documentation/bug01.png)

    - To fix this, I _____________________.

- JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).

    ![screenshot](documentation/bug02.png)

    - To fix this, I _____________________.

- Python `'ModuleNotFoundError'` when trying to import module from imported package

    ![screenshot](documentation/bug03.png)

    - To fix this, I _____________________.

- Django `TemplateDoesNotExist` at /appname/path appname/template_name.html

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

- Python `E501 line too long` (93 > 79 characters)

    ![screenshot](documentation/bug04.png)

    - To fix this, I _____________________.

**Fixed Bugs**

All previously closed/fixed bugs can be tracked [here](https://github.com/tarahwaters/milestone-project1/issues?q=is%3Aissue+is%3Aclosed).

| Bug | Status |
| --- | --- |
| [JS Uncaught ReferenceError: `foobar` is undefined/not defined](https://github.com/tarahwaters/milestone-project1/issues/1) | Closed |
| [Python `'ModuleNotFoundError'` when trying to import module from imported package](https://github.com/tarahwaters/milestone-project1/issues/2) | Closed |
| [Django `TemplateDoesNotExist` at /appname/path appname/template_name.html](https://github.com/tarahwaters/milestone-project1/issues/3) | Closed |

**Open Issues**

Any remaining open issues can be tracked [here](https://github.com/tarahwaters/milestone-project1/issues).

| Bug | Status |
| --- | --- |
| [JS `'let'` or `'const'` or `'template literal syntax'` or `'arrow function syntax (=>)'` is available in ES6 (use `'esversion: 11'`) or Mozilla JS extensions (use moz).](https://github.com/tarahwaters/milestone-project1/issues/4) | Open |
| [Python `E501 line too long` (93 > 79 characters)](https://github.com/tarahwaters/milestone-project1/issues/5) | Open |

## Unfixed Bugs

- **Boostrap hero image carousel takes up too much space on large screens** - ✔️ semi-fixed by adjusting the viewport image height in a media query for large screens above 2000px.
- **Horizontal and vertical extra spacing of the page on all devices (excessive margin at bottom and right sides of pages)** - ✅ horizontal spacing fixed by overriding BS gutter via .row class on all pages (credit to @Paul Treggiden for help with this), and vertical spacing fixed by maximising the height of the footer on all pages.
- **Alignment of 'next/previous' carousel indicators on hero and review images** - ✔️ semi-fixed by adding a media query for mobile devices (less than 992px) that overrides the BS class properties for 'align-items' and 'padding-top' so that prev/next indicators are more visible around the review photos. However, this styling then applies to the hero carousel indicators too which makes them less useable (though this is not too problematic for mobile devices, since the buttons are a bit cumbersome anyway).
- **Review captions distort container height and alignment of carousel indicators** - ❌ not yet fixed. Carousel indicators are now separately styled to be located above the review captions, but the caption container adapts in height depending on the content size which is quite jarring for the user on mobile devices.
- **No redirect page after submitting data for contact form** - ✅ redirect.html page created for user confirmation after submitting form data and links added to all contact forms (with button to return to the Home page).
- **University image on homepage stretched on mobile devices** - ✔️ semi-fixed by deleting the CSS media query mistake for .image-sizing up to max-width 1525px. This seemed to work until another bug arose, where there was white spacing under the image for 992px-1450px screen widths. The bug was not fixed, so instead the media query for max-width 992px (i.e. for the single column mobile layout to be activated) was change to 1450px. This means that the single column layout is triggered for larger devices, but at least the image is scaled properly.

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

You will need to mention unfixed bugs and why they were not fixed.
This section should include shortcomings of the frameworks or technologies used.
Although time can be a big variable to consider, paucity of time and difficulty understanding
implementation is not a valid reason to leave bugs unfixed.

If you've identified any unfixed bugs, no matter how small, be sure to list them here.
It's better to be honest and list them, because if it's not documented and an assessor finds the issue,
they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

Some examples:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

- On devices smaller than 375px, the page starts to have `overflow-x` scrolling.

    ![screenshot](documentation/unfixed-bug01.png)

    - Attempted fix: I tried to add additional media queries to handle this, but things started becoming too small to read.

- For PP3, when using a helper `clear()` function, any text above the height of the terminal does not clear, and remains when you scroll up.

    ![screenshot](documentation/unfixed-bug02.png)

    - Attempted fix: I tried to adjust the terminal size, but it only resizes the actual terminal, not the allowable area for text.

- When validating HTML with a semantic `section` element, the validator warns about lacking a header `h2-h6`. This is acceptable.

    ![screenshot](documentation/unfixed-bug03.png)

    - Attempted fix: this is a known warning and acceptable, and my section doesn't require a header since it's dynamically added via JS.

⚠️⚠️⚠️⚠️⚠️ START OF NOTES (to be deleted) ⚠️⚠️⚠️⚠️⚠️

If you legitimately cannot find any unfixed bugs or warnings, then use the following sentence:

🛑🛑🛑🛑🛑 END OF NOTES (to be deleted) 🛑🛑🛑🛑🛑

There are no remaining bugs that I am aware of.
