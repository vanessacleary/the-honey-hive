Link to live project.

This is the final portfolio


## Site Owner Goals

* Promote candle shop business and increase sales candles
* Increase online status and promote the site on social media
* Encourage the uptake of organic candle

## Demographics

* All genders and ethnicities
* Ages 18+
* Retail purchases not commercial wholesale

## USER STORIES

### As a first time visitor:
* I want to easily navigate throughout the site.
* I want to understand the purpose of the site easily.
* I expect an attractive site that contributes to my good experience.
* I want the site to be accessible.
* I want the site to be responsive across all devices.

### As an unregistered visitor:
* I want to be able to search and filter products easily and efficiently.
* I want to be able to sort and view products according to type, price and name.
* I want to be able to view product details so I can find information about price, size and description.
* I want to be able to add products to my shopping basket.
* I want to be able to view my shopping basket.
* I want to be able to edit my shopping basket.
* I want to be able to view the total cost of my basket.
* I want to be able to complete the checkout process and be able to enter payment information easily.
* I want to be able to view a confirmation of my order once the checkout process is complete.
* I want to be able to receive an email confirmation of my order.
* I want to be able to register easily for an account.
* I want to be able to access the blog posts.

### As a registered visitor:
* I want to be able to receive a confirmation email upon registration.
* I want to be able to view my personalized profile.
* I want to be able to save and edit personal information on my profile.
* I want to be able to view my order history.
* I want to be able to login and logout with ease.
* I want to be able to leave reviews on products.
* I want to be able to edit or delete my reviews.
* I want to be able to leave comments on the blog posts.
* I want to be able to edit or delete comments on blog posts.
* I want to be able to delete my account.
* I want to be able to change my password to keep my account secure.
* I want to be able to reset my password if I forget it.

### As a returning visitor:
* I want to be able to find social media links.
* I want to be able to contact the site owner if I have any queries.
* I want to enjoy using the site without never ending scrolling.

### As a superuser:
* I want to be able to add new products.
* I want to be able to edit or delete existing products.
* I want to be able to add new categories.
* I want to be able to add new blog posts.
* I want to be able to edit or delete existing blog posts.
* I want to be able to delete blog comments left by users.
* I want to be able to delete user reviews left on products.
* I want to be able to access the Django admin portal easily
* I want to be able to delete a user.
* I want to be able to make another user admin.
* I want to be notified when a user fills out the contact form, so I don't have to check the admin portal constantly.



## **TECHNOLOGY USED**

<details>
<summary> Languages and Libraries</summary>

