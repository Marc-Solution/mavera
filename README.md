![alt](assets/images/mavera-logo.png)

python3 -m http.server

# MaVera

A website for the company Mavera. The company's intention is to give information about and to sell their organic 100% natural deodorants. ( This is not a real company or product. They don't exist yet. This website is made for a school assignment. )

#### There is two types of customer we aim for:

1. The customer already knows why he or she wants to use natural deodorant and is looking for a good product. They already know about the danger of using ordinary deodorants that have chemical ingredients. This person has already decided to use organic deodorants.
2. Potential customer: This person is curious and wants to find information about the benefits of organic deodorants. This person is looking for reasons to use deodorants with only natural ingredients.

## UX

---

#### The business goals for this website are:

- Sell products
- Brand the company as being environment friendly
- Help people live more environment friendly lives
- Raise awareness about benefits of using organic natural products and the dangers of using non  organic products
- Connect with customers to have an dialogue with them

#### The customer goals for this website are:

- Find organic deodorants to buy ( and later on other organic products )
- Find information about organic deodorants
- Learn about why to use organic products


#### User stories:

1. As a new visitor to this company website, I want to instantly know what this company sells to see if it fits my needs.
2. As a visitor to this website, I want to easily navigate the site so that I can find what I am looking for.
3. As a visitor to this website, I want to find organic deodorants (and other organic products).
4. As a visitor to this website, I want to know if these deodorants really work.
5. As a customer or a potential customer to this company I want to support an environment friendly cause and I want to see if this company shares my values.
6. As a customer or a potential customer to this company I want to learn about how to live a more healthy and environment friendly life.
7. As a visitor to this website, I want to learn the benefits of organic deodorants.
8. As a customer or a potential customer, I want to know the price of the product.
9. As a customer or a potential customer, I want to know where I can buy the products
10. As a customer or a potential customer, I want to know about the ingredients in the products.

#### Wireframe mockups:

