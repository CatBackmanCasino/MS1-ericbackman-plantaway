# PlantAway


[Link to live site](https://catbackmancasino.github.io/MS1-ericbackman-plantcation/)


Even the most urban city slicker of the concrete jungle can appreciate the fresh air and the different shades of green that houseplants provide, but we don't always have the time to care for them. We travel for work, for vacation, to friends and family and some of us live hectic lives and simply forget about them.

We cannot help with your planning, but we can provide simple ways to keep your plants alive. 

This site will make sure you always return to a green home while you're off living life to its fullest.

![Responsive Mock-up](assets/images/readme-images/ami-responsive.png)


## User Stories

- First time visitors:
    - As a first-time visitor I find the site via a search engine searching for a way to keep my plants alive.
    - When I reach the site, I want to quickly find adequate information about the products.
    - The information and illustrations need to convince me that
        - The site is reliable.
        - The products are functional
    - As a first-time visitor I need the process of purchase to be easy.

- Returning visitors:
    -   As a returning visitor I already know what I want and quickly want to arrive at the purchase form.
    - I want to know if there are any new products without making my goal of purchase any less easy.

## Features 

I wanted to create a very simple visual language that corresponds with the company’s brand. A simple and effective language with a positive vibe that gives no place for unnecessary features. Each feature is there for a reason.

### Intro Animation

I wanted the first impression to be simple yet fun. The intro does just that. It's unexpected and shows a childish and almost retro feeling while also hinting to the travel aspect of the business idea by greeting the customer in four different languages.

![Intro](assets/images/readme-images/intro.png)

- Navigation Bar

 The site has a navigation bar fixed to the top of the view window to make it easy for the potential shopper to navigate through the different sections.
 By clicking any of the links the user will be transported to the corresponding area of the site. 
 Depending on screen size there will be either a hamburger dropdown or a regular header.

![Nav Bar](assets/images/readme-images/large-screen-nav.png)

![Nav Bar](assets/images/readme-images/small-screen-nav.png)

- __The landing page image__

The first thing to catch your eye is a picture of our founder and a quote that makes the visitor feel the business is trustworth. There are millions of sites out there so creating a personal connection with the customer makes all the difference. This gets us one step closer. By ending the section with a positive quote, we send the visitor to the next section with a positive feeling.

![Landing Page](assets/images/readme-images/landing-image.png)

## Quote/Showcase
This section is used to either showcase a new product or any other news regarding the company and its products. If there are nothing new to tell there will be a positive quote.

![Quote/showcase](assets/images/readme-images/quote%3Ashowcase.png)

- __Products Section__

PlantAway has three products with different features. The clients are everything from plant experts who already know what they want to persons who found the site because they have no idea how to solve the issue with watering while they're occupied with other things. The product section must tend to both.

For the more experienced plantista we have a large button with a cart to indicate purchase and price. Click it and they will arrive at the purchase form. simple and straight.

For the newcomers of the indoor farmer life, I made extremely simple illustrations and well formulated sales pitches to explain each products advantages before gently leading them towards the purchase form.

![Products](assets/images/readme-images/products.png)

- __About us section__

 This section gives the client an insight as to why PlantAway was founded. They are introduced to the common issues with keeping their plants alive while not being available and what solutions there is.

 The user will be prompted to use our help to find the right product (if needed) or order from the purchase form.

![About section](assets/images/readme-images/about-section.png)


- __The Purchase Form__

  - This is where the customer can order each product. The form is brilliantly put together ensuring all the correct info is acquired. all fields except from the last to product rows are required. This is because if the client only wants to order let’s say one pSphear they won’t have to fill out the fields for those who wants to order one of each or ten of each. There is also a terms and conditions page linked but it contains nothing more than a short text and an animated hammer.

![Purchase Form](assets/images/readme-images/purchase-form.png)
![Terms](assets/images/readme-images/terms.png)

- __The Footer__ 

 The footer is very simple and effective giving the visitor links to our social media profiles as well as opening hours and business location.
- 404 error page
Any site is nothing without a decent 404 document. 

![404](assets/images/readme-images/404.png)

 ![Footer](assets/images/readme-images/footer.png)

All parts of this page is included in the index.html file and /assets/css/style.css files as well as the 404.html and terms.html.



###Future Features Left to Implement

A proper purchase feature linked to credit cards and other payment services would be wise to implement making purchases even more simple.

Getting a proper illustrator to make more visually appealing content describing the products would make the site look better and create a more professional impression.

A customer review section would make a first-time customer feel more confident about a purchase.

## Testing 

The testing has mainly consisted in testing it on all my own devices and with google dev-tools.

The site has slightly different designs depending on screen-size.

 ## Queries
 -  More than 1000px wide.
     - The header is a logo on the left and a menu on the right
     -  The presentation includes a picture
     -  The Products and their corresponding info and purchase button are display side by side
     -  The about section is displayed in two columns
     -  purchase form section is displayed in two columns
     -  Footer is divided into three columns
-   Under 1000px and over 650px
    -   Header changes font size to a smaller size
    -   About section changes to one column
-   under 650px
    -   Nav changes to a hamburger dropdown
    -   The Picture of the owner is removed to save space
    -   Products section changes into one column with product name, illustration, info and purchase.
    -   Purchase form changes to one column
    -   Footer changes to one column

I used googles dev-tools to virtually try it on different devices. After not finding any bugs or issues I asked my family to test it on their devices to see if they understand the site and if it works the way it should. This would test both functionalities, UX and Visuals.
This resulted in two issues/bugs.

 - The word "home" in the “quote" section appeared on top of the product section on smaller screens
 - After pressing "go" in the form a site opens to confirm the visitor is human. This opened in the same window and since the link back to the main site did not work it could cause problems.

 Both issues have been addressed and are solved.

 

### Physically Tested Devices
 - Iphone 12 
    - Chrome - No issues
    - Safari - No issues
    - DuckDuckGo -No issues
    
 - iphone 12 mini
    - Safari - no issues

- lenovo 15" 
    - Issue with "home in the quote section dropping to a new line on top of products. 
        - Issue is fixed.

 - Iphone 11 chrome 
    - no issues

#### Virtually tested devices
- Iphone 12 SE
- Iphone XR
- Iphone 12 Pro
- Pixel 5
- Galaxy s8+
- Galaxy s20 Ultra
- Ipad Air
- Ipad Mini
- Surface Pro 7
- Surface Duo
- Galaxy Fold
- Galaxy A51/71
- Nest Hub
- Nest Hub Max
- Imac 27"


### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcatbackmancasino.github.io%2FMS1-ericbackman-plantcation%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fcatbackmancasino.github.io%2FMS1-ericbackman-plantcation%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=
)

