# luxury-watches

https://pshumgti.github.io/luxury-watches/

This Website is set up to provide a platform for promoting a brand and selling Luxury watches with an option to receive a payment for each watch. 

Table of Contents:
    Installation
    Technologies used
    Wire-frames
    Images
    User Experience No.1
    The Actual User Experience/Features
    Building the platform
    Testing
    Issues 
    Deployment
    Credits
    Acknowledgements

Technologies Used:

Github
I used GitHub to create a repository that allowed me to store my files. 

Gitpod
I linked my Github account to Gitpod which allowed me to create the files and locally check my code throgh every stage. 

CSS3
Css helped me style my bootstrap framework. 

HTML5
Used to structure every html file.

Bootstrap 4
I mostly used Bootstrap as the frame work of the site. 

JQuery
I only used Java in the hamburger menu on the nav bar. 

PayPal
I used PayPal sandbox to create buy now buttons

Powerpoint
I used Power Point to mock up my ideas. 

Font Awesome
I used Font-Awesome to create my social media links

w3 schools
I utilized w3 schools in order to gain access to a lot of very useful examples of code. 

Google fonts
I chose Pidera because It looked rugged as well as elegant for this type of site. 

Wireframes:

Powerpoint - a simple structure located in the images tab

Images:

Instead of using free online images, I tried my hand in photography and photographed some of the watches my wife and I own. I uploaded the images to my Laptop and dragged the images into the images folder. 

https://unsplash.com/photos/vTA2Het76y8 photo in aboutus.html

User Experience/Features No.1

The first page of the website showcases the products with a caption "Home of Luxury Watches". The image is showcasing Men's watches, this is for a reason which is explained further down. A grey header to lightly highlight the functionality of the website. 'Luxury' as the home button  a with 'Men' and 'ladies' section. The 'about us' is the section whereby is advertises the CEO and his Goals, this gives you more of a feel about their mission. 

The Men's layout is to the point. the products they have and simple explanation, the make of the watch followed by a PayPal buy now button. The button is linked to a PayPal sandbox account which moves to another browser when clicked. Once the PayPal button is clicked sometimes it does not load, just click refresh and it will take you to my PayPal sandbox page.

The Ladies section is identical to the Men's section, its to the point with make and model that had a PayPal button under each item that is linked to a PayPal sandbox account which moves to another browser when clicked, again Once the PayPal button is clicked sometimes it does not load, just click refresh and it will take you to my PayPal sandbox page.

The about us page is the brand, nice and simple which allows the user to see exactly what the objective is, objective being that its not just about the sale of a watch but the sale of a luxury wrist band that also gives 10% to a worthy cause. It will also give the company more of an edge that overshadows the competition.

The footer is a bootstrap card, the reason I chose this option is because it works well and I wanted to try the bootstrap code. The social media icons are from font-awesome which is surrounded by a h ref link that directs the user to that respective site. Facebook, Twitter, Instagram and YouTube. Each link moves to another browser when clicked. The footer also contains a contact us link, The reason its at the bottom and not powering on header is so it gives the user an interest to have a look around without giving them the option to reach out to the company. The 'contact us' link moved to a page where the user can enter a name and email address and a note. 

The contact us page has the second power image, however, on purpose, its not supposed to be mobile optimized as the image is supposed to showcase the Ladies watches in the background. It has the option to submit an email address and telephone number which will request the company to call the customer. (This has been updated,explanation further down)

On moving to Mobile, the model of the watch disappears along with the 'our other platforms below' content in the footer, however, this feature I ended up removing. 

The Actual User Experience/Features:

Logging into the website you are met with a nav bar (light grey) with the logo right-aligned that acts as the Home button also. The right hand side of the nav bar has men's, ladies and about us sections. The nav bar is mobile optimized which turns into a hamburger menu and when dropped down it shows Men, Ladies and about us. 
This nav bar is the same for all 5 pages. 

The hero image is displayed in the background and underneath that is the brand name inviting customers to browse the latest watches. 

The footer is a bootstrap footer which houses the contact us button 

- this leads to another page showing a contact us form. This page layout is the navbar, contact us page and footer (all bootstrap) the page is inviting customers to contact us if they have any questions or would like to leave feedback. 

The rest of the footer contains font-awesome social media icons that are also links, these links lead the user to another web browser. The remaining information is an address and phone number of the company. 

