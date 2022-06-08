# Aviation Abbreviations

In the world of aviation, a very wide variety of different abbreviations is used. There's so many that even the most experienced aviators don't know about all of them. Aviation Abbreviations is a website that tries to shine a light on a selection of the most used abbreviations in aviation. Feel free to take a look around and make yourself familiar with some of the abbreviations used in aviation. 

![Responsice Mockup](https://jve89.github.io/portfolio1/assets/images/responsive-mockup.jpg)

## Features 

Aviations Abbreviations consists of a welcome page with a nice high resolution photo of an airplane which is interactive and by clicking it brings you to the most important page of the website, namely the list with abbreviations. The list of abbreviations is also accessible trough the header and footer menus, which consist of the home, list and contact links. The footer menu contains on top of that external links to social media platforms suchs as Facebook, Instagram and Twitter. The contact page consists of a contact form, contact address and google maps location chart. The Aviation Abbreviation logo in the top left corner of each page will bring you back to the home page by simply clicking it. 

By the way... Did you find the eastern egg hidden somewhere on the website ;)

### Existing Features

- __Header & Navigation__

  - The header inclused the website logo in the left corner which is responsive and by clicking brings you back to the home page.
  - The navigation bar is responsive and includes links to the home page, list page and contact page. 
  - This section of the website will allow the user to easily navigate from and to each page. The website is designed in such a way that it responses to the size of your screen and shows you the most useful layout. 

![Nav Bar Desktop](https://jve89.github.io/portfolio1/assets/images/header-wide.png)

![Nav Bar Mobile](https://jve89.github.io/portfolio1/assets/images/header-narrow.png)



- __Homepage Photo__

  - The homepage shows an interactive, high resolution photo of flight crew boarding an aircraft. As stated, the photo is interactive which means by cicking, it brings you to the abbreviation list page. 
  - The photo used is a copyright free image and was found through google by searching for airplane photos with commercial usage right licenses.

![Homepage Photo](https://jve89.github.io/portfolio1/assets/images/home-photo.png) 

- __Abbreviation List__

  - The abbreviation list page is where this website is all about. Here you find a selection of widely used aviation related abbreviations.
  - The list is ordered from A to Z. Every letter is clearly seperated by a clear border for a semantic feeling.

![Abbreviation List](https://jve89.github.io/portfolio1/assets/images/abbreviations-example.png)

- __Contact Page__

  - This page consists of a contact form to get in contact with the developer of the website through email. Also, you'll find here a section with usefull information, such as the address of the developer as well as an interactive map from google.
  - The photo used in this readme is copyright free from the website pixabay.com.

![Contact](https://jve89.github.io/portfolio1/assets/images/contact.png)

- __The Footer__ 

  - The footer of Aviation Abbreviation is the same throughout every page and consists of a non-interactive logo in the left corner with a slogan underneath and an interactive menu on the right side which consists of the same menu items as in the header of the website as well as links to social media platforms like: Facebook, Instragram and Twitter.
  - The footer is like every aspect of the website responsive to the size of the screen you visit the website on. The footers vary slighty from each other in the aspect of font size and spacing between the rows.

![Footer Desktop](https://jve89.github.io/portfolio1/assets/images/footer-wide.png)

![Footer Mobile](https://jve89.github.io/portfolio1/assets/images/footer-narrow.png)

### Features Left to Implement

- This website will in the future display a much more comprehensive list of aviation related abbreviations. 
- The website will be styled to look more modern.
- The logo will look more sophisticated in the future.

## Testing 

Aviation Abbreviation has been tested on multiple web browsers installed on multiple devices. In this chapter, I'll explain the features that I've tested and the outcome of the tests. Any interesting highlights (bugs, problems, etc.) that I found will be discussed here as well. 

For the tests, I used both a Lenovo Ideapad 340 laptop and a Samsung Galaxy S21FE Android smartphone. The browers installed on the laptop are Chrome Version 102.0.5005.63, Firefox Version 101.0 and Edge Version 102.0.1245.33. The browsers installed on the smartphone are Chrome Version 102.0.5005.99, Firefox Version 101.1.1 and Opera Version 69.2.3606.65175. All of these browsers are considered the latest updates at the time of writing (08/06/2022).

Chrome (desktop)

- All buttons work.
- The current active page shows a line under the menu item (both in header and footer).
- Hovering over the menu item underlines it as well.
- Clicking the home photo brings you to the abbreviation list.
- Clicking the website logo brings you back to home.
- All social media links work.
- Contact form works but only using your own email client.
- Contact address readible in full width (desktop) all the way down to a minimum width of 320px (mobile).
- interactive map visible in full width (desktop) all the way down to a minimum width of 320px (mobile).
- List items well readible in full width (desktop) all the way down to a minimum width of 320px (mobile).
- Hidden eastern egg works as well!

Below a width of 320px, weird stuff starts to happen. the viewport starts to get too narrow to show all website properties without overlapping or shifting to another location.

Firefox and Edge have been tested the exact same way and have the exact same outcome. For that reason, I won't list the same items once again. The only difference was the loading speed in Edge which was noticably slower. 

Chrome (mobile)

- All buttons work.
- The current active page shows a line under the menu item (both in header and footer).
- Clicking the home photo brings you to the abbreviation list.
- Clicking the website logo brings you back to home.
- All social media links work.
- Contact form unfortunately doesn't work (405 not allowed).
- Contact address readible.
- interactive map visible.
- List items well readible.
- Hidden eastern egg works as well!

Just like on the desktop, the testing went exactly the same in both other browsers. The contact form not working happened in these browsers as well.

### Validator Testing 

- HTML
  - Initially 4 errors were detected. After debugging, the test returned without any errors or warnings in the W3C HTML validator [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjve89.github.io%2Fportfolio1%2F)

- CSS
  - No errors were found when passing through the official Jigsaw CSS validator [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjve89.github.io%2Fportfolio1%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs
 
 - The contact form is not working correctly because I still lack the knowledge about this. Altough the contact form works on the desktop, it's a but flawed since you have to submit the form through your own email client. This subject definitely needs more attention in the future.
 
 - Some of the block elements are not perfectly alined. It took an eternity to code it the way it is. I need more experience to be able to do a better job but for a first website, I'm happy with the result.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the pages side menu, select the 'main' branch source
  - Once the main branch source has been saved, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://jve89.github.io/portfolio1/


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site


Congratulations on completing your Readme, you have made another big stride in the direction of being a developer! 

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 