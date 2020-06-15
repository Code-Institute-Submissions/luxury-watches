# luxury-watches

***Link goes here***

This Website is set up to provide a platform for promoting a brand and selling Luxury watches with an option to receive a payment for each watch. 

Table of Contents:
    Installation
    Technologies used
    Wireframes
    Images
    User Experience
    Building the platform
    Testing
    Issues 
    Deployment
    Credits
    Acknowledgements

Technologies Used

Github
Gitpod
CSS3
HTML5
Bootstrap 4
Javascript
PayPal
Powerpoint
Font Awesome
w3schools

Wireframes:

Powerpoint - a simple structure located in the images tab

Images:

Instead of using free online images, I tried my hand in photography and photographed some of the watches my wife and I own. I uploaded the images to my Laptop and dragged the images into the images folder. 

User Experience/Features:

The first page of the website showcases the products with a caption "The home of Luxury Watches". The image is showcasing Mens watches, this is for a reson which is explained further down. A grey header to lightly highlight the functionality of the website. 'Luxury' as the home button  a with 'Men' and 'ladies' section. The 'about us' is the section whereby is advertises the brand and the companies goals, this gives you more of a feel about their mission. 

The Mens layout is to the point. the products they have and simple explanation, the make of the watch followed by a PayPal buy now button. The button is linked to a PayPal sandbox account which moves to another browser when clicked. 

The Ladies section is identical to the Mens section, its to the point with make and model that had a PayPal button under each item that is linked to a PayPal sandbox account which moves to another browser when clicked. 

The about us page is the brand, nice and simple which allows the user to see exactly what the objective is, objective being that its not just about the sale of a watch but the sale of a luxury rist band that also gives 10% to a worthy cause, a childrens charity of your choice. It will also give the company more of an edge that overshadows the competition. Here is where you will see updates of the effects the charitable dontations bring to the life's of those in need. 

The structure of each page is the same to allow the user to understand from the start how to mave around the website. 

The footer is a bootstrap card, the reason I chose this option is becasuse it works well and I wanted to try the bootstrap code. The social media icons are from fontawesome which is surrounded by a h ref link that directs the user to that respective site. Facebook, Twitter, Instagram and Youtube. Each link moves to another browser when clicked. The footer also contains a conatct us link, The reason its at the bottom and not powering on header is so it gives the user an interest to have a look around without giving them the option to reach out to the company. The 'contact us' link moved to a page where the user can enter a name and email address to be conatcted by the company. There is also a phone number they can call. 

The conatct us page has the second power image, however, on purpose, its not supposed to be mobile optimised as the image is supposed to showcase the Ladies watches in the background. It has the option to submit an email address and telephone number which will request the company to call the customer. 

On moving to Mobile, the model of the watch disapears along with the 'our other platforms below' content in the footer. 

Building the platform:

I am using Github and Gitpod to create the server environment to allow the coding of the website. 
Bootstrap will be used in order to ensure a mobile optimised environment. 
HTML will be the main feature, bootstrap will determine the structure and CSS will be used to style.
I used a boostrap header navagation system to allow a hamburger dropdown when moved to mobile. 

The initial index.html file was created using the shift+apstraphy+tab that created the main struture of the code, Html, body etc. I chose code from w3schools to confirm if the index.html and css pages were linked. success. 

I placed bootstrap 4.0.0 link in the html and tested it, success. 

I added all images to the umages folder and tested that the location source of the images worked. This took a few attempts to ensure I had the correct location, I tried:
../images/The-Full-Collection.jpg
images/The-Full-Collection.jpg
/images/The-Full-Collection.jpg
../assets/images.The-Full-Collection.jpg
Ite not the correct testing order but in the end, I figured this out: /assets/images/The-Full-Collection.jpg, success.

The html was added as an update. 

A header/body/footer was added with help from bootstrap and Code institue tutorials. I used the same code to place the image as was used in the bootstrap tutorial, I used the styling to make sure it was positioned the same as I liked this method. 
    -webkit-background-size: cover;
    justify-content: center;	        
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
I used a bootstrap card to taylor the footer. 

Once the stucutre was completed, well I thought it was, I created the other pages of the website. I duplicated the index.html for a Men.html, Ladies.html and conatct.html. 

On the other pages I added the images and a PayPal buy now sandbox buttton. I then added the content to the images. 
I inserted the location in each h ref to link the pages together. success
Social media icons with linked added, links defered to another new browser page. 
Added images to the ladies.html. this commit was incorrectly spelled. 
I began adding the hero image to the contact.html page, i made some attempt to mobile optimise but as i was testing  I noticed that it functioned better if the hero image was fully displayed on the desktop but only partial on mobile which would not be mobile optimised. It heroed the ladies watches. So i left it as is, not mobile optimsed. 

I placed all the information in one div and added the content. 
This is where I actially updated the links to target _blank - move to another broswer window when clicked. 

I tested Media query visibilty hidden so that the content does no show on mobile, just the name of the watch and PaPal Buy now button but decided to not use Media query to hid anything as all information would be needed in mobile.

I collaberated at this point with my tutor and we agreed to bring more life to the website the easiest way possible. 

Google fonts Pidera was added to highlight the text that would catch the eye of the user. 

On the men.html/ladies.html a bootstrap corousel was added with new images. I thought in order to give more life would be to show more of the products in different lights. I took my own photos and sized them to 744x322 before i added them to the files. I had to re-adjust a few times as it did not look right. 

Initially I was going for a plane minimal but decided to give it a little more height and information. I googled bootstrap footer and contact us page and then applied the footer to the website and all pages. 

I centered and updated the headings on each page and the P on index,html to be more attractive. 

I removed the boders around the bootstrap cards on men/html and ladies.html. 

Testing

The testing was basically every time a added html, bootstrap or a css style to see how it performed:

1. Broswer. 
2. Mobile
    I used Chrome dev tools to check each optimisation. 

I used Validator.w3.org to review the code within the pages for any errors. I had a few that needed resolving before my final push. 

I continuously moved through the website to see how it performed throughout the whole process. 

Issues:

I noticed a few issues when adding codes and this was all a result of missing code. For example, I was positioning the images in Men.html and Ladies.html and noties that the bootstrap colums were not working and the footer was moving from the bottom over the the very middle left of the page. Thsi was due to a missing closed div tag. 

Deployment

Credits

Acknowledgements:
I would like to achnowledge Matt, the Code Institute tutor. I used his code from the Bootstarp 4 tutorial to place the background image into the index.html page. 

Youtube blondiebytes for assistance with responsiveness. 