- [Django](https://www.djangoproject.com/) - Python Framework
- [HTML5](https://developer.mozilla.org/en-US/docs/Glossary/HTML5) - Programming Language
- [CSS 3](https://developer.mozilla.org/en-US/docs/Web/CSS) - Programming Language
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - Programming Language
- [Python](https://www.python.org/) - Programming Language
- [Jinja](https://jinja.palletsprojects.com/en/3.0.x/) - Template Language
- [jQuery](https://jquery.com/) - JavaScript Library
- [Bootstrap v4](https://getbootstrap.com/) - Library Import
- [Google Fonts](https://fonts.google.com/) - Typography Import
- [Font Awesome](https://fontawesome.com/) - Icon provider
- [Hover.CSS](https://ianlunn.github.io/Hover/) - Hover.CSS

</details>

<details>
<summary> IDE and Version Control</summary>

- [Git Pod](https://gitpod.io/) - IDE (Integrated Development Environment)
- [Git](https://git-scm.com/) - Version Control Tool
- [Github](https://github.com/) - Cloud based hosting service to manager my Git Repositories
- [Code Institute GitPod Template](https://github.com/Code-Institute-Org/gitpod-full-template) - Provides GitPod extensions to help with code production
</details>

<details>
<summary> Design and Development</summary>

- [Google Chrome Development Tools](https://developer.chrome.com/docs/devtools/) - Design/Development Tools
- [Balsamiq](https://balsamiq.com/) - Wireframe designer software
- [Coolors](https://coolors.co/) - Colour scheme generator
- [Lucid App](https://lucid.app/) - Diagram creator
- [Draw.io](https://app.diagrams.net/) - Flow chart creator
</details>

<details>
<summary> Validation and Testing</summary>

- [CSS Beautifier](https://www.freeformatter.com/css-beautifier.html) - Beautifying CSS Code
- [JavaScript Validator](https://beautifytools.com/javascript-validator.php) - Validating JS code
- [Am I Responsive?](http://ami.responsivedesign.is/) - Webpage Breakpoint visualizer and image generator
- [Black](https://black.readthedocs.io/en/stable/)- Code Formatter
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/)
- [Browser Stack Responsive Design Tester](https://www.browserstack.com/responsive)
- [Media Genesis RESPONSIVE WEB DESIGN CHECKER](https://responsivedesignchecker.com/)
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [pylint](https://pylint.org/)
</details>

<details>
<summary> Documentation</summary>

- [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables) - Markdown Table Production
- [Table Converter](https://tableconvert.com/excel-to-markdown) - Excel to Markdown table converter 
</details>



## Testing First time User Stories 
 
  * I want to easily navigate throughout the site.
    * The website has a navbar that will allow all users to navigate around the website on any device 
        * Desktop Nav
        ![](readme/assets/testing-images/nav.png)

        * Mobile Nav
        ![](readme/assets/testing-images/nav-mobile.png)
---------------------------------------------------------------------------------------------------------------------------
 * I want to understand the purpose of the site easily.
    * On the homepage there is an 'About' section which tells the story about what The HoneyHive is about 
    * The Homescreen image allow website visitors about what the purpose of the website.
---------------------------------------------------------------------------------------------------------------------------

* I expect an attractive site that contributes to my good experience.
    * The colours, style and layout have been choosen to enure a good user expierence. 
    * Design aspects and products have been taken from other Beeswas websites - see credits for more information

---------------------------------------------------------------------------------------------------------------------------

* I want the site to be accessible.
    * All anchor links have aria-labels, images have alt attributes and the colours pass the Lighthouse accessibility checks. 
    * Placeholders and form labels have been used throughout to ensure accesbility is available throughout the site. 

---------------------------------------------------------------------------------------------------------------------------

* I want the site to be responsive across all devices.
    * Throughout development responsiveness has been considered. 
    * Using Bootstrap and media queries the site is accessible across all devices.

---------------------------------------------------------------------------------------------------------------------------

### Overview of First time user stories 
<p> the stories have been staisfied for each story set out for first time users </p>

---------------------------------------------------------------------------------------------------------------------------

## Testing Unregistereds User Stories 

* I want to be able to search and filter products easily and efficiently.
    * A searchbar input field allows users to search by product, description or category. 
    * Product category badges allow users to filter which category they want to look at. 
    * Navbar dropdown menus have categories listed so users can easily filter which products users want to look at. 

---------------------------------------------------------------------------------------------------------------------------

* I want to be able to sort and view products according to type, price and name.
    * The sort selector dropdown allows users to sort products based on price, name or category

---------------------------------------------------------------------------------------------------------------------------

* I want to be able to view product details so I can find information about price, size and description.
    * The product detail page displays product information clearly for the user

---------------------------------------------------------------------------------------------------------------------------

* I want to be able to add products to my shopping basket.
    * On the product detail page an 'Add to basket' button allows users to add products to their bags.

---------------------------------------------------------------------------------------------------------------------------

* I want to be able to view my shopping basket.
    * Users can click on shopping basket icon in navbar or 'Proceed to basket' button on toast message. 
    * The basket page displays all products added to basket and an order summary.

---------------------------------------------------------------------------------------------------------------------------

* I want to be able to edit my shopping basket.
    * A quantity selector dropdown allows users to change the quantity and use the update link to update the amount. 
    * The remove link allows users to remove item completely from their basket

---------------------------------------------------------------------------------------------------------------------------

* I want to be able to view the total cost of my basket.
    * In the shopping basket page the total cost with breakdown of order total and delivery cost are displayed. 
    * Total cost of basket is also displayed in toast messages if the user is not on the basket or profile pages. 

---------------------------------------------------------------------------------------------------------------------------

* I want to be able to complete the checkout process and be able to enter payment information easily.
    * The checkout page displays checkout form. This is clearly labelled with input labels and placeholders.
    * Stripe card payment section is available for card payments

---------------------------------------------------------------------------------------------------------------------------


