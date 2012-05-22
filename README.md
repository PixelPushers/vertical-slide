vertical-slide
==============

Example to demonstrate how to create a vertical slide on a touch screen.

An interesting use case for a vertical slide is as a select tool when you have several options and you want to allow someone to slide a block to select an option, like a volume slider (Example from jQuery UI: http://jqueryui.com/demos/slider/#slider-vertical).

The trick on a mobile touch screen is that when you want to click to slide, the whole page slides.  This technique prevents the default page from sliding and then move a block element along a Y axis.