### Unfixed Bugs

There are no known bugs.

## Deployment

The project was based on the Code Institute GitHub template and deployed via GitHub pages in March 2022.
After creating any repository on GitHub you can follow these steps to deploy a site.

1.  Log in to your Github Account
2.  Open the repository that you want to go live with
3.  Go to "settings"
4.  Find the "pages link" on the left side menu.
5.  Under "sources" press the button that says "none" and choose "main"
6.  Click "save" and you will receive a message saying your site is ready to be deployed.
7.  After a few minutes this message will change into "your site is published at 'link to site'.
8. you are now live and anyone with the link can see your site

## Languages used:

-	Css
-	Html

## Credits 

All HTML and CSS code is custom made with inspiration from the love running repo. 

 - Positioning assistance - Web Dev Simplified YouTube channel
 - Visual and functionality assistance - Brian Macharia
 - Gradient code - https://cssgradient.io/
 - Picture of "owner" - Picture taken from vogue who borrowed it from chronicle books ‘boys with plants’.
 - Fonts by Google Fonts
 - Symbols by Font Awesome
 - Form submit data - FormSubmit.co
 - Inspiration for readme.md - Elaine Broche ![README.md]url(https://github.com/elainebroche-dev/ms1-thrive/blob/master/README.md)

### Content 

All content written by me (Eric Bäckman) pretending to be the founder of the business.

### Media

All visuals except from banner background and owner image is custom made by Eric


Written by Eric Bäckman
March 2022

