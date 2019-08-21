# Louis Gelinas 16AUG19
# Sprint Challenge: Advanced CSS - Space Walkers Web Page

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored advanced CSS techniques using Responsive Design and Preprocessing. During this Sprint, you studied how to use the viewport meta tag, media queries, setting up a preprocessor, and advanced use of preprocessing techniques. In your challenge this week, you will demonstrate proficiency by updating a website that is missing content as well as adding mobile styling.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in advanced css and your command of the concepts and techniques in responsive web design and preprocessing.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons) and your project manager.

## Description

The client for this challenge is _Spacewalkers Magazine_. Spacewalkers needs your help to build a small proof of concept website for their marketing team. They have provided designs for both desktop and phone views. In addition to designs and content they have most of the home page coded for you. You just need to finish the navigation and header as well as the mobile styles.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution design files of the desktop and mobile views:

[Click here to review the home design][1]

[Click here to review the mobile design][2]

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. What is the difference between an adaptive website and a fully responsive website?

An adaptive website senses the device, and has pre-made HTML templates that it serves based on the size/type of device connecting.

A responsive website has a single template with media queries that automatically adjust the pages content based on the size of the device. Responsive websites load much faster.

2. Describe what it means to be mobile first vs desktop first.

Mobile first means the base HTML / CSS file is built for a phone screen width, and  styles are changed/added through “min-width” media queries (roughly 500px to expand to tablet, 800px to expand to desktop). 

Desktop first means the base template is built for a desktop screen width, and styles are changed/added through “max-width” media queries (roughly 800px to shrink down to tablet, 500px to shrink down to mobile).

3. What does `font-size: 62.5%` in the `html` tag do for us when using `rem` units?

It sets our root font-size (the one defined in the html tag) to be relative to the user’s font settings. If all font-sizes throughout the page are defined in “rems,” that means our entire site will be cascaded off the user’s personal settings for font size.

4. How would you describe preprocessing to someone new to CSS?

Preprocessing lets you write, shorter, simpler, more elegant code for styling your website.  The preprocessor then turns your code in the redundant and byzantine cascades required by CSS to achieve your desired effect.

5. What is your favorite concept in preprocessing? What is the concept that gives you the most trouble?

Nesting! Simply making my CSS mirror my HTML makes styling much easier. The most difficult is imports— although I understand for an extremely large website this would be easier, as a solo programmer having multiple files to work from is unnecessary pain.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section *will* prevent you from passing this challenge.

## Project Set Up

Follow these steps to set up your project:

### Git Set up
COMPLETE
 
Follow these steps for completing your project.

COMPLETE
 
### Preprocessor Set up

COMPLETE

## Minimum Viable Product

Your finished project must include all of the following requirements:

### Import LESS Files

* [X] Navigate to your `index.less` file. Notice the file is blank. You have been asked to use a certain import order. That order is as follows:

```markdown
1.variables.less
2.mixins.less
3.reset.less
4.global.less
5.navigation.less
6.footer.less
7.home-page.less
```

_You will know everything is working properly when you see the styles enabled for the provided content._  

### Home Page - Desktop HTML & LESS

* [X] Take 10 minutes to review the code that has already been provided for you. Take time to see how the home page was built.

* [X] Add a viewport meta tag to the head of your index.html page

* [X] [Review the provided home desktop design file](design-files/home-desktop.png). You are to build the missing navigation system and header image. You have been provided all content necessary in the [index.html file][3]

* [X] Navigation Styles: Use the `navigation.less` file for styling.

* [X] Main Content Styles: Use the `home-page.less` file for styling

* [X] LESS Mixins: Create and use 2 different mixins to aid your styling. Use the `mixins.less` file for your mixins

* [X] LESS Parametric Mixin: create a parametric mixin that is used to create the `sign up` button styles.

* [X]  Use at least 2 parameters to create your button

* [X] Create a hover state that swaps the background color and font color of the base button styles.

### Mobile Design

* [X] Create a `@phone` variable that contains a `max-width: 500px` media query string. Use the `@phone` variable for all your nested mobile styling.

* [X] [Review the provided home mobile design file](design-files/home-mobile.png). Match your mobile styling the best you can using the design file.

* [X] Push your changes and create a pull request if you haven't already.

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

* [-] Build a page of your choosing from the navigation items. Come up with content and images that fit the theme.

* [X] Introduce CSS animations to your site.

Animated the transition of the signup button

* [X] Create a fixed navigation and add some opacity to the background

Fixed the navigation bar and provided opacity to just the background color of the nav bar

* [ ] Create a form that would allow someone to sign up for a Spacewalkers Magazine subscription

[1]:	design-files/home-desktop.png
[2]:	design-files/home-mobile.png
[3]:	index.html