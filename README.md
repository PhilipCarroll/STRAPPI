# STRAPPi 
STRAPPi is a website that will eventually function as an ECommerce platform. I want to showcase products with high quality imagery and in time I will build in a blog. This will act as a means to consistently add new content and have the site index with SEO, driving organic traffic and giving me a mechanism to redirect consumers toward products on the site, increasing sales.

For this MileStone1 project I am focusing on the layout and overall style of the static frontend portion in order to develop the skills I have acquired so far during first module of the Code Institute course.

## Table of Conetents
- [User Experience](#### User Experience Design (UXD/UX))
    -[Strategy](#### Strategy:)
    -[Scope](#### Scope:)
    -[Structure](#### Structure:)
    -[Skeleton](#### Skeleton:)
        -[Some Examples](##### Some examples-)
    -[Surface](#### Surface:)
- [User Stories](### User Stories:)
- [Features](## Features)
    -[Existing Features](### Existing Features)
    -[Features to Implement Later](### Features to implement at a later date.)
- [Technologies Used](## Technologies Used:)
- [Testing](## Testing)
- [Development](## Development)
- [Credits](## Credits)
- [Resources](## Resources)

## User Experience Design (UXD/UX)
In order to develop my plan this project I used the 5 planes of User Experience Design-
- Strategy, Scope, Strucrture, Skeleton and Surface.
I aimed to answer a few key questions in each plane to guide my decision making process.

#### Strategy:
1. Who is my audience?  
This is a B2C platform for watch enthusiast, casual watch fans, and anyoen looking to buy a gift or watch related product.
2. What makes this site special?
STRAPPI aims to provide an experience reminiscent of walking into a brick and mortar watch shop. I want to echo the feeling of entering
and browsing a highstreet watch retail liek you would in one of Europe's many shopping districts.
3. How can we trigger the emotional response to buy?
Part of the brick and mortar shopping experience is the visual sensation of feasting your eyes on products in their best light. You are greeted with
well presented items complimented by other fine materials and alternatives. Layout and imagery will be the focus in regards to coverting browsers to customers.

#### Scope: 
1. What features will be included in this project?
This is a static frontend project using only HTML and CSS and so there are limitations to the features and content that are possible.
The main goal for this project is to build the overall structure and layout including placement of future features. 
2. What do users need/want?
Intuitive navigation. Minimum clicks/taps to locate desired content - product listings/blog/contact etc.

#### Structure:
I'm aiming to keep things as simple as possible when it comes to the navigation of the site with the idea that regardless of the level of content added the 
overall structure does not need to change and ensures returning customers are presented with a familiar platform.
 I want to begin with 5 main pages to the site. These will be the headings in the Navigation bar of the site and the first step to uncovering 
more information for the user. They will the be - 
* Home Page
* Shop
* Blog
* About
* Contact

#### Skeleton:
My plan is to use the home page as a window shopping element to actively entice users toward the other areas of the site. Users 
that enter the site find themselves on the home page and will naturally begin to scroll(encouraged by the design concept of content hinting). 
They will discover sections that will allow them to learn who we are as a brand, what we offer on the site and actively engage them to visit the different areas.

##### Some examples-
* A snippet of a blog article with an image with a "->Read More->" style CTA that will open up the article on the blog page. 
* An image of a well known watch on a third party strap option accompanied by "->Shop Straps->" CTA button opening up the shop page.
* The blog can be utilised to write reviews and articles on products we stock. A double-edged sales sword pitching the product under the guise of a blog while guiding them carefully back to the shop section.

#### Surface:

Please see wireframes folder. The end reult is signif

I used the Rubik font from Google Fonts throughout the site with Sans-serif as the default fall back.

I used [Coolors](https://coolors.co/) to create a pallete to use for this site. I must say coolors is one of the slickest sites I have come across! 
There are three colours in use throughout the site. I made use of the rgba opacity property in some cases.
- #14213D Oxford Blue
- #FDB035 Bright Yellow Crayon.
- #F5F5F5 Cultured.

### User Stories:
* With this website I want to offer watch enthusiasts and casual shoppers a place to browse products and watch
related content. I want to engage visitors with high quality images and turn them in to loyal customers by offering good value products and great service.
I have decided to break my users into 5 personas. Each persona defined will have a "First Time Visitor" and "Returning Visitor"
story. 

I researched types of consumers in order to define my personas and have loosely based Users 1-4 on the 4 types outlined here - 
[Beyond the Hedge Creative](https://www.beyondthehedgecreative.com/4-different-types-consumers-market/) 
I also added a 5th story because I felt this type of user is a common persona in the watch world (I may or may not be one myself!) - The Fantasy Shopper. 

#### User 1: The Gift Shopper (Needs-Based)
##### Typical Characteristics: Has item or items in mind and will be searching competitors also. Budget driven. 
##### Purchasing Frequency: Variable/Can be influenced.
* First Time Visitor - I want to be able to quickly browse products so I can compare them with other sites.
* Returning Visitor - I want to buy the item I saw on my last visit because it meets my requirements for a gift.

#### User 2: The Bargain Hunter (Discount)
##### Typical Behaviour: Market savvy. Hunts for deals.
##### Purchasing Frequency: Frequent when price suits.
* First Time Visitor - I want to look for products that are on sale so that I am encouraged to buy them.
* Returning Visitor - I want sign up for the newsletter so I can be informed of sale items and offers.

#### User 3 The Impulse Buyer (Impulsive)
##### Typical Characteristics: Always ready to buy. 
##### Purchasing Frequency: Somewhat frequent.
* First Time Visitor - I want to browse through products with ease so I can easily see what's on offer.
* Returning Visitor - I want to find a product I haven't seen before so I can feel good buying something unique.

#### User 4 The Enthusiast (Loyal)
##### Typical Characteristics: Will advocate elsewhere online. Will always check your site first for products.
##### Purchasing Frequency: High frequency.
* First Time Visitor - I want to be impressed by the sites overall look and feel so that I can become a loyal customer. I visit many similar sites regularly so I know what I like.
* Returning Visitor - I want to see new content and product listings as well as read blog posts about the watch world so I can enjoy my hobby. I want to build a relationship with the site through purchases and good service. I'm interested in a regular newsletter.

#### User 5 The Fantasy Shopper
##### Typical Characteristics: Content consumer.
##### Purchasing Frequency: Infrequent.
* First Time Visitor - I want to browse through high quality imagery of products so I can fantasise about a purchase that may never happen.
* Returning Visitor - I want to view high quality images and consume new blog posts. 
Insert joke - I believe the perfect number of watches in any collection can be expressed as a simple formula (n)+1. (n) being the number you currently own :)




## Features
### Existing Features
This site is built with the aim of constantly driving users back to the shop page to drive sales. The home page is essentially one large image driven navigation tool. Each section encourages the user to visit another part of the site and all end with a CTA button to allow ease of maneouverability from anywhere.
* Bootstrap designed responsive Navbar with expanding menu section at the 'md' breakpoint.
* Bootstrap Carousel slider with 3 images and active indicators. Implemented links on each image to direct traffic.
* Shortened text blog post that leads users toward the blog page of the site with a CTA to read more.
* Utilised Bootstrap cards to display product section on home page.
* 3 section rersponsive footer with-
    * Newsletter sign-up input field.
    * Navigation links for the site mirroring those of the Navbar.
    * Social links section.
* Uniform buttons across the site with hover functionality.


### Features to implement at a later date.
#### The Shop Page.
While planning this project I wireframed the shop page for mobile. I soon came to the realisation that it would require more 
than I was capable of at the time and likely 3 additional pages I had wanted to implement 3 sections that would load from tabs at the top 
of the page without ahving to leave that page. I'll be honest, I still don't know how to do that but I didn;t look in to it much either! 
#### Modal Contact pop up.
I'd like to implement a modal pop up as a means of allowing the customer to fill out a contact form. This would allow me to remove one entire page from 
the site and make the navigation cleaner and more refined.
#### Instagram Feed.
I think an instagram gallery/feed section has several great functions. Ideally I can manage an instagram account along side the site showing off products and 
highlighting customer 'wrist shots' which are very popular in the industry. It acts as an emotional trigger for sales and functions as another form of browsing. 
#### Watches.
Although this is a project site, I aim to use this site in the future. I'd like to start out by wholeselling straps and accessories before eventually 
wholeselling watches also once the brand becomes somewhat estabilished.
#### Blog archive.
Over time the site will inevitably become bulky with blog material. It would be nice to implement an archive/break off site for the blog.
#### Improved display across screen sizes.
I kept finding myself working away at CSS before realising I was only refreshing one screen size to see if it had worked and later finding it wasn't very good looking when resizing the viewport. I'd like to spend some time increasing the overall look of the site across devices. I think it's just OK as it is. I'd like to implement a fixed width for the main content on larger screens to keep the structural flow in tact. I felt I learned a lot from my mistakes in this area and would approach the build very differently next time having made them this time.

## Technologies Used
- **HTML5:** Latest version of semantic markup language HTML used to build the structure of the site.
- **CSS3:** Used to style HTML elements and increase UX and responsiveness overall.
- **Bootstrap:** Used many of Bootstraps handy features including some that make use of Javascript suich as the Carousel. I read somewhere that BS can be your best friend or worst nightmare. I definitely experienced both ends of the spectrum during this project but I am happy to say we are still on talking terms. I think with more time and a deeper understanding it can be a very powerful tool to speed up the development process.
- **Git:** Used Git to manage staging, committing and pushing versions of the project to Github as it was developed over time.
- **Github:** Used Github to store versions of the project in it's centralised repository.
- **Github Pages:** Used to deploy and host the website on the real internet :) 
- **Gitpod:** IDE used to create and edit all files for the project.
- **Balsamiq:** Used to wireframe the site. Also used to realise I bit off way more than I could chew for my first build! I drew up the mobile wireframes with the intention of coming back to do the larger screen sizes at a later point as I familiarised myself with responsive design, and hwo the grid system works etc. I left the mobile wireframes as I had them originally to show how different the end result was. I imagine this is pretty poor practice in the real world but I learned a lot by tweaking the design to my ability as I went along.
- **FontAwesome:** CDN providing icons for use across the site.

## Testing
I used the W3 HTML and CSS Validators to test the code on my site. Although there were errors found it seems that they all stem from outside sources and I'll be brutally honest and say I don't know how to resolve them.

## Deployment
1. Open Github and search the repository: 'STRAPPI'...https://github.com/PhilipCarroll/STRAPPI
2. Open Settings tab.
3. Open Github Pages from there. 
4. Select Master Branch.
5. Click Save.
6. Use the generated link to open the deployed site.

## Credits
I took small snippets of blog articles from other sites online. 
I believe I have covered just about everything elsewhere so I just want to credit my wife Alejandra for making me bomb sandwiches in the evening while I worked on this!

## Resources
I dipped in and out of a lot of videos and sites for inspiration in overcoming small obstacles. I watched a decent amount of content in my spare time too without it being directly in relation to this build also. Below are links to videos/channels/sites that I found myself returning to that carried the most value.
### YouTube
[Academind Channel](https://www.youtube.com/watch?v=23bpce-5s8I)
[Drew Ryan](https://www.youtube.com/user/DrewOnCue)
[Dev Ed](https://www.youtube.com/channel/UClb90NQQcskPUGDIXsQEz5Q)
### Other Sites Used 
[Outbrain](https://www.outbrain.com/help/advertisers/why-ecommerce-site-should-have-blog/)
[w3schools](https://www.w3schools.com/)
[StackOverflow](https://stackoverflow.com/)