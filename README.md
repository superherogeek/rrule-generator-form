# RRULE Generator Form
There are great resources for RRULE reading and processing, but I could not find a good HTML / JavaScript form that would generate a RRULE based on a user's input, as well as read a RRULE and populate the same form appropriately.   Using the iCal inputs for inspiration, I created this easy-to-use form.

## Usage
- Include **js/rrule-gui.js** in your HTML document.
- Use the HTML form found in **index.html**
- Don't forget to include the dependencies (jQuery, jQuery UI, and styles) found in the head of **index.html**

##Dependencies
* jQuery
* jQuery UI (used for the Datepicker)
* Bootstrap CSS (only used for the button styles out of laziness, will remove in future version)


##Processing RRULE
This form does NOT process the RRULE into it's individual recurring dates.  You'll need an RRULE processor for that.

- [jkbrzt/RRULE](https://github.com/jkbrzt/rrule) - Great JavaScript library for working with recurrence rules for calendar dates.
- [tplaner/When](https://github.com/tplaner/When) - PHP Library for recurring date handling