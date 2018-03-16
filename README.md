# Theme for "Fun with vh and vw units" presentation

This is a theme I built to support my PNW Drupal Summit presentation, "Fun (but not too much fun) with vh & vw units".

## Warning

This code is more than a little crazy -- I essentially used twig templates to hard code all of my HTML markup (and content).  There was a method to my madness, however, as my web site became a sort of "living slide deck" for my presentation.

## Context

To view the entire presentation, please enjoy the [session video](https://pnwdrupalsummit.org/2018/sessions/having-fun-not-too-much-fun-vw-and-vh-units).

You may also visit the web site used in this presentation, at [bixgomez.com](http://bixgomez.com).

## Session description

Back in the day, pixels were a themer's best friend when it came to setting dimensions in CSS.  Way back in the day, they were a themer's ONLY friend.  Then came em (and rem) units.  For the past several years, as vw (viewport width) and vh (viewport height) units have enjoyed wider support among modern browsers, they have become increasingly popular among themers.

In this session, I will take participants along on my journey into the wonderful world of these latest scalable units, and how we can use them in conjunction with Sass to yield displays that are more consistent at any viewport size.  I will show how scalable units can help ease the pain of unpredictable results when content editors are let loose in a WYSIWYG environment; through the creative use of scalable units, we can create pages that are closer to their authors' intent.

I will also highlight cases where the use of vh and vw units might yield undesired results (such as unreadably small or unreasonably large text), and I will demonstrate how I have used Sass logic and math to overcome these obstacles.
