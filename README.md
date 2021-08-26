
# Huddle-Landing-Page-FM Solution

This is my third Frontend Metnor challege [Huddle Landing Page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-curved-sections-5ca5ecd01e82137ec91a50f2).

![Screenshot](desktop-preview.jpg)

## Overview

* Mobile First approach - works on every device :ballot_box_with_check:
* SCSS :ballot_box_with_check:
* CSS Flexbox :ballot_box_with_check:
* CSS Grid :ballot_box_with_check:
* Pixel perfect :ballot_box_with_check:

## Features

In order to reduce the use of media I used fluid design. For paragraphs and headings I used: 

font-size: calc( 24px + (48 - 24) * (100vw - 320px) / (1440 - 320) ); 

24px is minimal size and 48 is maximum.

Starting breakpoint is 320px and maximum is 1440px. So font sizes adjusted in this way increase in proportion to the change in screen width of the device
