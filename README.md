# luxury-watches

***Link goes here***

This Website is set up to provide a platform for promoting a brand and selling Luxury watches with an option to receive a payment for each watch. 

Table of Contents:
    Installation
    Technologies used
    Wireframes
    Images
    User Experience No.1
    The Actual User Experience/Features
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

User Experience/Features No.1

The first page of the website showcases the products with a caption "Home of Luxury Watches". The image is showcasing Mens watches, this is for a reson which is explained further down. A grey header to lightly highlight the functionality of the website. 'Luxury' as the home button  a with 'Men' and 'ladies' section. The 'about us' is the section whereby is advertises the CEO and his Goals, this gives you more of a feel about their mission. 

The Mens layout is to the point. the products they have and simple explanation, the make of the watch followed by a PayPal buy now button. The button is linked to a PayPal sandbox account which moves to another browser when clicked. Once the PayPal button is clicked sometimes it does not load, just click referesh and it will take you to my PayPal sandbox page.

The Ladies section is identical to the Mens section, its to the point with make and model that had a PayPal button under each item that is linked to a PayPal sandbox account which moves to another browser when clicked, again Once the PayPal button is clicked sometimes it does not load, just click referesh and it will take you to my PayPal sandbox page.

The about us page is the brand, nice and simple which allows the user to see exactly what the objective is, objective being that its not just about the sale of a watch but the sale of a luxury rist band that also gives 10% to a worthy cause. It will also give the company more of an edge that overshadows the competition.

The footer is a bootstrap card, the reason I chose this option is becasuse it works well and I wanted to try the bootstrap code. The social media icons are from fontawesome which is surrounded by a h ref link that directs the user to that respective site. Facebook, Twitter, Instagram and Youtube. Each link moves to another browser when clicked. The footer also contains a conatct us link, The reason its at the bottom and not powering on header is so it gives the user an interest to have a look around without giving them the option to reach out to the company. The 'contact us' link moved to a page where the user can enter a name and email address and a note. 

The conatct us page has the second power image, however, on purpose, its not supposed to be mobile optimised as the image is supposed to showcase the Ladies watches in the background. It has the option to submit an email address and telephone number which will request the company to call the customer. (This has been updated,explanaition further down)

On moving to Mobile, the model of the watch disapears along with the 'our other platforms below' content in the footer, however, this feature I ended up reoving. 

The Actual User Experience/Features:

Logging into the website you are met with a nav bar (lightgreay) with the logo right-aligned that acts as the Home button also. The right hand side of the nav bar has mens, ladies and about us sections. The nav bar is mobile optimised whivh turns into a hamburger menu and when dropped down it shows Men, Ladies and about us. 
This nav bar is the same for all 5 pages. 

The hero image is displayed in the background and underneath that is the brand name inviting customers to browse the latest watches. 

The footer is a bootstrap footer which houses the contact us button 

- this leades to another page showing a ocnatct us form. This page layout is the navbar, conatct us page and footer (all bootstrap) the page is inviting customers to contact us if they have any questions or would like to leave feedback. 

The rest of the footer contains fontawesome social media icons that are also links, these links lead the user to another web browser. The remianing information is an address and phone number of the company. 

Clicking into the mens/ladies tab the user will see the same Navbar as 'home' page, under that is corousel showcasing images of watches etc, the corousel is a bootstrap corousel that slides automatically and the option to click and slide. The images host text that display how the company works, 'Pick a Watch, Buy the Watch and Dontae 10% to charity. the Images are my own that I took and uploaded to the images folder from my Laptop. 
Underneath the corousel you will be greated with the heading - Home of Luxury watches. Underneath that you will be presented with the items for sale. All images, again my own, text and a PayPal button inside a Bootstrap card with more spacing down the middle from the column of bootstrap. spacing to seperate the items on top of eachother. 

If the user would like to buy a watch they can simply click on the PayPal buy no button and checkout safely and easy. PayPal is a very user firendly environment anyways so there will be no issue with user accessability. 

Clicking on the about us page the user will be met the nav bar followed by the Name and photo of the CEO wih some background that led to this wonderful company what they are doing for the community.

The footer is displayed as is in all other pages. 

Each page is mobile with the use of the bootstrap frame work, again, for easy user experience all the way through. 


Building the platform:

I am using Github and Gitpod to create the server environment to allow the coding of the website. 
Bootstrap will be used in order to ensure a mobile optimised environment. 
HTML will be the main feature, bootstrap will determine the structure and CSS will be used to style.
I used a boostrap header navagation system to allow a hamburger dropdown when moved to mobile, Java is installed also to allow this. 

The initial index.html file was created using the shift+apstraphy+tab that created the main struture of the code, Html, body etc. I chose code from w3schools to confirm if the index.html and css pages were linked. success. 

I placed bootstrap 4.0.0 link in the html and tested it, success. 

I added all images to the images folder and tested that the location source of the images worked. This took a few attempts to ensure I had the correct location, I tried:
../images/The-Full-Collection.jpg
images/The-Full-Collection.jpg
/images/The-Full-Collection.jpg
../assets/images.The-Full-Collection.jpg
Its not the correct testing order but in the end, I figured this out: /assets/images/The-Full-Collection.jpg, success.

