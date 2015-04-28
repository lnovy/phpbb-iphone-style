# Overview #
Mobile browsers are detected in the setup() function within the phpBB3 includes/sessions.php file. The browsers agent is compared to a list of keywords, common in mobile browser user agent strings.  If a match is found, the style for the session is set to that of the mobile theme, overriding the board and user style preferences.

# Notes #
The style needs to be installed as with any other style.  Once installed, it can be deactivated, meaning that users won't accidentaly select it from their desktop/laptop browser.  The style will still be usable though when the forum is accessed by a mobile browser though.