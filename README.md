# Digi-Meals

The main objective of this website is to increase social media presence in order to promote home cooking and increased chefability at home by encouriging users to share recipes they have cooked at home using Digi Meals Utensils increasing web presence in a crowded environment. 

Online presence with companies is prevalent in todays world, with this in mind it is impertive for companies to ensure a healthy digital presence encouraging real life day to day user interaction to ensure viability. By encouriging users to share recipes and cooked meals promotes the quality of Digi Meals Utensils allowing users to boast their talents whilst using Digi Meals Utensils also creating a digital environment where users can connect with like minded cook enthieustacts through social media.  
 
## UX
 
- As a user, I want to be able to view recipes to cook at home.
- As a user, I want to be able to edit recipes to improve them.
- As a site owner, I want to be able to promote my cooking tools.
- As  site owner, I want to be able to udpate my products without having to get a designer to update.
- As a user I want to be able to share my recipes on social media.


Wireframe is saved in Data Centric Dev Digi Meals Folder created on Balsamic

## Features



### Existing Features
- Feature 1 - allows users  to achieve add, edit and delete recipes
- Feature 2 - allows site owner to add their products which are automatically displayed on the home carousel and displayed on utensils. 
- Feature 3 - View Recipes in list format on all recipes page. 

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Search facility is not working 
- Link buttons to individual recipe or utensils not implemented
- Favourite recipe button to be linked ot favourites where user can then view their own particular recipes
- Footer to be sticky for pages with less content 
- MongoDB Database to be updated to include arrays for ingredients and instructions. 

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

-[Gitpod](https://www.gitpod.io/)
    - **Gitpod** as an online IDE
-[Balsamic](https://balsamiq.com/)
    - **Balsamic** to create wireframe. 
-[Materialize](https://materializecss.com/)
    - **Materialize** to add responsive grid and built in component for UX.
- [JQuery](https://jquery.com)
    - **JQuery** to simplify DOM manipulation.
- [Python](https://python.org)
    - **Python** to programme the app
- [MongoDB Atlas](https://cloud.mongodb.com)
    - **MongoDB Atlas** to create and store non relational database.


## Testing

One of the issues I faced were image display, as the user will upload the images as a designer different image sizes pose a problem for display and could potentialy make the site very ugly. So I researched and found that object-fit: cover in css helps the image display much like a background image meaning that no matter what size image the user uploads the cards recipe dispaly will remain pretty.

With each update of the site I commited files to github for deployment on Heroku to test in both local browser and live. 

All testing was completed manually though chrome web developer tools test for front end and running app.py file for pymongo. 


- The site is designed through Materializer grid system local links are not linking on gitpod.
- Local links are working fine on Heroku.
- Text on Mobile is quite difficult as it is small - update on font sizes through rem to ne completed.
- Mobile Sidebr is also difficult to see so requires update on css to rectify.
 
I initially started the project in AWS Cloud 9 which proved difficult I had issues with css styling updating and general timeout issues I found I spent more time logging in so I moved over to Gitpod.io which I found to be a better IDE to work with when I got uptodate with different commands. I had an issue with environment variables on gitpod so created envirnment variable through Gitpod Dashboard. 

As I used up free hours on Gitpod I created a new account and imported all files into a new gitpod file and re deployed to heroku. In this I have lost alot of my original commits but commited often as I set up the new ide. 

## Deployment

- [Github Repository](https://github.com/GMCD77/data-centric-dev-digi-meals)
- [Heroku App](https://data-centric-digi-meals.herokuapp.com/)


## Credits
- Autoplay Materialize Carousel [CodePen by Nubtehy](https://codepen.io/nubtehy/pen/WyXveP)

### Content
- The Kitchen Utensil Range is from [Jamie Olivers Online Shop](https://shop.jamieoliver.com/) 
- Recipes are copied from [BBC GOOD FOOD](https://www.bbcgoodfood.com/) with all images link copied. 

### Media
- Logo Created in [canva.com](https://www.canva.com/design/DADjavOHONg/-ADltptj8b54I6Dh6Kjs3w/edit)

### Acknowledgements

- I received inspiration for this project from [Visme.co](https://visme.co/blog/website-color-schemes/) for the color scheme. I chose Striking and Simple color scheme. 
- Kevin Powell - YouTube #fiveminutefriday [CSS Object Fit](https://www.youtube.com/watch?v=6yAAV-uP0po)