Clicking into the men's/ladies tab the user will see the same Navbar as 'home' page, under that is carousel showcasing images of watches etc, the carousel is a bootstrap carousel that slides automatically and the option to click and slide. The images host text that display how the company works, 'Pick a Watch, Buy the Watch and Donate 10% to charity. the Images are my own that I took and uploaded to the images folder from my Laptop. 
Underneath the carousel you will be greeted with the heading - Home of Luxury watches. Underneath that you will be presented with the items for sale. All images, again my own, text and a PayPal button inside a Bootstrap card with more spacing down the middle from the column of bootstrap. spacing to separate the items on top of each other. 

If the user would like to buy a watch they can simply click on the PayPal buy no button and checkout safely and easy. PayPal is a very user friendly environment anyways so there will be no issue with user accessibility. 

Clicking on the about us page the user will be met the nav bar followed by the Name and photo of the CEO with some background that led to this wonderful company what they are doing for the community.

The footer is displayed as is in all other pages. 

Each page is mobile with the use of the bootstrap frame work, again, for easy user experience all the way through. 


Building the platform:

This website is built with HTML, a bootstrap framework with CSS styling. Java for the hamburger Menu. Mainly Bootstrap. 

I am using Github and Gitpod to create the server environment to allow the coding of the website. 
Bootstrap will be used in order to ensure a mobile optimized environment. 
HTML will be the main feature, bootstrap will determine the structure and CSS will be used to style.
I used a bootstrap header navigation system to allow a hamburger drop-down when moved to mobile, Java is installed also to allow this. 

The initial index.html file was created using the shift+apostrophe+tab that created the main structure of the code, Html, body etc. I chose code from w3schools to confirm if the index.html and css pages were linked. success. 

I placed bootstrap 4.0.0 link in the html and tested it, success. 

I added all images to the images folder and tested that the location source of the images worked. This took a few attempts to ensure I had the correct location, I tried:
../images/The-Full-Collection.jpg
images/The-Full-Collection.jpg
/images/The-Full-Collection.jpg
../assets/images.The-Full-Collection.jpg
Its not the correct testing order but in the end, I figured this out: /assets/images/The-Full-Collection.jpg, success.

The html was added as an update. 

A header/body/footer was added with help from bootstrap and Code institute tutorials. I used the same code to place the image as was used in the bootstrap tutorial, I used the styling to make sure it was positioned the same as I liked this method. 
    -webkit-background-size: cover;
    justify-content: center;            
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
I used a bootstrap card to tailor the footer. 

Once the structure was completed, well I thought it was, I created the other pages of the website. I duplicated the index.html for Men.html, Ladies.html and contact.html. 

On the other pages I added the images and a PayPal buy now sandbox button. I then added the content to the images. 
I inserted the location in each h ref to link the pages together. success
Social media icons with linked added, links deferred to another new browser page using target-"_blank". 
Added images to the ladies.html. this commit was incorrectly spelled. 
I began adding the hero image to the contact.html page, I made some attempt to mobile optimize but as I was testing  I noticed that it functioned better if the hero image was fully displayed on the desktop but only partial on mobile which would not be mobile optimized. It hero-ed the ladies watches. So I left it as is, not mobile optimzed.  

I tested Media query visibility hidden so that the content does not show on mobile, just the name of the watch and PayPal Buy now button but decided to not use Media query to hide anything as all information would be needed in mobile.

I collaborated at this point with my tutor and we agreed to bring more life to the website the easiest way possible. 

Google fonts Pidera was added to highlight the text that would catch the eye of the user. 

On the men.html/ladies.html a bootstrap carousel was added with new images. I thought in order to give more life would be to show more of the products in different lights. I took my own photos and sized them to 744x322 before i added them to the files. I had to re-adjust a few times as it did not look right. 

Initially I was going for a plane minimal but decided to give it a little more height and information. I googled bootstrap footer and contact us page and then applied the footer to the website and all pages. 

I centered and updated the headings on each page and the P on index.html to be more attractive. 

I removed the boarders around the bootstrap cards on men/html and ladies.html. 

I centered the form on contact.html by updating a div col to col-md-6 and removed space between body and footer by removing pt-5 in div.

Added spacing between products on ladies and men.html by changing MT-3 to mt-5 on bootstrap, added text name and CEO to aboutus.html with padding, switched contact us button in footer to go under text. It looked off but it just makes it look nice and neat. 

In order to make the "Home of Luxury Watches" stand out I added padding of 30px above and below.

Looking at the images on ladies.html, the top two were too small, I resized top images to fit bootstrap card. resizing was done outside of gitpod and correct sized image added, this was a little challenging so for the carousel I decided to use css to size the images. I added new images and fixing the stretched look. 

I styles the footer to ensure the social media links were side by side with inline block value. 

Testing:

