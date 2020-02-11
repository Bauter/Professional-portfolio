# Updated-portfolio-themed
Updated developer portfolio using paid theme from themeforest.

## Link to live pages ##

https://bauter.github.io/Updated-portfolio/

## What you will need ##

1. A code editor, I prefer Visual Studio Code ("https://code.visualstudio.com/").
2. An understanding of Bootstrap 4 ("https://getbootstrap.com/") (this themes has bootstrap linked, please read the documentation to understand the many classes and styling attributes being utilized, or how you can build upon this theme with).
3. An account with Form Spree *optional* ("https://formspree.io/").

## Link to theme ##

https://themeforest.net/item/alison-portfolio-html-template/23151102\

## How to ge started ##

-Go to the link above and purchase theme "Alison".
-Download Zipped Folder titled "Master" and extract to a location on your computer.
-Please review the documentation folder inside "master" in the foloowing order:
 1. Inside you will find a index.html file. Please copy and paste this code inside your preferred code editor.
 2. Right click and open the file in your default browser to view.
 3. Carefully read through the page to understand how to approach this theme.
-When ready, copy the directory called "alison" and paste it into your project directory.
-You are now ready to make your changes.

## Moving Forward ##

-You will notice most of the hard work is already done for you. Take a moment and carefully read through the code, paying attention to selector names and reading each comment to understand how the code works.
-Ultimately it is up to you what to change. Below are the steps I took with this theme.

## Where to start ##

### Index.html ###

-There are a variety of img placeholders in the img file, My first step was to start with creating my portfolio section, putting project links in with a class selector shared by the themed buttons, and removing the default "zoom" image and replacing it with two links. Then place your project image in the parent element to the "hover div".

-Since I was not planning on using the image carousel I removed this and all associated code along with the "see my works" button under the H2 section name tag.

-Background images for each section div can be assigned in the "main.css" file. 

-Feel free to change the styling to how you see fit.

-Next I changed the "Alison logo" in the header div to my name.

-In the nave bar, links must be assigned. Whether to new .html files, or by ID to different sections on the index.html. (I chose to do both). 

-The icons, text, headers, and buttons all tweaked to my preference

-Text changed to what I wanted my page to say and how I wanted it divided up.

-An additional div was created in the "contacts" section to display my personal phone number.

-Google Maps location was removed. Google-maps directions can be embedded from google maps. But you will find it difficult to use what is supplied by the theme as google-maps API is no longer free and requires an account for use. That being said this was removed from my page as well.

### Credit.html ###

-I then chose to place a link in my footer to a new file called "credit.html". (up to you if you wanted to assign a target attribute of "_blank" to opwn a new page)

-From here I copied the index.html code over and only the "header", "portoflio", and "footer" sections over (to keep a similar format and styling).

-The purpose of this div was to give credit for all the photos I acquired from (www.pexels.com) and (unsplash.com).

-Duplicate portfolio divs were then created (beyond the original 6), to hold all add. images.

-Inside each "hover" class div, The link tags where removed and a simple paragraph tag took its place with text giving credit to the photographer/ designer. This allowed the page to remain clean, and the credit to be visible on hover over each image (just link the project link and repo buttons).

-Change the links in the nav bar to "index.html#home", "index.html#about" etc. to link back to original page in case the user decides to navigate back (this is not entirely necessary, but the links will be broken in the header without doing so, the only other option is to remove them).

### Contact.html ###

-Create a new file titled "contacts.html".

-Just link with credits.html, copy the index.html code with the "header", "contact", and "footer" sections.

-Change the links in the nav bar to "index.html#home", "index.html#about" etc. to link back to original page in case the user decides to navigate back (this is not entirely necessary, but the links will be broken in the header without doing so, the only other option is to remove them).

#### Why was this done? ####

-In the original theme documentation, you will read about reference to 2 lines within the "contacts.php" file that should be tweaked to link your email. Due to numerous errors when working with this product I chose to Delete both the "contacts.php" and "contacts.js" files. 

##### To work around this... #####

-Instead I used "Formspree"(formspree.io). Used as such:
 1. Create a free account with formspree.io.
 2. Once created, navigate to your account page and click on "create a new form".
 3. Form spree will then provide you with a link to place within your form inside "index.html" under the "action" attribute.
 4. From here test the form, upon submission you will notice you are re direct to a form-spree page confirming the message was successfully sent.

-To avoid back stepping through to get back to the index.html webpage. I found it easier to create a new file called "contacts.html".

-From here I removed my contact form and cell phone number, and create a button below the h2 tag linking to the contacts.html page AND assigning a target attribute of "_blank".

-This was done to open a new window, that once the form has been submitted can be closed out, without closing the portfolio page (thanks Kathy and Rebecca!).

### Clean up ###

-In order to clean up your code, carefully go through your files and delete/remove anything that is no longer being utilized to increase loading speed.

## Final thoughts ##

-This project was a fun way to create a high end portfolio webpage. Ultimately how you choose to utilize it is up to you. Have fun with it!

## Guidelines for Collaboration ##

-As I am still new to coding, and my initial projects will be used to create a portfolio to show to potential employers, i ask that no modifications are made at this time.

#### However ####

 -Any input to improve my coding would be GREATLY appreciated. I am not opposed to the files being pulled for the sake of modifying and using as an example to teach/explain alt. methods, better practice, etc. Again I would ask they not be pushed to the repo to modify the initial document, but instead be sent to me an some alt. way.

 --Thank you for taking the time to look over this 'README' file--





