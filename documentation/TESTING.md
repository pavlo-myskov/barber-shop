# Testing

## Contents

- [Functional Testing](#functional-testing)
    - [Home Page](#home-page)
    - [Form](#booking-page-form)
    - [Gallery](#gallery)
- [Compatibility Testing](#compatibility-testing)
    - [Browser Compatibility](#browser-compatibility)
    - [Device Compatability and Responsiveness Testing](#device-compatability-and-responsiveness-testing)
- [Validator Testing](#validator-testing)
    - [HTML Validation](#html-validation)
        - [Home page](#home-page-1)
        - [Booking page](#booking-page)
        - [Gallery page](#gallery-page)
    - [CSS Validation](#css-validation)
    - [Accessibility and Performance](#accessibility-and-performance)
        - [Home page](#home-page-2)
        - [Booking page](#booking-page-1)
        - [Gallery page](#gallery-page-1)
- [Bugs](#bugs)

## Functional Testing

- ### Home page
    Test | Result
    ---|:---:
    Page responsiveness | ok
    Sticky navbar | ok
    Navigation hover effect | ok
    Logo link back to homepage | ok
    Navigation links to relevant pages | ok
    Book Now link to booking form | ok
    Main menu collpases to a hamburger menu on small screen | ok
    Book an appointment in the service sections link to booking form | ok
    Social media icons in the footer link to the relevant social media and open in new tab | ok

- ### Booking page (Form)
    Test | Result
    ---|:---:
    Form responsiveness | ok
    Filling out the booking form | ok
    Service hover effect | ok
    Input field effects and animations | ok
    Selecting a service | ok
    Submiting the data | ok
    Returning form data from CodeInstitute API | ok

- ### Gallery
    Test | Result
    ---|:---:
    Imagery grid responsiveness | ok
    Image hover effect | ok

[Back to top](#contents)

## Compatibility Testing
### Browser Compatibility
The website was tested on the following browsers:
- Google Chrome
- Mozilla Firefox
- Microsoft Egde

The site worked well across all browsers and discrepancies were not found.

### Device Compatability and Responsiveness Testing
The website was tested using Google Chrome Developer Tool - Device Mode Toolbar.
#### Tested devices:
- iPhone SE
- iPhone XR
- iPhone 12 Pro
- Pixel 5
- Samsung Galaxy S8+
- Samsung Galaxy S20 Ultra
- iPad Air
- iPad Mini
- Surface Pro 7
- Surface Duo
- Galaxy Fold
- Samsung Galaxy A51
- Nest Hub
- Nest Hub Max

[Back to top](#contents)

## Validator Testing
### HTML Validation
The [W3C Markup Validation](https://validator.w3.org/) Service was used to validate the HTML of the website.
- #### Home Page
[*Click to re-validate this page*](https://validator.w3.org/nu/?doc=https%3A%2F%2Fflashdrag.github.io%2Fbarber-shop%2Findex.html)
![W3C Markup Validation Home Page](validation/homepage-test.png)

- #### Booking Page
[*Click to re-validate this page*](https://validator.w3.org/nu/?doc=https%3A%2F%2Fflashdrag.github.io%2Fbarber-shop%2Fbooknow.html)
![W3C Markup Validation Booking Page](validation/bookingpage-test.png)

- #### Gallery Page
[*Click to re-validate this page*](https://validator.w3.org/nu/?doc=https%3A%2F%2Fflashdrag.github.io%2Fbarber-shop%2Fgallery.html)
![W3C Markup Validation Gallery Page](validation/gallerypage-test.png)

### CSS Validation
The [W3C Jigsaw CSS Validation](https://validator.w3.org/) Service was used to check the CSS style sheet.

*Click to re-validate this page*
<a href="http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fflashdrag.github.io%2Fbarber-shop%2F&usermedium=all&vextwarning=&warning=1">
    <img style="border:0;width:88px;height:31px"
        src="https://jigsaw.w3.org/css-validator/images/vcss"
        alt="Valid CSS!" />
</a>

![Css Validation Result](validation/css-test.png)

### Accessibility and Performance
The [Google Chrome LightHouse](https://developer.chrome.com/docs/lighthouse) was used to do the Web Accessibility and Performance Audit

> Since the initial performance results for mobile devices were around 90, all images were converted to .webp format using [XConvert](https://www.xconvert.com/compress-webp)

- #### Home Page
Desktop | Mobile
:-:|:-:
![Home Page Desktop Google Lighthouse result](validation/home-desktop-lighthouse.png) | ![Home Page Mobile Google Lighthouse result](validation/home-mobile-lighthouse.png)

- #### Booking Page
Desktop | Mobile
:-:|:-:
![Booking Page Desktop Google Lighthouse result](validation/booknow-desktop-lighthouse.png) | ![Booking Page Mobile Google Lighthouse result](validation/booknow-mobile-lighthouse.png)

- #### Gallery Page
Desktop | Mobile
:-:|:-:
![Gallery Page Desktop Google Lighthouse result](validation/gallery-desktop-lighthouse.png) | ![Gallery Page Mobile Google Lighthouse result](validation/gallery-mobile-lighthouse.png)

[Back to top](#contents)

## Bugs
In order to get more performance in Lighthouse tests, optimize image loading speed and consume less cellular data, the main images were converted to the WebP format according to the recommendations [Performance Audits](https://developer.chrome.com/en/docs/lighthouse/performance/uses-webp-images/). But since WebP is a modern image format, it is not supported on some older devices browsers. In this case, the site was tested on an iPhone 5s and the images were not displayed.

[Back to top](#contents)

[Back to README.md](https://github.com/FlashDrag/barber-shop/blob/master/README.md#testing)