# Lista de Temas para XI Feira Tecnologica

JQuery Mobile aplication with list about themes for articles in FGF college

ACESS LINK: <http://temas-feira.surge.sh/>

![](http://demos.jquerymobile.com/1.2.1/docs/_assets/images/jquery-logo.png)

A Touch-Optimized UI Framework built with jQuery and HTML5.

jQuery Mobile is the easiest way to build sites and apps that are accessible on all popular smartphone, tablet and desktop devices. For jQuery 1.7.0 to 1.8.3.

### jQuery Mobile Overview

jQuery's mobile strategy can be summarized simply: A unified user interface system that works seamlessly across all popular mobile device platforms, built on the rock-solid jQuery and jQuery UI foundation. Focused on a feature-rich but lightweight codebase built on progressive enhancement with a flexible theming system and ThemeRoller tool.

The framework includes an Ajax navigation system that brings animated page transitions and a core set of UI widgets: pages, dialogs, toolbars, listviews, buttons with icons, form elements, accordions, collapsibles, and more.

The critical difference with our approach is the wide variety of mobile platforms we're targeting with jQuery Mobile so no browser or device is left behind. We've also focused on making jQuery Mobile easy to learn with a simple, markup-based system to applying behavior and theming. For more advanced developers, there is a rich API of global configuration options, events, and methods to apply scripting, generate dynamic pages, and even build native apps with tools like PhoneGap.

To make this broad support possible, all pages in jQuery Mobile are built on a foundation of clean, semantic HTML to ensure compatibility with pretty much any web-enabled device. In devices that interpret CSS and JavaScript, jQuery Mobile applies progressive enhancement techniques to unobtrusively transform the semantic page into a rich, interactive experience that leverages the power of jQuery and CSS. Accessibility features such as WAI-ARIA are tightly integrated throughout the framework to provide support for screen readers and other assistive technologies.

### Getting Started with jQuery Mobile

jQuery Mobile provides a set of touch-friendly UI widgets and an AJAX-powered navigation system to support animated page transitions. Building your first jQuery Mobile page is easy. Here's how:

### Create a basic page template

Pop open your favorite text editor, paste in the page template below, save and open in a browser. You are now a mobile developer!

Here's what's in the template. In the head, a meta viewport tag sets the screen width to the pixel width of the device and references to jQuery, jQuery Mobile and the mobile theme stylesheet from the CDN add all the styles and scripts. jQuery Mobile 1.2 (1.2.1) works with versions of jQuery core from 1.7.0 to 1.8.3.

In the body, a div with a data-role of page is the wrapper used to delineate a page, and the header bar (data-role="header") and content region (data-role="content") are added inside to create a basic page (these are both optional). These data- attributes are HTML5 attributes used throughout jQuery Mobile to transform basic markup into an enhanced and styled widget.


```

<!DOCTYPE html> 
<html> 
<head> 
	<title>My Page</title> 
	<meta name="viewport" content="width=device-width, initial-scale=1"> 
	<link rel="stylesheet" href="http://code.jquery.com/mobile/1.2.1/jquery.mobile-1.2.1.min.css" />
	<script src="http://code.jquery.com/jquery-1.8.3.min.js"></script>
	<script src="http://code.jquery.com/mobile/1.2.1/jquery.mobile-1.2.1.min.js"></script>
</head> 
<body> 

<div data-role="page">

	<div data-role="header">
		<h1>My Title</h1>
	</div><!-- /header -->

	<div data-role="content">	
		<p>Hello world</p>		
	</div><!-- /content -->

</div><!-- /page -->

</body>
</html>

```

### Add your content

Inside your content container, you can add any standard HTML elements - headings, lists, paragraphs, etc. You can write your own custom styles to create custom layouts by adding an additional stylesheet to the head after the jQuery Mobile stylesheet.

