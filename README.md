# NEXUS TECH

Nexus Tech is a single page website for a business that builds custom computers for both commercial and non-commercial clients with system requirements specifically tailored to the customers needs.

![Screenshot of Nexus Tech website on multiple devices to demonstrate responsive design.](assets/images/responsive-design.PNG)

## Features

- ### Navigation Menu
  
  - The navigation menu contains links to the Home page via both the 'Home' button and the logo itself, the 'What We Do' section and the 'Contact Us' section.
  - The menu will follow the user as they navigate up and down the webpage to provide quick and easy access to any section at the click of a button.

![Screenshot of navigation menu.](assets/images/navigation-menu.PNG)

- ### Hero Image

  - The hero section of the page displays an image overlayed with the business slogan 'Experience the pinnacle of personalised computing.'
  - The section uses an image to depict an example of a customer enjoying use of their own personalised system, and below this is a short short description of the business.

![Screenshot of hero image section.](assets/images/hero-image.PNG)

- ### What We Do Section

  - The What We Do section goes into further detail about what the business does.
  - Surrounding a responsive image of a graphics card are the four key principles thea Nexus Tech have to offer.

![Screenshot of What We Do section.](assets/images/what-we-do.PNG)

- ### Contact Us Section

  - This section offers the user a form to fill our where they can leave their name and email address and send a message to Nexus Tech to get in touch about developing their own personalised system/systems.

![Screenshot of enquiry form.](assets/images/contact-us-form.PNG)

- ### Footer

  - The footer of the page provides the user with links to follow Nexus Tech on Facebook, Instagram, Twitter and YouTube.
  - Each of the four links will open in a new tab to prevent the user from losing their page on the Nexus Tech website while they navigate to social media.

![Screenshot of the website footer.](assets/images/footer.PNG)

- ### Future Ideas

  - A page do display customer reviews and ratings for the service that they have received.
  - A gallery page to show off images of previous builds that have been developed for past customers.

## Testing

- The website has been tested on a variety of different browers such as Chrome, Firefox, Opera and Safari.
- The website has also been tested on a number of different devices of varying screen sizes.
- All areas of the site are readable on all browsers and devices that have been tested.
- The enquiry form has been tested, all required fields will not allow the used to submit content if left blank and the email field must contain an email addresss for the form to be sent.

### Bugs

- The navigation bar covered part of the What We Do and Contact Us sections when their links were clicked.
- This issue was resolved by using a scroll-margin selector with a size equal to the height of the navigation menu.
- The webpage was displaying wider than viewport width and thus the user had to scroll horizontally to view all content.
- This problem was rectified by ensuring that the width of all child elements did not exceed the width of their parent.
- What We Do section became jumbled at display widths of 1379px - 1414px and 2211px and above.
- Giving the attribute description paragraphs within the What We Do section a max-height fixed this issue.
<!-- - Poor performance rating was returned when running the website through lighthouse in devtools.
- Images were all reduced in size to ensure that they were no bigger than necessary and file types were converted to '.webp'. -->

### Validation Testing

- HTML
  - All HTML code has been run through the official HTML validator at <https://validator.w3.org/> and no errors were returned. Notes were displayed due to 'trailing slash on void elements' due to the Codeanywhere IDE adding a forward slash to specific elements upon saving, such as "br /". After reviewing the br element and other subsequent elements on <https://developer.mozilla.org/en-US/docs/Web/HTML> this is shown as correct syntax.
- CSS
  - All CSS code has been run through the official CSS validator at <https://jigsaw.w3.org/css-validator/> and no errors were returned.
- Accessibility



### Unfixed Bugs

No apparent bugs remain unfixed.

## Deployment

- The webbsite has been deployed using GitHub pages. To do this the following procedure has been used:
  - Go to the settings tab in the GitHub repositary.
  - Navigated to 'Pages' from the menu, under 'Code and automation'.
  - Ensure that Master Branch is selected from the 'Deploy from a branch' dropdown menu underneath 'Source'.
  - The link to the webpage was provided upon selecting a source.

A link can be followed to the live website here: [Nexus Tech](https://eddy-bryan.github.io/nexus-tech/)

## Credits

### Content

- 

### Media

- 