The html was added as an update. 

A header/body/footer was added with help from bootstrap and Code institue tutorials. I used the same code to place the image as was used in the bootstrap tutorial, I used the styling to make sure it was positioned the same as I liked this method. 
    -webkit-background-size: cover;
    justify-content: center;	        
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
I used a bootstrap card to taylor the footer. 

Once the stucutre was completed, well I thought it was, I created the other pages of the website. I duplicated the index.html for Men.html, Ladies.html and conatct.html. 

On the other pages I added the images and a PayPal buy now sandbox buttton. I then added the content to the images. 
I inserted the location in each h ref to link the pages together. success
Social media icons with linked added, links defered to another new browser page using target-"_blank". 
Added images to the ladies.html. this commit was incorrectly spelled. 
I began adding the hero image to the contact.html page, I made some attempt to mobile optimise but as I was testing  I noticed that it functioned better if the hero image was fully displayed on the desktop but only partial on mobile which would not be mobile optimised. It heroed the ladies watches. So I left it as is, not mobile optimsed.  

I tested Media query visibilty hidden so that the content does no shtow on mobile, just the name of the watch and PaPal Buy now button but decided to not use Media query to hide anything as all information would be needed in mobile.

I collaberated at this point with my tutor and we agreed to bring more life to the website the easiest way possible. 

Google fonts Pidera was added to highlight the text that would catch the eye of the user. 

On the men.html/ladies.html a bootstrap corousel was added with new images. I thought in order to give more life would be to show more of the products in different lights. I took my own photos and sized them to 744x322 before i added them to the files. I had to re-adjust a few times as it did not look right. 

Initially I was going for a plane minimal but decided to give it a little more height and information. I googled bootstrap footer and contact us page and then applied the footer to the website and all pages. 

I centered and updated the headings on each page and the P on index.html to be more attractive. 

I removed the boarders around the bootstrap cards on men/html and ladies.html. 

I centered the form on contact.html by updating a div col to col-md-6 and removed space between body and footer by removing pt-5 in div.

Added spacing between products on ladies and men.html by changing MT-3 to mt-5 on bootstrap, added text name and ceo to aboutus.html with padding, switched conatct us button in footer to go under text. It looked off but it just makes it look nice and neat. 

In order to make the "Home of Luxury Watches" stand out I added padding of 30px above and below.

Looking at the images on ladies.html, the top two were too small, I resized top images to fit bootstrap card. resizing was done outside of gitpod and correct sized image added, this was a little challenging so for the corousel I decided to use css to size the images. I added new images and fixing the stretched look. 

I styles the footer to ensure the social media links were side by side with inline block value. 

Testing

The testing was basically every time a added html, bootstrap or a css style to see how it performed:

1. Broswer. 
2. Mobile
    I used Chrome dev tools to check each optimisation. 

I used Validator.w3.org to review the code within the pages for any errors. I had a few that needed resolving before my final push. 

I continuously moved through the website to see how it performed throughout the whole process. 

I used my last two mentor sessions to as my test sessions. Any feedback provided I updated as it was unbiased.

Test 1 - We looked at every page within detail to ensure that the code worked the way it should have. The pages had some aligning issues and would not center. My tutor assisted me with the best plan of action in order to allow centering with the use of class's and text align. The coorrect targeting and styling helped complete this process. 

Test 2 - I made significant changes to the body and footer and added a bootstrap corousel and bootstrap footer with some new images. again, i had some aligning issues with the bootstrap cards, contact us forms and spaces between body and footer. 

Test 3 was my own text to see how the website looked, everything seems to be working as it should with no more issues. 

I copy and pasted all code form each page to the ws validator and all passed with no errors, however, This is after I rectified the errors. 

I tried to add validaiton results however I was having issue. I have uploaded the text to https://validator.w3.org and all pages have passed. 

Issues:

I noticed a few issues when adding codes and this was all a result of missing code. For example, I was positioning the images in Men.html and Ladies.html and noties that the bootstrap colums were not working and the footer was moving from the bottom over the the very middle left of the page. Thsi was due to a missing closed div tag. 

After the second mentor session, aftert adding the carousel and new footer i noticed that there was spacing between the body and the footer, i made several attmepts to remove the spacing, however, in the end I received assitance from my mentor. I aldo had issue centering the contact us form, if I used CSS then it would not be mobile optimised. in the end, my mentor pointed out that I needed to update bootstrap code to center it. I centered the form on contact.html by updating a div col to col-md-6 and also provide more spacing between products in Men.html and ladies.html by changing the PT-3 to PT-5. 

Other issues I had was the image resolution. I tried to re-sixr them before re-adding them back to the images folder, it worked for some and not for others, the ones it did not work for I sized them in css. 

Deployment

Credits

Acknowledgements:
I would like to achnowledge Matt, the Code Institute tutor. I used his code from the Bootstarp 4 tutorial to place the background image into the index.html page. 

Youtube blondiebytes for assistance with responsiveness. 
