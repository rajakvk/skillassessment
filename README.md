#SAPIENT | INTERACTIVE | India Studio

##SKILL ASSESSMENT EXERCISE

###Requirement Document

The exercise is to build a simple webpage based on Responsive Design approach coded in HTML5/CSS3 with JavaScript/jQuery. The HTML/CSS code should be semantic, AA Accessibility compliance. JS code should be validated with JSLint/JSHint.

Example layout for three screen dimension are given below

* Desktop Version 1024x768 (https://github.com/rajakvk/skillassessment/blob/master/docs/deskTop.jpg)
* Tablet Version 768x1024 (https://github.com/rajakvk/skillassessment/blob/master/docs/iPad.jpg)
* Mobile Version 320x480 (https://github.com/rajakvk/skillassessment/blob/master/docs/iPhone.jpg)

##Requirement for some important components

1. Recent Activities
  * Icons and text should be clickable
  * Connect
    ** These are static icons, Social media integration is optional (good to have)
2. Hero Carousel
  * This carousel and the overlay should be JSON driven.
  * Dots at the bottom represent pagination; there should be 9 items in carousel, one dot represents 3 items.
  * On click of dot, the carousel should move to next or previous set of items. 
  * Carousel should be Mobile/Tablets friendly, should work with finger swipe. Use jQuery Touch for this functionality (Optional)
  * On clicking the arrows the next product should load up – the first and last products will decide if the previous and next arrows are enabled or not.
  * On click of the next arrow – the data will get loaded from a static html or getting data from a XML or JSON. This will happen only for the first time, and once the data is in the DOM, the regular previous next should work.
  * On click of any item in carousel, an overlay gets open with bigger picture and related text in it. Refer point 3 for more information on it.
3. Overlay
  * The overlay data should be JSON driven; ideally the object used in carousel should be used here as well.
  * Previous & Next link will be disabled or enable based on item viewed and on click of next should show the next item in the carousel on the main page, same applies to previous link as well.
4. Video player
  * HTML5 Video player
  * Should have fallback/ polyfill for legacy browsers
  * On click of arrow icon video should start playing
  * Fetch some sample videos or use any online sample videos URL for playing purpose
  * Format supported by HTML5 video player are H.264 / MP4 (.mp4), VP8 / WebM (.webm), Ogg Theora (.ogv)
5. Personal Information form
  * Use HTML5 form elements and its validation techniques
  * For validations do not use any JavaScript, it should be HTML5 driven
  * Fallback for placeholder attributes (Optional/Good to have)
6. Yearly Report
  * Implement this table using JavaScript and JSON. We are looking at clean, well factored object oriented code.
  * Respective data to be populated on change of year in the dropdown.

## General Guidelines
1. The page needs to be coded using HTML5/CSS3 with backward compatibility on IE7
2. Use modular approach in html to keep design & code responsive to different screen areas and devices
3. Code needs to be Semantic & “AA” Accessibility compliance.
4. You can use any library of your choice, preference is jQuery
5. are IE7+, Firefox Latest, Chrome and Mac Safari
Note: Legacy Browser does not support Responsive Design Legacy browsers: IE 6/7/8
8. Follow Progressive enhancement approach. Follow the following for more details on Progressive enhancement:
  * http://coding.smashingmagazine.com/2009/04/22/progressive-enhancement-what-it-is-and-how-to-use-it/
9. You can test your exercise for Responsive Design on Chrome without using any specific device. Refer the following document for the same.
 TestTheDesign.docx
10. Refer the following links to read more on Responsive Design Approach
  * http://coding.smashingmagazine.com/2011/01/12/guidelines-for-responsive-web-design/
  * http://www.spoonfulcom
  * http://johnpolacek.github.com/scrolldeck.js/decks/responsive/
11. Refer to the following SVN location to fetch PSD files for the exersice.
  * https://github.com/rajakvk/skillassessment/tree/master/docs