For wirefarmaing I used [Balsamiq](https://balsamiq.com)

Click this link to see my wireframes.

<https://marc-solution.github.io/mavera-wireframes/>

### Design choises

I wanted the design to be very simple and give a calming feeling of nature. Therefor I chose to have nature pictures on every page.

### Images

The company's aim is to reach people that care about nature, therefor I used beautiful nature images to remind the user of the beauty of nature.

### All the images have a symbolic meaning

- The image on the home page is beautiful forest image with the products in it. The symbolism of this image is to show that these products are natural.

- The image on the products page is a tree with flowers. Flowers smell good, so the intention is to remind the user of fresh scents.
- On the about page there is an image of a sunrise. According to some cultures a sunrise is a symbol for a new beginning and victory. Why i choose this symbol is because the company vision and mission is to create a new better world and to overcome destructive habits.
- On the contact page there is a pleasant looking image of water. The symbolism of this image is: Water connects us all. 

### Colors

Most of the page is in black, white and gray. I used colorful images to sparkle up the page. 

In the product modals I use colorful backgrounds.

- For Lavender I used a purple background color because Lavender i the color purple.
- For EucalyptusI used a green background color because  eucalyptus leaves are green.
- For Citronella I used a yellow background color because a citrus kind of smell is associated with the the collor yellow.

For the newsletter form I used the sam purple color as for the Lavender popup, because I thought it looked good. 

## Features

---

### Existing Features

#### On all pages:

- A responsive navbar with links to each respective page on the website. And a company logo. Clicking the logo returns users to the home page.

- A Footer on all pages with social media links. The links open a new tab in the browser.

The navbar is on the top of the page and the footer in the bottom on all pages on the website.

### Home

A large image of the products on the home page, just under the navbar. The purpose is that the user instantly will know that they can find organic natural deodorants on this website.

Headline and text on home page that describes the products. The intention is to sell the product.

Headline and text on home page that describes the ingredients of the product. The intention with this text is to assure the customer or potential customer that the company only uses 100% natural organic ingredients. Also, the purpose is to brand the company as environmentally friendly.

After the texts comes two customer reviews. There is an image of the customer and what they say. ( The code for this section I took from the page whiskey drop that is a Code institute assignment. )


### Products 

Under the navbar there is an image that shows the products. Not the same image that's on the home page.

Efter this there's a headline that says Products. Then there are 3 bootstrap4 cards with 3 different products. Each card has an image of the product and some text. There is information about the ingredients of each product. At the moment the company only has 3 products. It has 3 different deodorants, so 3 bootstrap4 cards is enough.

Then comes a text section with information about which retailers sell the product and the price.

Efter this comes a thank you note to the customers ( Inspired by Lily & hannas ice cream )

### About

About text: Text about the why the productuct was created.

Mission and Vision: A text about the company values and vision for the future

Newsletter: A heading and text to get people to sign up to the company's newsletter. Under this text there is a button that opens a pop up with a newsletter signup form. ( The newsletter is without backend for the moment )

The purposes with the newsletter are:

- To give tips about environment friendly living for.
- To raise brand awareness.
- Content marketing and
- To communicate with the customer
- Competitions and lotteries where the customer can win products

### Contact

The contact page contains:

1. An image at the top just under the navbar
2. A contact form

The contact form has 4 input fields and a submit button. These are the input fields:

1. Name
2. Your email
3. Subject
4. Your message. A text field where you write your message.
5. A submit button.


### Features Left to Implement

- A webshop. So that the company can sell their products directly from the webpage. At the moment they only provide information about what retailers sell their products.
- A blog. The purpose for the blog is content marketing and brand awareness
- A scrollable products gallery when the company has more products to offer.
- A FAQ page or section. This is relevant when the company has received more knowledge of what people want to know.
- The option to choose languages

## Technologies Used

- HTML5
- CSS3
- Bootstrap4
- Bootsnipp liberty
- jQuery
- Fontawesome
- Google fonts


## Testing

---

### Browsers I tested

- Chrome
- Firefox
- Safari
- Opera

I tried these browsers. I looked at all the different sizes in the inspect mode ( Except for in safari, because it does not have that option). It works in widescreen, desktop, tablet and mobile.
I have tested it on my laptop computer and also on a big screen. I tested it on two different Iphones and on a Samsung Galaxy. It works as it should on all devises.

### Changes I made

When testing the products cards on the smallest size smartphone and also the tablet size in google chrome, Firefox and Opera it looked strange. The text got very stretched out and it didn’t look so good. I also tested this on a real Iphone and a Samsung Galaxy with the same result. I removed the product info text from the card and changed it to a button with the text Read more. This button opens a modal with the product info text.

### W3 validator

#### HTML validator - https://validator.w3.org/

I tested my code in the w3 html validator. I got two errors. The first error was in the what customers say section in the index.html page. The problem was that there was no header directly after the section tag. The header came later in the section. I moved the header so that it comes directly after the section tag. It worked and it was approved.

The second error was in the same section. It had to do with the customer review images. I am not really sure exactly what the second error was. I changed these two things and it got approved. 

- The div that contained the customer images had a class attribute but with no value. I removed that class attribute from the div tag. 
- Secondly, the hight and width properties for the customer images was in the img tag. I moved the hight and width properties to my style.css. 

After doing these changes the code was approved by W3 html validator.

#### CSS validator - https://jigsaw.w3.org/css-validator/

Again I got two errors. But this time the errors where not from any code i've written in my workspace. The errors were from the bootstrap library. The errors were found in this link https://maxcdn.bootstrapcdn.com/bootstrap/4.2.1/css/bootstrap.min.css

There where also some warnings. Again it was not from any code I’ve written. It came from the bootsnipp code I use for the newsletter. The warning came from this link script //cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js

I wrote to tutor assistance. They said it will be ok as long as I mention it here in this README. 

### Contact and newsletter forms

I tested the contact and newsletter forms. 
- When submitting without any message an error message about the required fields appears.
- When submitting with an invalid email address an error message about the required fields appears.
- When submitting the form with all inputs valid a success message appears.

## Deployment

---

This projects was developed using Gitpod and Vs code. committed to git and pushed to GitHub from Gitpod. The website is published on Github pages. To view the web-site click the following link. https://marc-solution.github.io/Mavera/


## Credits

---

### Code 

This project uses bootstrap4

- navbar
    - I followed the instructions from the whiskey drop page and did a similar nav for this page, with a little changes.

- Footer
    - I got the code for this footer from following the instructions for the Love Running web-site assignment.
    - I learned from this tutorial how to make the footer stick at the bottom. https://www.youtube.com/watch?v=US_3XvufMLU

- Responsive image
    - I learned from this tutorial how to make the image under navbar (on all pages) responsive. https://www.youtube.com/watch?v=VF5kD6QEEag

- Modal Popup
    - The code for the modal I got from the bootstrap documentation. I changed the code a little bit. I use the modal in the products cards and for the newsletter.
    - The changes I did for the products modal was that I removed the modal header and added a background color. I inserted a text with product information.
    - In the newsletter modal I inserted a newsletter form

- Newsletter form
    - The code for the newsletter I got from https://bootsnipp.com/snippets/AlM7P
    - I made some changes. I did not use any of the css code from this bootsnipp newsletter code. I did my own css code. I changed the background color and I added a name input field 

- Contact form
    - The contact form is a mix between:
        - My own code
        - code that i got from following this tutorial https://www.youtube.com/watch?v=52pEihWDQ9A
        - And I got some parts from the bootstrap documentation

First I followed the tutorial but i did not use a background image. I also styled it a little bit differently. The address, phone number and email-address part I got from the bootstrap documentation.


### Content

The text for this web-site was written by Marco Deb.

In the products information texts I mention some research facts about the ingredients.
The sources to that information is:

- For the Lavender deodorant https://www.medicalnewstoday.com/articles/265922#benefits
- For the Eucalyptus deodorant https://www.medicalnewstoday.com/articles/266580#eucalyptus_health_benefits 
- For the citronella deodorant https://www.medicalnewstoday.com/articles/327226#oils-to-use 



### Media

- The logo image in the navbar was designed by Klara Kazmi

- The banner image on the home page under navbar was obtained from https://unsplash.com/photos/7rIE9DPdo80 . The deodorant bottles on the image was added with Photoshop by Klara Kazmi
- The bottle image where photographed by Klara Kazmi
- The bottles were designed in Photoshop by Klara Kazmi
- The banner image on the products page was obtained from https://www.hdwallpaper.nu/beautiful-flowers-wallpapers/ 
- The banner image on the about page was obtained from https://www.zedge.net/wallpaper/d77a9e3e-91f3-30bf-9a9d-cbc4bc685a9e
- The banner image on the contact page was obtained from https://wallpapersafari.com/w/tXIbiE
- The woman customer image was obtained from https://unsplash.com/s/photos/woman
- The man customer image was obtained from https://unsplash.com/photos/7rIE9DPdo80

### Acknowledgements

I received inspiration for this project from: 

- The Code Institutet assignments Love running, Whiskey drop and The Resume project

- https://zenhabits.net/  I liked that it was very simple
-I received inspiration for the text on the products for the retailers section from https://www.lilyohanna.se/en/ (Click the retailers link in the heading and you will find the section)
- I received inspiration for the text on the home page from https://beekings.com/product/natural-deodorant-subscription/


