tumblr-roadtobatcountry
=======================

Tumblr theme with google maps integration for [roadtobatcountry](http://roadtobatcountry.tumblr.com), a blog about the West Coast USA road trip I did in 2013. It features attaching a geographical location to each post and a full-size moving Google Maps background that will pan to the location of the currently visible blog post as you scroll through the content.

Setup
-----

Edit your Tumblr theme and copy the HTML into the box. See the Tumblr help for more information.

To use the theme, you require the following Google API keys:

- Google Maps API
- Google Analytics (optional)

Tagging Locations
-----------------

You can attach a location to a post by adding a tag like `location: san francisco~ca`. Allowed separators are:

    ~
    .
    ;
    :
    -

It's important to be specific so the Google Maps API Geocoder understand what you are saying. Always at least provide the country or state. Saying `location: Hannover` will most likely not be enough as there are "Hannover"s in Germany as well as the US at least. Instead, say `location: Hannover~Germany`.

Tumblr Features
---------------

The theme only provides styling for a very simple blog with pagination. No pages are supported. Currently simply adding endless scroll would break the maps integration.

----
This theme is tailored specifically for my needs. You may use this as inspiration or just copy and adapt it. Please change the title of the blog though, as that will probably not fit your needs.

The layout of the page, colors and all graphics (which are not included in this repository) were created by Felix Meyer of [We Think Things](http://www.wethinkthings.com).

