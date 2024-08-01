# E Shop

E Shop is an e-commerce store . The site is targeted towards users who want to shop conveniently from home and get the products delivered to home.
The site provides a seamless online shopping experience, offering a wide range of high-quality products at competitive prices.

Users can browse and purchase a wide range of products or check out the different types of Products and make an enquiry. They can also look at images and testimonials of other Customers or leave a testimonial if they wish.

The payment system uses Stripe. Please note that this website is for educational purposes do not enter any personal credit/debit card details when using the site.

To test this system, test card details can be used. A list of these can be found in Stripe's documentation [here](https://stripe.com/docs/testing#cards).

The live link can be found here - [E Shop](https://e-shop-app-0892571914c8.herokuapp.com/)

![Site Mockup](docs/readme_images/site_mockup.png)

- [User Experience (UX)](#user-experience--ux-)
  * [User Stories](#user-stories)
  * [Design](#design)
    + [Colour Scheme](#colour-scheme)
    + [Imagery](#imagery)
    + [Fonts](#fonts)
    + [Wireframes](#wireframes)
- [Agile Methodology](#agile-methodology)
- [Database Schema](#database-schema)
- [Security Features and Defensive Design](#security-features-and-defensive-design)
  * [User Authentication](#user-authentication)
  * [Form Validation](#form-validation)
  * [Database Security](#database-security)
  * [Custom error pages:](#custom-error-pages-)
- [Features](#features)
  * [Header](#header)
  * [Footer](#footer)
  * [Home Page](#home-page)
  * [User Account Pages](#user-account-pages)
  * [Profile](#profile)
  * [Products](#home-decor--products-)
  * [Product Detail](#product-detail)
  * [Bag](#bag)
  * [Checkout](#checkout)
  * [Testimonials](#testimonials)
  * [Customer Reviews ](#testimonials)
  * [Contact Form](#contact-form)
  * [Enquiries Dashboard](#enquiries-dashboard)
  * [Error Pages](#error-pages)
- [Business Model](#business-model)
- [Marketing Strategy](#marketing-strategy)
  * [SEO](#seo)
  * [Content marketing](#content-marketing)
  * [Social Media Marketing](#social-media-marketing)
  * [Email Marketing](#email-marketing)
- [Testing](#testing)
- [Deployment - Heroku](#deployment---heroku)
- [AWS Set Up](#aws-set-up)
- [Forking this repository](#forking-this-repository)
- [Cloning this repository](#cloning-this-repository)
- [Languages](#languages)
- [Frameworks - Libraries - Programs Used](#frameworks---libraries---programs-used)
- [Credits](#credits)
- [Acknowledgments](#acknowledgments)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>





## User Experience (UX)

A visitor to E Shop would be someone who is most likely an adult who is interested in buying Quality products at reasonable prices conviniantly.

### User Stories

#### EPIC | Viewing and Navigation
- As a Site User, I can intuitively navigate around the site so that I can find content.
- As a Site User, I can view a list of products so that I can select a product to view.
- As a shopper, I can click on a product so that I can read the full product details.
- As a shopper, I can view a specific category of products so I can browse the type of products I'm looking for.
- As a shopper, I can search all products so that I can find what I am looking for.
- As a shopper, I can sort all products so that I can view products based on price or title.
- As a site user, I can view a list of Products so I can understand the quality and discription of the Product and make an enquiry if desired.
- As a site user, I can read testimonials left by other customers so I see what feedback they gave to their shopping experience with the store.
- As a site user, I can view pictures and the read the Views of other customers about the products and overall shopping experience with the Store so that I can      see quality of the products and credibility of the store and build trust on the Store.

#### EPIC | User Account and Profile
- As a site user, I can register an account so that I can have a personal account.
- As a site user, I can log in or log out of my account so that I can keep my account secure.
- As a site user, I can see my login status so that I know if I'm logged in or out.
- As a site user, I can save my personal details in my user profile so that I do not have to fill them out for future orders.
- As a site user, I can view my order history so that I can remember what purchases I've made.
- As a site user, I can recover my password in case I forget it so that I can recover access to my account.

#### EPIC | Purchasing
- As a shopper, I can add a number of products in different quantities to my shopping bag so that I can purchase them all together when I am ready.
- As a shopper, I can view a running total of my shopping bag as I am shopping so that I can see how much it costs in total.
- As a shopper, I can view the contents of my shopping bag at any time so I can see what is included and the total cost.
- As a shopper, I can adjust the quantity of individual products in my bag so that I can easily make changes before I purchase.
- As a shopper, I can see a summary of my shopping cart when I checkout so that I know what products are included and the total cost before I commit to purchasing.
- As a shopper, I can easily enter my payment information securely so that I can purchase my chosen products quickly with no issues.
- As a shopper checkout as a guest so I don't have to sign up for an account.
- As a shopper, I can view an order confirmation after checkout so that I know my purchase was successful.
- As a shopper, I can receive an email confirmation of my order so that I have a record of my purchase.


#### EPIC | Admin & Store Management
- As a store owner, I can add/edit/delete products through an easy-to-use interface so that I can manage the store's contents.
- As a site owner, I can view/read/ customer reviews through an easy-to-use interface so that I can manage the site's contents.
- As a site owner, I can add/delete images and description of products so that I can manage the site's contents.
- As a site owner, I can view, read, Reply and delete customer enquiries on The webpage without going to Admin page.

#### EPIC | User Interaction
- As a site user, I can submit an enquiry form so that I can enquire about a Product.
- As a site user, I can add / edit / delete a testimonial in relation to my perchase experience so that I can give my feedback.
- As a site user, I can add / edit / delete a review and give Rating to Products so that I can express my satisfaction about a product and the Store.

#### User stories not yet implemented

The following user stories were scoped out of the project due to time constraints and labelled as "Won't Have" on the project board on Github. It is intended that these user stories will be implemented at a later date.

- As a shopper, I can add products to my saved items so that I can go back and view them at a later date.
- As a shopper, I can view my saved products so I can find them easily in the one location.


### Design

The site has a vibrant and clean design with the use of Orange and white color combination to give the idea of luxury and opulence. 
#### Colour Scheme
Colour palette from Coolors

![Colour Scheme](docs/readme_images/colour_scheme.png)

The colour scheme of the site is mainly Orange and White. The colours chosen are quite neutral in order to showcase the Products with minimal distraction. 

Great care was taken to establish a good contrast between background colours and text at all times to ensure maximum user accessibility.

#### Imagery
There is only one main static image on the site which is of a laptop and a shopping Cart on the home page. The color scheme of the site makes a good contrast with the main homepage image which largely consists of orange and White. The rest of the imagery will be uploaded by the site owner for individual products. 

#### Fonts
The Lato font is the main font used for the body of the website. This font was imported via Google Fonts. Sans Serif is the backup font, in case for any reason the main font isn't being imported into the site correctly.

#### Wireframes

<details>

 <summary>Home Page</summary>

![Home Page](docs/wireframes/landing-page.png)
</details>

<details>

 <summary>Product Details Page</summary>

![Product Details](docs/wireframes/Product-details.png)
</details>

<details>

 <summary>Customers Reviews</summary>

![Customers Reviews](docs/wireframes/reviews-page.png)
![Customers Reviews](docs/wireframes/add-review-page.png)
</details>

<details>

 <summary>Testimonials</summary>

![Testimonials](docs/wireframes/testimonials-Page.png)
</details>

<details>

 <summary>Contact</summary>

![Contact](docs/wireframes/Contact-page.png)
</details>

<details>

 <summary>Bag</summary>

![Shopping Bag](docs/wireframes/shopping-bag.png)
</details>

<details>

 <summary>Checkout</summary>

![Checkout](docs/wireframes/checkout.png)
</details>

<details>

 <summary>Order Confirmation</summary>

![Order Confirmation](docs/wireframes/order-confirmation.png)
</details>

<details>

 <summary>Enquiries</summary>

![Enquiries](docs/wireframes/Enquiries-page.png)
![Enquiries](docs/wireframes/enqury-page.png)
</details>

<details>

 <summary>Profile</summary>

![Profile](docs/wireframes/profile-page.png)
</details>

<details>

 <summary>Product Management</summary>

![Product Management](docs/wireframes/Products-manage-page.png)
</details>

<details>

 <summary>Sign Up </summary>

![Sign Up](docs/wireframes/signup.png)
</details>

<details>

 <summary>Log In</summary>

![Log In](docs/wireframes/Login-Page.png)
</details>

<details>

 <summary>Sign Out</summary>

![Sign Out](docs/wireframes/signout-page.png)
</details>

## Agile Methodology
Github projects was used to manage the development process using an agile approach. Please see link to project board [here](https://github.com/users/)


The 5 Epics listed above were documented within the Github project as Milestones. A Github Issue was created for each User Story which was then allocated to a milestone(Epic). Each User Story has defined acceptance criteria to make it clear when the User Story has been completed. The acceptance criteria are further broken down into tasks to facilitate the User Story's execution.

## Database Schema 

Two relational databases were used to create this site - during production SQLite was used and then Postgres was used for the deployed Heroku version. Below is an image of how the database models relate to each other:

![Database Schema](docs/readme_images/database_schema.png)

## Security Features and Defensive Design
### User Authentication

Where I have used Django's Class-based-views; Django's LoginRequired is used to make sure that any requests to access secure pages by non-authenticated users are redirected to the login page. Django's UserPassesTest is used to limit access based on certain permissions i.e. to ensure users can only edit/delete Testimonials for which they are the author or if the user is the superuser. If the user doesn't pass the test they are shown an HTTP 403 Forbidden error.

Where I have used function based views I have used Django's login_required and user_passes_test decorators to restrict access as required. 

### Form Validation
If incorrect or empty data is added to a form, the form won't submit and a warning will appear to the user informing them what field raised the error.

### Database Security
The database url and secret key are stored in the env.py file to prevent unwanted connections to the database. Stripe keys and wh secret are also stored in the env.py file. 

Cross-Site Request Forgery (CSRF) tokens were used on all forms throughout this site.

### Custom error pages:
Custom Error Pages were created to give the user more information on the error and to provide them with buttons to guide them back to the site.

400 Bad Request - E Shop is unable to handle this request.
403 Page Forbidden - Looks like you're trying to access forbidden content. Please log out and sign in to the correct account.
404 Page Not Found - The page you're looking for doesn't exist.
500 Server Error - Due to an internal error we are unable to process this request.


## Features

### Header
![header](docs/readme_images/features/header.png)

**Logo**
- A customised logo was created using LOGO.com which is a free logo generator.
- This logo is positioned in the top left of the navigation bar. The logo is linked to the home page for ease of navigation for the user.

**Navigation Bar**

- The navigation bar is visible at the top of every page and includes links to the other pages.

**Search Bar**

![Search](docs/readme_images/features/search.png)
- The search bar displays above the nav bar.
- On smaller screens, this bar becomes a search icon which when clicked will drop down the full bar.
- Any searched word will match itself to any text in the product's title, or description and display the results on the product's page.


**User Icon**


- The User icon navigation link is a drop down menu which includes the Sign up and Log in links. 
- Once a user has signed in, their username will display below the user icon.
- The options to Sign up or Log in will change to the option to log out once a user has logged in.
- Once a user has signed in, the 'My Profile' option becomes available in the User dropdown.

![Logged In](docs/readme_images/features/logged_in.png)
- If the superuser has signed in, more options such as 'Products Management' become available in the User dropdown.

![user menu](docs/readme_images/features/superuser_login.png)
- The navigation bar is fully responsive, collapsing into a hamburger menu when the screen size becomes too small.
- Hovering over the links will turn the font Black.

**Bag Icon**

![bag](docs/readme_images/features/bag.png)
- Located on the right side of the navbar next to the User icon is the bag Icon.
- Once a product is added to the bag, a number displaying the total quantity of items appears, located at the top right of the bag icon.
- As the user adds products to their bag, a toast message appears in the top right-hand corner of the screen informing the user that the item has been added, giving them a snapshot of the bag contents and the total cost of the bag.

![bag total](docs/readme_images/features/bag_total.png)
- Clicking the bag icon navigates the user to the shopping bag page which displays a summary of what's been added.

### Footer

![footer](docs/readme_images/features/footer.png)

- The footer appears at the bottom of every page.
- The footer section includes links to Facebook, Instagram, Twitter , linkedin , Github , and Google.
- There is a newsletter signup section powered by Mailchimp where the user can input their email address to signup to the monthly newsletter.
- The Quick Links section has links to the main parts of the site including 'Contact Us' and 'Privacy Policy'.
- On the right hand side of the footer there are Contact links like, telephone number Fax , Email adress and Business Adress.
### Home Page


![Home page](docs/readme_images/features/home_page.png)

- The home page includes an apealing layout which encourages the user to 'shop now' or to browse "All Products" with the message "CHECK OUT OUR LATEST COLLECTION" and a stylish online shopping background. 

### User Account Pages

**Sign Up**

![Sign Up](docs/readme_images/features/sign_up.png)

**Sign In**

![Sign In](docs/readme_images/features/sign_in.png)

**Log Out**

![Sign Out](docs/readme_images/features/sign_out.png)

- Django allauth was installed and used to create the Sign up, Log in and Log out functionality. 
- Success messages inform the user if they have logged in/ logged out successfully.
- When a user signs up for an account they must verify their email address by clicking on the authentication link emailed  to the address they provided.
- If a user forgets their password they can reset it by clicking the 'Forgot Password' on the log in page.


### Profile
**Delivery Details**

![Delivery Details](docs/readme_images/features/delivery_info.png)
- The delivery details section stores the user's delivery address and phone number.
- The information provided here is used to autofill the delivery address when placing an order.

**Order History**

![Order History](docs/readme_images/features/order_history.png)
- The order history section displays a list of every order the user has placed.
- The table displays the order number, date it was ordered and the order total.
- Clicking the order number will take the user to a summary page of that order.

### Products

![all products](docs/readme_images/features/products_all.png)
- When clicking the 'All products' link in the navbar the dropdown menu will show all the different categories.

![Categories](docs/readme_images/features/categories.png)
- The 'All Products' link will display a list of all products from the database.
- Clicking any of the categories will filter the products to only show products from the category selected.
- The category selected will display as the page heading.

![products](docs/readme_images/features/products.png)


- Each product card shows an image of the product, its title, excerpt and price.
- If the user is a superuser, edit and delete buttons will appear at the bottom of the product card.
- The products page is fully responsive, adjusting how many products are on each row depending on the user's screen size.
- A sort box is located on the products page where users can sort all products by price in ascending or descending order and by title (A-Z).

![sort](docs/readme_images/features/sort.png)

### Product Detail

![Product Detail](docs/readme_images/features/product_detail.png)
- When the user clicks on an individual product card they are taken to the full product details. The link is a bootstrap stretched link so clicking anywhere on the card will work.
- The product detail page displays the product image, title, excerpt, price, product details.
- If the user is a superuser, edit and delete buttons will appear below these details.

**Quantity Buttons**
- The quantity buttons are located underneath the product details and are used to add items to the bag.
- The plus and minus buttons increase and decrease the input value.
- If the value is set to 1 the minus quantity will be disabled. Respectively if the value is set to 99 the plus button is disabled.
- If the user manually types in a negative number or a number >99 and clicks "Add to Bag" an error button will appear informing the user of the parameters needed to be successful.
- Clicking the 'Add to Bag' button takes the number in the input field and adds that amount of products to the bag.
- Clicking the 'Keep Shopping' button takes the user back to the store.

### Product Management
**Add Product**

![add product](docs/readme_images/features/add_product.png)
- The add product page can be accessed by clicking the 'Add Product' button on the Product Management page or in the user dropdown menu, under the User . These options are only visible to superusers.
- If a user tries to add a product (by changing the url) without being a superuser they are redirected to a custom 403 page.
- The user must fill out all the fields that have an Asterix. If the form is submitted with any of these fields left blank or with just whitespace then an error message will appear above that particular field, notifying the user of the issue.
- The SKU field must be unique. An error message will appear if the SKU already exists.
- If a price is added with more than 6 digits the form will fail and an error message will appear under the price field.
- The user can upload a photo if they wish. If they choose not to, a default image displays as their product image.
- Clicking the 'Add Product' button at the bottom of the form will create the product providing there are no errors on the form.
-  The user will receive a success message notifying them that the product has been successfully added.

**Edit Product**

![edit product](docs/readme_images/features/edit_product.png)
- The superuser can choose to edit a Product by clicking the edit button on the product card or on the product detail page. 
- The form opens with all fields populated with the original content.
- The image field displays a thumbnail of the existing image and has a checkbox option to remove it. Checking this will change the image to the default image.
- If a user tries to add a product (by changing the url) without being a superuser they are redirected to a custom 403 page.
- The superuser will receive a success message notifying them that the product has been successfully updated.

**Delete Product**

![delete product](docs/readme_images/features/delete_product.png)
- The superuser can choose to delete a Product by clicking the delete button on the product card or on the product detail page. 
- The superuser is asked to confirm if they wish to delete the product or cancel.
- The superuser will receive a success message notifying them that the product has been successfully deleted.

### Bag

![shopping bag](docs/readme_images/features/shopping_bag.png)
- When the user clicks on the shopping bag icon in the nav bar they are taken to the shopping bag page which shows the products which the user has added to their cart, unit price, quantity and subtotal.

**Quantity Buttons**
- The quantity input box displays the product quantity the user has added to their bag.
- The plus and minus buttons increase and decrease the input value.
- If the value is set to 1 the minus quantity will be disabled. Respectively if the value is set to 99 the plus button is disabled.

**Update and Delete Buttons**

![Update Delete buttons](docs/readme_images/features/update_delete_buttons.png)
- Clicking the 'update' icon button saves any changes to the quantity and updates the item's subtotal.
- Clicking the 'Bin' icon button removes the item completely from the user's bag.
- If the user manually types in a negative number and clicks 'update', the item will be removed from the item from the bag.
- If the user manually types in a number >99 and clicks 'update' an error message will display informing the user of the correct parameters.

**Total Section**
- At the end of the line items is a summary of the costs.
- The summary features the bags total, delivery cost and the grand total to pay.
- Underneath the grand total users will find a message informing them of how much more they need to spend to receive free delivery if they haven't already met the free delivery threshold (€50). 
- Beneath the grand total is two buttons. From here the user can either continue to the checkout or return to the products page by clicking 'Continue Shopping'.

### Checkout 

![checkout](docs/readme_images/features/checkout.png)

**Details**
- Within the details section the user can fill out their contact details, delivery address, and card number.
- If the user is a guest, a link to create an account or login will be present.
- If the user is signed in a checkbox to save the delivery information can be checked.
- If the user is signed in and has delivery information saved, the delivery details and email address will be automatically filled in.
- If a user leaves a required field empty, inputs whitespace in a required field or includes text in the phone number field an error message will prompt the user to 'Fill in the field' or 'match the format requested'

**Order Summary**
- The order summary section details all the items about to be purchased, along with the quantity, subtotal and a grand total.
- Next to the order summary title will be a number reflecting the total number of items that appear in the order.
- Clicking the product image in the summary will take the user to that product's detail page.

**Payment**
- The card payment is handled by Stripe to ensure secure payment.
- Incorrect card numbers will automatically show an invalid card number error.
- A loading screen will appear when a payment is being processed to stop the user clicking away.
- There is a warning message at the bottom of the page informing the user of how much their card is about to be charged.
- If the payment form doesn't submit properly or the user closes the browser during the wait animation, the order will still be created in the database through the webhook. 
- Once the payment is processed, the webhook will search the database to confirm the order exists. If it cannot find it, it will create one using the payment information.

**Confirmation**

![order_confirmation](docs/readme_images/features/order_confirmation.png)
- Once the order has been processed the user is taken to the checkout success page.
This page summarises the completed order.
- An email will be sent to the user with their order confirmation
- At the end of the summary is a 'Keep Shopping' button that takes the user back to the Products page.

### Testimonials

![Testimonials](docs/readme_images/features/testimonials.png)
- The testimonials page can be accessed by clicking the link in the nav bar.
- When the user navigates to the Testimonials page they can see all testimonials left by previous clients. 
- Each testimonial displays the Topic they relate to, the date and the user's name.

**Add Testimonial**

![Add Testimonial](docs/readme_images/features/add_testimonial.png)
- When a logged-in user clicks on the "Add Testimonial" button on the Testimonials page, they can see a user-friendly form where they can add a new Testimonial to the site.
- If the user is not logged in they are redirected to the log-in page.
- The completed testimonial is automatically populated with the user's username and date underneath the body.

**Edit Testimonial**

![Edit Testimonial](docs/readme_images/features/edit_testimonial.png)
- The user is able to edit their own testimonials by clicking the edit button which display beside their own testimonial on the Testimonials Page.
- The edit form fields are pre-populated with the existing testimonial text.
- If a user tries to update a testimonial (by changing the url) without being signed in they are redirected to the log in page.
- If a user tries to update another user's testimonial (by changing the url) they receive a custom 403 error.
- The superuser can edit anyone's testimonial.
- The user will receive a success message notifying them that the testimonial has been successfully updated.

**Delete Testimonial**

![Delete Testimonial](docs/readme_images/features/delete_testimonial.png)
- The user can choose to delete their own testimonial by clicking the delete button which display beside their own testimonial on the Testimonials Page.
- The user is asked to confirm if they wish to delete the testimonial or cancel.
- The user will receive a success message notifying them that the testimonial has been successfully deleted.
- If a user tries to delete a testimonial (by changing the url) without being signed in they are redirected to the log in page.
- If a user tries to delete another user's testimonial (by changing the url) they receive a custom 403 error.
- The superuser can delete anyone's testimonial.

### Contact Form

![Enquiry Form](docs/readme_images/features/enquiry_form.png)
- A user can open up the contact form by clicking on the "Enquire Now" button  by clicking the 'Contact' button in the Nav bar.
- If the user is logged in, the email field is prepopulated with the user's email address. 
- The form contains a drop down menu where the user can select the type of enquiry from a list so that the site owner knows what the enquiry is about.
- The user must fill out all the fields that have an Asterix. If the form is submitted with any of these fields left blank or with just whitespace then an error message will appear above that particular field, notifying the user of the issue.
- When the form is submitted, the user receives an email confirmation of their enquiry so that they have a record of it.

### Enquiries Dashboard

![Enquiries Dashboard](docs/readme_images/features/enquiry_dashboard.png)
- When the site owner is logged in, an Enquiries Management option appears in the User drop-down menu.
- When the site owner navigates to the Enquiries Management page they can see a list of user enquiries sorted from newest to oldest.
- Emails that have been read are greyed out.
- When the site owner clicks on an enquiry they are taken to the individual enquiry detail.

![Enquiry Detail](docs/readme_images/features/enquiry_detail.png)
- The site owner can choose to delete the enquiry or to go back to the list of enquiries.

### Customer Reviews 

![Reviews](docs/readme_images/features/testimonials.png)
- The Reviews page can be accessed by clicking the link in the nav bar.
- When the user navigates to the Reviews page they can see all Reviews left by previous Customers. 
- Each Reviews displays the Topic they relate to, the date and the user's name.

**Add Review**

![Add Reviews](docs/readme_images/features/add_testimonial.png)
- When a logged-in user clicks on the "Add Reviews" button on the Nav bar link under More, they can see a user-friendly form where they can add a new Reviews to the site.
- If the user is not logged in they are redirected to the log-in page.
- The completed Review is automatically populated with the user's username and date underneath the body.

**Edit Review**

![Edit Review](docs/readme_images/features/edit_testimonial.png)
- The user is able to edit their own Reviews by clicking the edit button which display beside their own Reviews on the Reviews Page.
- The edit form fields are pre-populated with the existing Review text.
- If a user tries to update a Review (by changing the URL) without being signed in they are redirected to the log in page.
- If a user tries to update another user's Review (by changing the url) they receive a custom 403 error.
- The superuser can edit anyone's Reviews.
- The user will receive a success message notifying them that the Review has been successfully updated.

**Delete Review**

![Delete Review](docs/readme_images/features/delete_testimonial.png)
- The user can choose to delete their own Review by clicking the delete button which display beside their own Review on the Reviews Page.
- The user is asked to confirm if they wish to delete the Review or cancel.
- The user will receive a success message notifying them that the Review has been successfully deleted.
- If a user tries to delete a Review (by changing the url) without being signed in they are redirected to the log in page.
- If a user tries to delete another user's Review (by changing the url) they receive a custom 403 error.
- The superuser can delete anyone's Reviews.


### Error Pages
Custom Error Pages were created to give the user more information on the error and to guide them back to the site.

![403 error](docs/readme_images/features/403_error.png)


- 400 Bad Request - E Shop is unable to handle this request.
- 403 Page Forbidden - Looks like you're trying to access forbidden content. Please log out and sign in to the correct account.
- 404 Page Not Found - The page you're looking for doesn't exist.
- 500 Server Error - Due to an internal error we are unable to process this request.

## Business Model

E Shop's Business Model is Business to Consumer (B2C). Products and services are sold directly from E Shop to consumers who are the end-users. 
A customer of E Shop would be someone who is most likely an adult who is interested in buying luxurious interior products and high end interior design services.

## Marketing Strategy

A number of different marketing strategies have been utilised to promote E Shop including SEO, content marketing, social media marketing and email marketing. Each of these strategies have been discussed individually below:  

### SEO
Several SEO techniques were undertaken in order to ensure the site ranks highly in search engine results:

**Keywords:** 

A mixture of short tail and long tail keywords were carefully considered for the site. Keyword research was performed by checking Google search results, looking at competitor's keywords and by utilising wordtracker.com. 

An initial list of topics and keywords generated can be seen below. This list was then refined based on relevance and authority.

The most relevant keywords have been added to the site's meta-keywords and meta-description. These keywords have also been carefully included in page titles, headings, site content, `<strong></strong>` tags, image alt attributes and anchor tag links across the site. 

 ![Keywords](docs/readme_images/seo_keywords.png)

**External Links:**

Included in the site footer are links to other high quality relevant websites including Houzz, Institute of Designers Ireland, and The Interiors Association. These links show search engines that the page is of good quality improving the site's ranking further. 

**Building Trust:**

In order to build brand trust, a testimonial page for interior design services has been included in the site with a link to the page being included in the page footer as well as the main nav bar. 

The page footer also includes links to the privacy policy to inform users about how their data is being collected and processed.

**Sitemap and robots.txt**

A sitemap file with a list of important page URLs was created to ensure that search engines are able to understand the site's structure and easily navigate through the site. This was made using xml-sitemaps.com.

A robots.txt file was created to tell search engines where they are not allowed to go on the website. This improves SEO by increasing the quality of the site

### Content marketing 
The site showcases high quality images of previous interior design projects projects in order to attract potential new clients. The photos allow the business to show off their expertise and style and build up trust with the customer.

### Social Media Marketing 
For this site, a Facebook business page has been created for organic social media marketing. The Facebook page includes a 'Shop Now' button which takes the user to the E Shop website. The page pairs well with the content media marketing on the main site as images of previous projects and new product arrivals can be shared easily.

![Facebook Page](docs/readme_images/facebook_page.png)

### Email Marketing
Visitors to the site can sign up to the newsletter and do not need to have an account to do so. A signup box is included in the footer of the site. This allows the business to share news with customers and potential customers including new products/services and special offers. Mailchimp was used to create this service. 