I continuously moved through the website to see how it performed throughout the whole process.
The testing was basically every time a added html, bootstrap or a css style to see how it performed:

1. Browser. 
2. Mobile
    I used Chrome dev tools to check each optimization. 

The first thing I initially tested was folders and files. I created the assets folder and index file and linked the style sheet to the index file and save this. I then began to test a style in the css using a HTML class and checked it locally in a browser.
GitPod allows you to make the files public along with opening the files in browser to see how everything responds. 
The tests here responded nicely after I linked the pages together using the link tag. 
I add bootstrap and also tested if it would respond in the broswer. it was a success. so now that everything worked as it should i decided to move on. 

After testing HTML and css only in another repository i decided to use bootstraps framework as it was the use of code that would allow alot with simple styling. I reviewed w3schoold and tested the navbar in the browser and i liked the way it responded so I embedded it and slightly changed the background color etc. I tested font style oblique, it was more of an italic look so later changed from oblique to FontAwesome Pidera. Along with the bootstrap nav back comes mobile hamburger with i tested in dev tools and my phone 7 and it responded how it should have. 

The carousel is also bootstrap frame work, pasted into men.html and ladies.html. I saw how it responded but i had some trouble getting the images right. I managed to size them correctly however closer to the end I decided to use new photos, same images, and style them using css which looked way better and clearer as they looked stretched. The body on both pages (men.html/ladies.html) have bootstrap card with images in side and a PayPal button. Placing the image in side was not an issue but the styling was part issue. again, this was more of the frame BS frame work code that had to be amended, I provide more spacing between products in Men.html and ladies.html by changing a BS class from PT-3 to PT-5. In the ladies.html, i had an issue with the top two images, too much padding on bottom. Tried everything and went as far as resizing before adding photo to files so i just played around with the height and VW until i got the right fit. 


The body in the index.html page is code from Code Institute as I liked the way it looked in the tutorial and tis was my first time using bootstrap so it only made sense to test and ultimately used what i knew, at that time. I had text heading text on the photo but later moved that off the photo. it took me a while to understand it and in the end, the photo was fixed and the scrolling up and down allowed you to see different points of the photo. i have thought of removing it, maybe i will int he future, bbut i am leaving it for now. 

The contact us page again, bootstrap framework, It was plane without styling, I had issue centering it, with the help pf my mentor we managed to get it aligned center and add headings etc to make it look the part. 

The about us page has a free stock photo and text. I added the photo and it took up way too much of the page and more, there was a scrolling bar made on the left and the bottom it was so big. i tried making the width 50% and this seemed to work. I tested it on mobile and it centered which is exactly what I was looking for. sometimes when I tried to use CSS to center, half of photo was missing on mobile. 

I used Validator.w3.org to review the code within the pages for any errors. I had a few that needed resolving before my final push.  
 
I then passed the code through he validator again and all was passed.  

I tried to add validation results however I was having issue. I have uploaded the text to https://validator.w3.org and all pages have passed. 

Issues:

I noticed a few issues when adding codes and this was all a result of missing code. For example, I was positioning the images in Men.html and Ladies.html and noticed that the bootstrap columns were not working and the footer was moving from the bottom over the the very middle left of the page. This was due to a missing closed div tag. 

After the second mentor session, after adding the carousel and new footer i noticed that there was spacing between the body and the footer, i made several attempts to remove the spacing, however, in the end I received assistance from my mentor. I also had issue centering the contact us form, if I used CSS then it would not be mobile optimized. in the end, my mentor pointed out that I needed to update bootstrap code to center it. I centered the form on contact.html by updating a div col to col-md-6 and also provide more spacing between products in Men.html and ladies.html by changing the PT-3 to PT-5. 

Other issues I had was the image resolution. I tried to re-size them before re-adding them back to the images folder, it worked for some and not for others, the ones it did not work for I sized them in css. 

Major issue, 

Just after I deployed it, the home page would not show the background image, I removed it and placed a carousel which I though looks better and is showing on published site. 
Deployment:
I came to the stage where I was now fully 100% happy with the website. I went to the Github respository and clicked on settings, from there, I went to GitHib Pages to send it out hosted and selected Master Branch. The site was then deployed and published. 

Credits:
ws schools
stack overflow
Youtube blondiebytes/mmtuts for assistance with responsiveness.

Acknowledgements:
I would like to acknowledge Matt, the Code Institute tutor. I used his code from the Bootstrap 4 tutorial to place the background image into the index.html page, however, i have since removed this feature. 

photo in aboutus.html https://unsplash.com/photos/vTA2Het76y8 = tim-mossholder
