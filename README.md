# Shahinoor Alom Resume Website
Milestone One Project: User-Centric Frontend Development - Code Institute 

This is my personal resume website to present to prospective employers and clients. 
The website highlights my skills and educational experiences, including my coding skills, and a contact form.


## Demo
A live demo can be found [here](https://www.shumonsta.github.io/S).

## UX

### User stories

As a recruiter I expect to see a showcase of Shahinoor's resume.

![Resume](/assets/READMEdocs/Resume_Section.jpg "Resume")

### Strategy
I intended to make the design of the website as easy as possible to access the relevant information needed while making it user-friendly at the same time.

### Scope
I intended to showcase an overview of myself and my capabilities to prospective employers. 
They can access information relating to my background, work I've done and my skills, with the option to contact me if they choose.

### Structure
In the 'Work Experience' section, I want employers/recruiters/clients to be able to quickly access the work that I've done. I provided in the footer, a link to my LinkedIn profile, my twitter and facebook profile, and a downloadable PDF version of my CV.

### Skeleton
I followed the skeleton of the example bootstrap pages. 
Header (Navbar) -> Carousel -> About -> Resume -> Contact -> Footer

### Surface
A grey and black color scheme was chosen to create a sleek and modern feel.

## Technologies
1. HTML
2. CSS
3. Bootstrap 4

## Features
This site uses the scrollSpy feature in Bootstrap with an extra JavaScript function added to create a 'smooth scrolling' effect. The site also includes the Carousel featuure, taken from a Bootsstrap template. 

### Features Left to Implement
I would like to add a space on the website where I showcase a portfolio of my web projects. I would like to also add animations and a progress bar on the different coding languages.  

## Testing
The employer and recruiter user story achieved the intended outcome of providing them with a showcase of myself and my work. 
In the about me section, they can read about the skills I have acquired through the Code Institute, and if they're viewing on a desktop, the background of this section is a photo of me. 
They are also able to view my social media profiles via clicking on the icons in the footer. 
They are also able to download my CV by either clicking on CV in the footer, or by clicking on the button in the carousel. 
The CV will download to your default folder for downloads on click using the 'download' attribute. 
All links have been manually tested to ensure that they are pointing to the correct destination.

By clicking on the links in the navbar, the scrollSpy effect will work.

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) and on multiple mobile devices (iPhone 4, 5, 7: Chrome and Safari, iPad, Samsung Galaxy) to ensure compatibility and responsiveness. 
I added a media query to remove the background from the about section when viewing on smaller screen sizes so that the font doesn't blend in to the image. 

## Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named `index.html`.

To run locally, you can clone this repository directly into the editor of your choice by pasting `git clone https://github.com/shumonsta/Shahinoor.git` into your terminal. To cut ties with this GitHub repository, type `git remote rm origin` into the terminal.

### Content
All content on the website were written by me. 

### Media

All photos were taken from [Google Images](https://www.google.com/), with the exception of the photo of myself in the background of the 'about me' section in the desktop view.

### Acknowledgements
The scrollSpy delay JavaScript function was found through this tutorial [here](https://getbootstrap.com/docs/4.0/components/scrollspy/).
The Carousel and the Product templates were taken from Bootstrap websites:
[Product](https://getbootstrap.com/docs/4.0/examples/product/)

[Carousel](https://getbootstrap.com/docs/4.0/examples/carousel/)

