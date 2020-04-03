

**Q. 1.What is Bootstrap 4?

Ans : Bootstrap 4 is the current version of Bootstrap. Bootstrap 4 is basically an HTML, JavaScript and CSS framework. Bootstrap 4 is popular among the developer across the globe for building mobile-first and also responsive sites with a Bootstrap content distribution network and the template starter page. Bootstrap 4 is free to download and use.

** Q. 3.Can you list the difference between Bootstrap 3 and Bootstrap 4?



** Q. 4.Why we use Bootstrap 4?

Easy to use: Anyone who has the fundamental knowledge of the HTML and the CSS can start working on Bootstrap
Responsive feature: The responsive CSS of Bootstrap adjusts to phones, tablets, and even desktops
Mobile-first approach: In this version, the mobile-first styles are the part of the core framework
Browser compatibility: Bootstrap 4 is compatible with the leading browsers like Google Chrome, Internet Explorer 10+, Mozilla Firefox, Edge, Safari & Opera.



** Q. 5.Can you explain the basic Structure of a Bootstrap 4 Grid?

The Bootstrap 4 grid System is developed with flexbox has a limit of 12 columns across the entire page. If a developer does not want to use the 12 columns individually then, it can be merged to create a full column. The grid system in Bootstrap 4 is responsive and also depending upon the screen size the columns are re-arranged dynamically. The UI developer has to make sure that the sum must be 12 or less than 12.

The bootstrap 4 grid system has the following five classes:-
col- (for an extra small devices whose screen width less than 576px)
col-sm- (for a small devices whose screen width equal to or greater than 576px)
col-md- (for a medium devices whose screen width equal to or greater than 768px)
col-lg- (for large devices whose screen width equal to or greater than 992px)
col-xl- (for xlarge devices whose screen width equal to or greater than 1200px)
The above classes can be united to create a flexible and dynamic layout.


** Q. 6.What new in Bootstrap 4? Explain

Bootstrap 4 is a significant change from it’s earlier versions. Following are some of the necessary changes:
CSS is moved from LESS model to SASS model.
Print pages: Support for printing pages ensures that the size of the printed page is good enough on larger screens. This is done using flex and new print styles.
By adding uniform code for custom and regular checkbox and radio buttons, form validations are now much more accessible.
For JS behaviors “data” attribute is used and for group toggling “btn-group-toggle” is added newly.
Table classes are now named “dark-*” instead of “inverse.”

** Q. 7.List the different image shapes & Corners used in Bootstrap 4?

Bootstrap has the following image shapes and Corners:-
Rounded Corners
circle
Thumbnail
Aligning Images
Responsive Images
Centered Image
Rounded Corners:-

  The class .rounded add round corners to the image .

syntax:-

   <img alt="Statue of unity" class="rounded" src="Statueofunity.jpg">

Circle :-

 The class .rounded-circle turns the shape of the image to a circle.

Syntax:-

  <img alt="Statue of unity" class="rounded-circle" src="Statueofunity.jpg">

Thumbnail:-

  The class .img-thumbnail turns the shape of the image to a thumbnail, i.e. bordered image.

Syntax:-

  <img alt="Statue of unity" class="img-thumbnail" src="Statueofunity.jpg">

Aligning Images:-

An image is aligned to the left with the class .float-left and an image is aligned to the right with the class .float-right

Syntax:-

  <img class="float-left" src="Statueofunity .jpg">

  <img class="float-right" src="Statueofunity .jpg">

Centered Image:-

 The classes .mx-auto (margin:auto) & .d-block (display:block) align the image at the center.

Syntax:-

   <img class="mx-auto d-block" src="Statueofunity .jpg">

Responsive Images:-

The responsive images adjust themselves dynamically according to the size of the screen. The class .img-fluid is added to the <img> tag to create a responsive images. The class .img-fluid gives max-width: 100%; & height: auto; to the image that has to be responsive.

Syntax:-

<img alt="Pune" class="img-fluid" src="img_Pune.jpg">

**Q. 8.Explain Bootstrap 4 Tables?

A Bootstrap 4 table has very light padding and has a horizontal divider. The class .table gives primary styling to a table.

Striped Rows:- The class .table-striped gives the zebra-stripes to a table.
Bordered Table:- The class .table-bordered gives borders on all the four sides of the table and between the cells.
Hover Rows:- The class .table-hover gives a grey background color or a hover effect on the rows of the table.
Dark Striped Table:- .table-dark & .table-striped are combined to create a dark and striped table.
Borderless Table:- The class .table-borderless removes the borders all from all the four sides of the table and between the cells.
Contextual Classes:- Contextual classes are used to color the entire table (<table>) or rows of the table (<tr>) or cells of the table (<td>). Some of the contextual classes are:-
                  1 .table-primary—it is blue in color, and it shows a significant action.

                  2 .table-success-it is green in color, and it shows a successful or a positive action

                  3 .table-warning -it is orange in color and it shows a warning and needs attention.

Table Head Colors:- The class .thead-dark gives a dark black background to the headers of the table, and the class .thead-light gives the light grey color to the headers of the table
Small table:- The class .table-sm makes the table small in size by cutting the cell padding in half.
Responsive Tables:- The class .table-responsive creates a responsive table which means if needed, on the screens less than 992px wide, a horizontal scrollbar is added to the table and if the more than 992px then no difference.

** Q. 9.Explain Bootstrap 4 Positions.

Bootstrap 4 Positions rapidly configure the position of the elements. The positioning classes are .position-static, .position-relative, .position-absolute, .position-fixed, .position-sticky.

There are three positions in Bootstrap 4:-
Fixed top:- Here the position of an element is at the top of the viewport from an edge to an edge. Syntax:-<div class="fixed-top">...</div>
Fixed bottom:- Here the position of an element is at the bottom of the viewport from an edge to an edge. Syntax:-<div class="fixed-bottom">...</div>
Sticky Top:-Here the position of an element is at the top of the viewport from an edge to an edge but only after the user scrolls down below the position of the element. Syntax:- <div class="sticky-top">...</div>

** Q. 10.How many colors in Bootstrap 4? Explain

There are two types of Bootstrap 4 colors:-
Text Colours
Background Colours
Text Colours:-

Bootstrap 4 has few contextual classes which can be used to give "meaning through colours". The classes for the text colours are: .text-muted, .text-success, .text-info, .text-primary, .text-danger, .text-secondary, .text-dark, .text-white, .text-body (default body colour/often black) and .text-light. Contextual classes can be used on links, and this will add a darker hover color. 50% opacity for black or white text can be added with the classes .text-black-50 or .text-white-50.

Background Colours:-

The background colours classes are .bg-primary, .bg-warning, .bg-info, .bg-success, .bg-danger, .bg-secondary, .bg-dark & .bg-light. Since the background colours do not set the colour of the text therefore the developer have to use them with the clas .text-*

** Q. 11.Explain media objects in bootstrap 4?

Bootstrap 4 gives an effortless way to align the images and the videos along with the content. 
We can use media objects to show tweets, comments on blogs and many more things. 
To have a media object the container needs to have a class named .media and for the content of the media, a child container needs to be created with a class attached .media-body

To make sure sufficient spacing is given used padding and other tags as needed. We can have more than one media objects nested with each other. You can add another .media class in a container with a class of .media-body. Alignment to the right can be done by adding an image after .media-body container. For Bottom, top or middle alignment we can provide utilities of flex such as align-self*



Q #1) Define Bootstrap. (or ) What is Twitter Bootstrap?

Answer: 
Bootstrap is a sleek, intuitive, and powerful mobile first front-end framework for faster and easier web development.
It uses HTML, CSS and Javascript.
Its layout is very responsive, fast and easy to use. 
It mostly focuses on building a mobile application with having design templates for creating UI like Dropdown, Forms, Buttons, Alerts Tab, etc.




Q #2) Why Bootstrap is used for Web development? 

Answer: 
Bootstrap can be used as −



Mobile first approach 
− Since Bootstrap 3, the framework consists of Mobile first styles throughout the entire library instead of in separate files.

Browser Support − It is supported by all popular browsers.

Popular Browser
Easy to get started − With just the knowledge of HTML and CSS anyone can get started with Bootstrap. Also the Bootstrap official site has a good documentation.

Responsive design − Bootstrap's responsive CSS adjusts to Desktops,Tablets and Mobiles.

Provides a clean and uniform solution for building an interface for developers.

It contains beautiful and functional built-in components which are easy to customize.

It also provides web based customization.




Q #3) Explain the features of Bootstrap.

Answer: Its features include:

Open source for use
Compatibility with all browsers.
Responsive designs
Easy to use and fast.

Q #4) Define the key components of Bootstrap.

Answer: Its components include:

Scaffolding: It has the grid system, background, styles.
JS Plugins: Contains JS and jQuery plugins.
Customize: Can customize frameworks.
CSS: Contains CSS files.

Q #5) What do you understand by Bootstrap container?

Answer: Bootstrap container behaves like a container where you can put HTML code and it is a part within the page where the content of the site can be placed to make it responsive and fast.

Q #6) What do you mean by Bootstrap Classloader?

Answer: Bootstrap class loader is a part of java and a main parental class of class loader.

Q #7) How many types of layouts are there in Bootstrap?

Answer: There are two types of layouts in Bootstrap.

They are:

Fluid Layout
Fixed Layout
Q #8) Define Fluid Layout.

Answer: Fluid Layout is useful when you need to make an app that involves the full width of the screen i.e. Fluid Layout adjusts itself according to the browser size.

Q #9) Define Fixed Layout.

Answer: A fixed layout is responsive and easy to use but just like the fluid layout, it cannot adjust itself according to the browser size. The fixed layout should be 940 px in most cases.

Q #10) How can you display code in Bootstrap?

Answer: You can display the code in two ways i.e. by using the <code>tag and by using the <pre>tag.

Q #11) When will you use <code>tag and <pre>tag?

Answer: <code>tag is used to show the code inline and <pre>tag is used to show code with multiple lines.

Q #12) What is a progress bar in bootstrap?

Answer: Progress bar is used with HTML tag style in HTML element using <progress> keyword. In bootstrap, we use html5 <progress> with CSS classes that have special features in bootstrap, which is only made for the progress bar.

Q #13) Name the contextual classes that are used with the progressive bar in bootstrap.

Answer: The contextual classes used with progressive bar are as follows.

Progress-success
Progress-info
Progress-warning
Progress-danger
Q #14) What are responsive utility classes in Bootstrap?

Answer: Responsive utility classes in bootstrap are a set of classes that are used to conceal or exhibit the HTML elements based on screen resolution that discerns by media query in bootstrap.

Example: “hidden-md-down”, It hides

Q #15) What are the different button styles in Bootstrap?

Answer: In bootstrap, there are seven styles which we can use with the bootstrap button.

.btn-default.
.btn-primary
.btn-success
.btn-info
.btn-warning.
.btn-danger.
.btn-link.
Q #16) What are Bootstrap alerts?

Answer: This is used to create presume alert messages, which adds style to the messages to look more noticeable to the user.

There are four classes in alerts: .alert-success, .alert-info, .alert-warning, .alert-danger.

Q #17) Define Bootstrap thumbnails.

Answer: It is a way to use the layout images, videos, text, etc. in a grid system. We can create thumbnails by adding a tag with the class .thumbnails around the image.

This will add four pixels of padding and a grey border.

Q #18) Explain Modal plugin in Bootstrap.

Answer: A model is an inherited window that is layered over its parent window. This is used to augment the user experience and adds different functionalities to the users. Model windows are created with the help of the modal plugin.

Q #19) Which class is used for pagination in Bootstrap?

Answer: To add pagination on the webpage we have to use the class .pagination.

Q #20) Explain what is Bootstrap collapsing elements.

Answer: It allows you to collapse any particular element without using any JavaScript code.

To use this feature in bootstrap you have to add data-toggle=” collapse” to the controller element along with a data target to automatically assign the control of a collapsible element. We can use this by writing .collapse(options) etc.

Q #21) What is Bootstrap Well?

Answer: Bootstrap well is a form of container which thrives or makes the content look recessed on the web page. It also wraps the content by using .well class.

Q #22) Explain the uses of the carousel plugin in Bootstrap.

Answer: Carousel plugin in bootstrap is used to make sliders in the web pages or your site. There are several carousel plugins that are used in bootstrap to display large contents within a small space by adding sliders.

Example: .carousel(options), .carousel(‘pause’), .carousel(cycle’), .carousel(‘prev’), .carousel(‘next’).

Q #23) What will be the output of the below code and why?

 <div class="progress">
<div class="progress-bar progress-bar-success" style="width: 65%">
<span class="sr-only">75% successfully completed</span>
</div>
<div class="progress-bar progress-bar-warning" style="width: 20%">
<span class="sr-only">30% completed with warnings</span>
</div>
<div class="progress-bar progress-bar-danger" style="width: 15%">
<span class="sr-only">15% did not complete</span>
</div>
</div>
Answer: If we place multiple bars with the same .progress parent element, Bootstrap will pile them into one single progress bar. As we know, in bootstrap the sum of the progress bar is 100 %. So, the progress bar will give the result as full width and fully populated.

Q #24) How can we customize links of pagination in Bootstrap?

Answer: We can customize the links by using .disabled for unclickable links and .active for indicating the current page.

Q #25) Explain the input group in Bootstrap.

Answer: Input group in bootstrap is put out from controls. By using an input group, we can easily add prepended and appended text or button to the text-based inputs.

We can prepend and append elements to a .form-control by taking all the elements in a <div> under a class .input-group. After that, place your extra content inside a <span> in same <div> by using class .input-group-addon after this you can place the <span> element either before or after the input element.

Q #26) Write the ways to create a tabbed navigation menu in Bootstrap.

Answer: We can create tabbed navigation by making a basic unordered list with the base class of .nav and after this, we can add class .nav-tabs.

Q #27) In Bootstrap, how can you create a pills navigation menu?

Answer: Pills navigation menu in bootstrap is created by making an unordered list at first with the base class of .nav and after this add the class .nav-pills.

Q #28) How navbar works in Bootstrap?

Answer: In bootstrap, the navbar is an eminent feature to make a responsive meta component that works as navigation headers for your application and site. In the mobile view, the navbar collapses and becomes horizontal as the available viewport width increases.

Q #29) How we can create a navbar in Bootstrap?

Answer: To create a navbar in a bootstrap at first, we have to add the classes .navbar, .navbar-default to the <nav> tag. After this, we have to add the role=” navigation” to the above element, and this will help inaccessibility.

We have added a header class .nav-header to the <div> element, which will include an <a> element with a class navbar brand. From this, we will get a text with a larger size.

Q #30) What is Bootstrap breadcrumb?

Answer: Bootstrap breadcrumb is an efficient way to show hierarchy-based information for a site. This can show the dates of publishing, categories or tags in a blog. They also tell the user about the current page location within a navigational hierarchy.

So we can say that Bootstrap breadcrumb is simply an unordered list with a class of .breadcrumb.

Q #31) What are labels in Bootstrap?

Answer: Bootstrap labels are used for offering counts, tips or other things to provide markup on web pages. To use the label in Bootstrap we use the class .labels to indicate the labels.

Q #32) What are badges in Bootstrap?

Answer: Badges are homogeneous to labels, the main difference between them is corners are more rounded. The main work of badges in the bootstrap is to highlight new or unread items. To use badges just add <span class=”badge”> to links and bootstrap navs.

Q #33) What is a jumbotron in Bootstrap?

Answer: It is used to increase the size of headings and to add a lot of margins for landing page content. To create a jumbotron we have to create a container <div> with the class of .jumbotron.

Q #34) How can we make image responsive in Bootstrap?

Answer: After the updates in Bootstrap, currently the feature to make an image responsive has been added, we can do this by adding a class .img-responsive to the <img> tag. This class makes the width max-width =100%; and height=auto; to the image so that it matches nicely to the parent element.

Q #35) What do you mean by normalize in Bootstrap?

Answer: Bootstrap normalize is a small CSS file that is used to make cross-browser consistency.

Q #36) What is lead body copy in Bootstrap?

Answer: It is used to add some ascent to the paragraph if we add class=”lead”. This will enlarge the font size and taller line-height.

Q #37) What are panels in Bootstrap?

Answer: Panels are components that are used when you want to put your DOM component in a box. So, to retrieve a basic panel we just need to add class.panel to the <div> element. We can also add class.panel-default to this element.

Q #38) How will you create a Bootstrap panel with the heading?

Answer: There are two ways by which we can add panel heading.

First is, we can directly use the .panel-heading class to add heading containers in a panel and the second way is by using any heading tag like <h1> to <h6> with a .panel-title class to give more styles on the heading.

Q #39) What is a scrollspy plugin in Bootstrap?

Answer: It is an auto-updating nav plugin that allows in fetching section of the page based on the scroll position. This can be done by the .active class to the navbar based scroll position.

Q #40) What is the work of the affix plugin in Bootstrap?

Answer: This plugin allows a <div> to be attached to a location on the page.

Use of the social icon in a page is an example for this in which we see that the icons will start in a location, but when the page hits on a certain mark it will block the <div> in place and will stop the scrolling for rest of the page.

Q #41) What is the grid system in Bootstrap?

Answer: By using the grid system, we can make up to 12 columns across a page. There are different classes that have been defined for this for the UI purpose.

Q #42) What are Grid classes in the Bootstrap?

Answer: There are four grid classes in Bootstrap.

They are:

xs (It is used for phone screens less than 786px wide).
sm (It is used for the tablet screens which are greater than 786px wide).
md (It is for small laptop screen of size equal to or greater than 992px wide).
LG ( It is for laptop and desktop screens which are equal to greater than 1200px wide).
Q #43) What are global styles that are used in Bootstrap Default Typography?

Answer: In Bootstrap the global default font-size is 14px and the line height is 1.428. The default font changes to Helvetica and Arial are with sans-serif fallback and all these styles are applicable for both body and all paragraphs.

Q #44) What will be the output of the below code?

<div
class="row">
<div class="col-xs-12 col-md-3">.col-xs-12 .col-md-3</div>
</div>
Answer: The output of this will give the grids for extra small devices as we can see in the snippet col-xs-12 that has been used and it will also give the grids for desktop devices and above as the class col-md-3 has been used.

Q #45) What dependencies does Bootstrap require to work properly?

Answer: jQuery is the only dependency that bootstrap requires for working properly and this is only for JavaScript plugins in bootstrap.

Q #46) Explain what the below code will do?

<a href="#">Home <span class="badge">36</span></a>
Answer: This code will produce a link with an inline badge which will give an important notification to the user like number received, message received or the number of requests, etc.

Q #47) What are the two codes that are used for code display in Bootstrap?

Answer: The codes are <code> tag and <pre> tag.

Q #48) What is the difference between Bootstrap and Foundation?

Answer: Bootstrap uses very fewer preprocessors as it supports less and it allows the designing and development for both mobile and desktop. On the other hand, Foundation supports sass processors and it is used only for mobile UI designing.

Q #49) What are Glyphicons in Bootstrap?

Answer: By this, we can use the icon simply anywhere in your code.

<span class=”glyphicon glyphicon-search”></span>
Q #50) What is a transition plugin in Bootstrap?

Answer: It provides simple transition effects like sliding or fading in modals.

Q #51) Explain the concept of creating a vertical or basic form in Bootstrap.

Answer: For this first we have to add a role form to the parent <form> element then we have to wrap labels and controls in a <div> with class.form-group and then we have to add a class of .form-control to all text url <input>,<textarea> and <select> elements.







What does Bootstrap package includes?
Bootstrap package includes −

Scaffolding − Bootstrap provides a basic structure with Grid System, link styles, background. This is is covered in detail in the section Bootstrap Basic Structure

CSS − Bootstrap comes with feature of global CSS settings, fundamental HTML elements styled and enhanced with extensible classes, and an advanced grid system. This is covered in detail in the section Bootstrap with CSS.

Components − Bootstrap contains over a dozen reusable components built to provide iconography, dropdowns, navigation, alerts, popovers, and much more. This is covered in detail in the section Layout Components.

JavaScript Plugins − Bootstrap contains over a dozen custom jQuery plugins. You can easily include them all, or one by one. This is covered in details in the section Bootstrap Plugins.

Customize − You can customize Bootstrap's components, LESS variables, and jQuery plugins to get your very own version.

What is Contextual classes of table in Bootstrap?
The Contextual classes allow you to change the background color of your table rows or individual cells.

Sr.No.	Class & Description
1	
.active

Applies the hover color to a particular row or cell

2	
.success

Indicates a successful or positive action

3	
.warning

Indicates a warning that might need attention

4	
.danger

Indicates a dangerous or potentially negative action

What is Bootstrap Grid System?
Bootstrap includes a responsive, mobile first fluid grid system that appropriately scales up to 12 columns as the device or viewport size increases. It includes predefined classes for easy layout options, as well as powerful mixins for generating more semantic layouts.

What are Bootstrap media queries?
Media Queries in Bootstrap allow you to move, show and hide content based on viewport size.

Show a basic grid structure in Bootstrap.
Following is basic structure of Bootstrap grid −

<div class = "container">
   <div class = "row">
      <div class = "col-*-*"></div>
      <div class = "col-*-*"></div>      
   </div>
   
   <div class = "row">...</div>
</div>
<div class = "container">....
What are Offset columns?
Offsets are a useful feature for more specialized layouts. They can be used to push columns over for more spacing, for example. The .col-xs = * classes don't support offsets, but they are easily replicated by using an empty cell.

How can you order columns in Bootstrap?
You can easily change the order of built-in grid columns with .col-md-push-* and .col-md-pull-* modifier classes where * range from 1 to 11.

How do you make images responsive?
Bootstrap 3 allows to make the images responsive by adding a class .img-responsive to the <img> tag. This class applies max-width: 100%; and height: auto; to the image so that it scales nicely to the parent element.

Explain the typography and links in Bootstrap.
Bootstrap sets a basic global display (background), typography, and link styles −

Basic Global display − Sets background-color: #fff; on the <body> element.

Typography − Uses the @font-family-base, @font-size-base, and @line-height-base attributes as the typographic base

Link styles − Sets the global link color via attribute @link-color and apply link underlines only on :hover.

What is Normalize in Bootstrap?
Bootstrap uses Normalize to establish cross browser consistency.

Normalize.css is a modern, HTML5-ready alternative to CSS resets. It is a small CSS file that provides better cross-browser consistency in the default styling of HTML elements.

What is Lead Body Copy
To add some emphasis to a paragraph, add class = "lead". This will give you larger font size, lighter weight, and a taller line height

Explain types of lists supported by Bootstrap.
Bootstrap supports ordered lists, unordered lists, and definition lists.

Ordered lists − An ordered list is a list that falls in some sort of sequential order and is prefaced by numbers.

Unordered lists − An unordered list is a list that doesn't have any particular order and is traditionally styled with bullets. If you do not want the bullets to appear then you can remove the styling by using the class .list-unstyled. You can also place all list items on a single line using the class .list-inline.

Definition lists − In this type of list, each list item can consist of both the <dt> and the <dd> elements. <dt> stands for definition term, and like a dictionary, this is the term (or phrase) that is being defined. Subsequently, the <dd> is the definition of the <dt>.

You can make terms and descriptions in <dl> line up side-by-side using class dl-horizontal.
What are glyphicons?
Glyphicons are icon fonts which you can use in your web projects. Glyphicons Halflings are not free and require licensing, however their creator has made them available for Bootstrap projects free of cost.

How do you use Glyphicons?
To use the icons, simply use the following code just about anywhere in your code. Leave a space between the icon and text for proper padding.

<span class = "glyphicon glyphicon-search"></span>
What is a transition plugin?
The transition plugin provides simple transition effects such as Sliding or fading in modals.

What is a Modal Plugin?
A modal is a child window that is layered over its parent window. Typically, the purpose is to display content from a separate source that can have some interaction without leaving the parent window. Child windows can provide information, interaction, or more.

How do you use the Dropdown plugin?
You can toggle the dropdown plugin's hidden content −

Via data attributes − Add data-toggle = "dropdown" to a link or button to toggle a dropdown as shown below −

<div class = "dropdown">
   <a data-toggle = "dropdown" href = "#">Dropdown trigger</a>
   <ul class = "dropdown-menu" role = "menu" aria-labelledby = "dLabel">
    ...
   </ul>
</div>
If you need to keep links intact (which is useful if the browser is not enabling JavaScript), use the data-target attribute instead of href="#" −

<div class = "dropdown">
   <a id = "dLabel" role = "button" data-toggle = "dropdown" data-target = "#" href = "/page.html">
      Dropdown 
    
      <span class = "caret"></span>
   </a>
    
   <ul class = "dropdown-menu" role = "menu" aria-labelledby = "dLabel">
      ...
   </ul>
	
</div>
Via JavaScript − To call the dropdown toggle via JavaScript, use the following method −

$('.dropdown-toggle').dropdown()
What is Bootstrap caraousel?
The Bootstrap carousel is a flexible, responsive way to add a slider to your site. In addition to being responsive, the content is flexible enough to allow images, iframes, videos, or just about any type of content that you might want.

What is button group
Button groups allow multiple buttons to be stacked together on a single line. This is useful when you want to place items like alignment buttons together.

Which class is used for basic button group
.btn-group class is used for a basic button group. Wrap a series of buttons with class .btn in .btn-group.

Which class is used to draw a toolbar of buttons
.btn-toolbar helps to combine sets of <div class = "btn-group"> into a <div class = "btn-toolbar"> for more complex components.

Which classes can be applied to button group instead of resizing each button
.btn-group-lg, .btn-group-sm, .btn-group-xs classes can be applied to button group instead of resizing each button.

Which class make a set of buttons appear vertically stacked rather than horizontally
.btn-group-vertical class make a set of buttons appear vertically stacked rather than horizontally.

What are input groups
Input groups are extended Form Controls. Using input groups you can easily prepend and append text or buttons to the text-based inputs.

By adding prepended and appended content to an input field, you can add common elements to the user's input. For example, you can add the dollar symbol, the @ for a Twitter username, or anything else that might be common for your application interface.

To prepend or append elements to a .form-control −

Wrap it in a <div> with class .input-group

As a next step, within that same <div> , place your extra content inside a <span> with class .input-group-addon.

Now place this <span> either before or after the <input> element.

How will you create a tabbed navigation menu
To create a tabbed navigation menu −

Start with a basic unordered list with the base class of .nav.
Add class .nav-tabs.
How will you create a pills navigation menu
To create a pills navigation menu −

Start with a basic unordered list with the base class of .nav.
Add class .nav-pills.
How will you create a vertical pills navigation menu
You can stack the pills vertically using the class .nav-stacked along with the classes: .nav, .nav-pills.

What is bootstrap navbar
The navbar is one of the prominent features of Bootstrap sites. Navbars are responsive 'meta' components that serve as navigation headers for your application or site. Navbars collapse in mobile views and become horizontal as the available viewport width increases. At its core, the navbar includes styling for site names and basic navigation.

How to create a navbar in bootstrap
To create a default navbar −

Add the classes .navbar, .navbar-default to the <nav> tag.

Add role = "navigation" to the above element, to help with accessibility.

Add a header class .navbar-header to the <div> element. Include an <a> element with class navbar-brand. This will give the text a slightly larger size.

To add links to the navbar, simply add an unordered list with the classes of .nav, .navbar-nav.

What is bootstrap breadcrumb
Breadcrumbs are a great way to show hierarchy-based information for a site. In the case of blogs, breadcrumbs can show the dates of publishing, categories, or tags. They indicate the current page's location within a navigational hierarchy.

A breadcrumb in Bootstrap is simply an unordered list with a class of .breadcrumb. The separator is automatically added by CSS (bootstrap.min.css).

Which class is used for basic pagination
.pagination class is uesed to add the pagination on a page.

How will you customize links of pagination
You can customize links by using .disabled for unclickable links and .active to indicate the current page.

What are bootstrap labels
Bootstrap labels are great for offering counts, tips, or other markup for pages. Use class .label to display labels.

What are bootstrap badges
Badges are similar to labels; the primary difference is that the corners are more rounded. Badges are mainly used to highlight new or unread items. To use badges just add <span class = "badge"> to links, Bootstrap navs, and more.

What is Bootstrap Jumbotron
As the name suggest this component can optionally increase the size of headings and add a lot of margin for landing page content. To use the Jumbotron −

Create a container <div> with the class of .jumbotron.
In addition to a larger <h1>, the font-weight is reduced to 200px.
What is Bootstrap page header
The page header is a nice little feature to add appropriate spacing around the headings on a page. This is particularly helpful on a web page where you may have several post titles and need a way to add distinction to each of them. To use a page header, wrap your heading in a <div> with a class of .page-header.

How to create thumbnails using Bootstrap
To create thumbnails using Bootstrap −

Add an <a> tag with the class of .thumbnail around an image.
This adds four pixels of padding and a gray border.
On hover, an animated glow outlines the image.
How to customize thumbnails using Bootstrap
it's possible to add any kind of HTML content like headings, paragraphs, or buttons into thumbnails. Follow the steps below −

Change the <a> tag that has a class of .thumbnail to a <div>.

Inside of that <div>, you can add anything you need. As this is a <div>, we can use the default span-based naming convention for sizing.

If you want to group multiple images, place them in an unordered list, and each list item will be floated to the left.

What are bootstrap alerts?
Bootstrap Alerts provide a way to style messages to the user. They provide contextual feedback messages for typical user actions.

You can add an optional close icon to alert.

How will you create a bootstrap alert?
You can add a basic alert by creating a wrapper <div> and adding a class of .alert and one of the four contextual classes (e.g., .alert-success, .alert-info, .alert-warning, .alert-danger).

How will you create a Bootstrap Dismissal Alert?
To build a dismissal alert −

Add a basic alert by creating a wrapper <div> and adding a class of .alert and one of the four contextual classes (e.g., .alert-success, .alert-info, .alert-warning, .alert-danger).

Also add optional .alert-dismissable to the above <div> class.

Add a close button.

Use the <button> element with the data-dismiss = "alert" data attribute.

How will you create a progress bar using bootstrap?
To create a basic progress bar −

Add a <div> with a class of .progress.

Next, inside the above <div>, add an empty <div> with a class of .progress-bar.

Add a style attribute with the width expressed as a percentage. Say for example, style = "60%"; indicates that the progress bar was at 60%.

How will you create a alternate progress bar using bootstrap?
To create a progress bar with different styles −

Add a <div> with a class of .progress.

Next, inside the above <div>, add an empty <div> with a class of .progress-bar and class progress-bar-* where * could be success, info, warning, danger.

Add a style attribute with the width expressed as a percentage. Say for example, style = "60%"; indicates that the progress bar was at 60%.

How will you create a striped progress bar using bootstrap
To create a striped progress bar −

Add a <div> with a class of .progress and .progress-striped.

Next, inside the above <div>, add an empty <div> with a class of .progress-bar and class progress-bar-* where * could be success, info, warning, danger.

Add a style attribute with the width expressed as a percentage. Say for example, style = "60%"; indicates that the progress bar was at 60%.

How will you create a animated progress bar using bootstrap?
To create an animated progress bar −

Add a <div> with a class of .progress and .progress-striped. Also add class .active to .progress-striped.

Next, inside the above <div>, add an empty <div> with a class of .progress-bar.

Add a style attribute with the width expressed as a percentage. Say for example, style = "60%"; indicates that the progress bar was at 60%.

How will you create a stacked progress bar using bootstrap
You can even stack multiple progress bars. Place the multiple progress bars into the same .progress to stack them.

What are bootstrap media objects
These are abstract object styles for building various types of components (like blog comments, Tweets, etc.) that feature a left-aligned or right-aligned image alongside the textual content. The goal of the media object is to make the code for developing these blocks of information drastically shorter.

The goal of media objects (light markup, easy extendability) is achieved by applying classes to some of the simple markup.

What is the purpose of .media class in bootstrap?
This class allows to float a media object (images, video, and audio) to the left or right of a content block.

What is the purpose of .media-list class in bootstrap
If you are preparing a list where the items will be part of an unordered list, use a class. useful for comment threads or articles lists.

What are bootstrap panels
Panel components are used when you want to put your DOM component in a box. To get a basic panel, just add class .panel to the <div> element. Also add class .panel-default to this element.

How will you create a bootstrap panel with heading
here are two ways to add panel heading −

Use .panel-heading class to easily add a heading container to your panel.

Use any <h1>-<h6> with a .panel-title class to add a pre-styled heading.

How will you create a bootstrap panel with footer

You can add footers to panels, by wrapping buttons or secondary text in a <div> containing class .panel-footer.

What contextual classes are available to style the panels

Use contextual state classes such as, panel-primary, panel-success, panel-info, panel-warning, panel-danger, to make a panel more meaningful to a particular context.

Can you put a table within bootstrap panel

Yes! To get a non-bordered table within a panel, use the class .table within the panel. Suppose there is a <div> containing .panel-body, we add an extra border to the top of the table for separation. If there is no <div> containing .panel-body, then the component moves from panel header to table without interruption.

Can you put a listgroup within bootstrap panel

Yes! You can include list groups within any panel. Create a panel by adding class .panel to the <div> element. Also add class .panel-default to this element. Now within this panel include your list groups.

What is bootstrap well

A well is a container in <div> that causes the content to appear sunken or an inset effect on the page. To create a well, simply wrap the content that you would like to appear in the well with a <div> containing the class of .well.

What is Scrollspy plugin

The Scrollspy (auto updating nav) plugin allows you to target sections of the page based on the scroll position. In its basic implementation, as you scroll, you can add .active classes to the navbar based on the scroll position.

What is affix plugin

The affix plugin allows a <div> to become affixed to a location on the page. You can also toggle it's pinning on and off using this plugin. A common example of this are social icons. They will start in a location, but as the page hits a certain mark, the <div> will be locked in place and will stop scrolling with the rest of the page.





1) Explain what is Bootstrap?

Bootstrap is a HTML, CSS, and JS framework for building the rich web applications with minimal effort. This framework emphasis more on building mobile web applications.

2) Explain why to choose Bootstrap for building the websites?

There are few reason why we choose Bootstrap for building websites

Mobile Support: For mobile devices it provides full support in one single file rather than in separate file. It supports the responsive design including adjusting the CSS based on the different types of device, size of the screen etc. It reduces extra effort for developers.
Easy to learn: Writing application in bootstrap is easy if you know CSS and HTML
Browser Support: It supports all the popular browsers like Firefox, Opera, Safari, IE etc.
3) What are the key components of Bootstrap?

The key components of Bootstrap are

CSS : It comes with plenty of CSS files
Scaffolding : It provides a basic structure with Grid system , link styles and background
Layout Components : List of layout components
JavaScript Plugins: It contains many jQuery and JavaScript plugins
Customize: To get your own version of framework you can customize your components
4) Explain what are class loaders in Bootstrap?

Class loader is a part of JRE (Java Runtime Environment) which loads Java classes into Java virtual environment. Class loaders also does the process of converting a named class into its equivalent binary form.

5) What are the types of layout available in Bootstrap?

In Bootstrap there are two types of Layout available

Fluid Layout: Fluid layout is used when you want to create a app that is 100% wide and use up all the width of the screen
Fixed Layout: For a standard screen you will use fixed layout (940 px) option

6) Explain what is Bootstrap Grid System?
For creating page layout through a series of rows and columns that house your content Bootstrap Grid Sytem is used.

7) What are offset columns in Bootstrap?

For more specialized layouts offsets are a useful feature. For more spacing they can be used by pushing column over.

For example, .col-xs=* classes do not support offset but they are easily replicated using an empty cell

8) What is column ordering in Bootstrap?

Column ordering is one of the feature available in bootstrap and you can easily write columns in an order and show them in another one. With .col-md-push-* and .col-md-pull-*

the order of the column can be easily changed.

9) What function you can use to wrap a page content?

To wrap a page content you can use .container and using that you can also center the content.

10) Explain what pagination in bootstrap is and how they are classified?

Pagination is the handling of an unordered list by bootstrap. To handle pagination bootstrap provides following classes

.pagination: To get pagination on your page you have to add this class
.disabled, .active: Customize links by .disabled for unclickable links and .active to indicate the current page
.pagination-Ig, .pagination-sm: Use these classes to get different size item
 

11) What is the use of Jumbotron in Bootstrap?

In bootstrap, Jumbotron is generally used for content that you want to highlight like some slogan or marketing headline etc. in other words it is used to enlarge the size of the headings and to add a margin for landing page content

To use the Jumbotron in Bootstrap

Create a container <div> with the class of .jumbotron

12) What is the difference between Bootstrap and Foundation?

Bootstrap	
– Bootstrap offers unlimited number of UI elements	
– Bootstraps uses pixels	
– Bootstrap encourages to design for both desktop and mobile.
– Bootstrap support LESS as its preprocessor	
Foundation
– In Foundation UI element options are very limited in numbers
– Foundation use REMs
	– Foundation encourages to design mobile first
  – Foundation support Sass and Compass as its preprocessor

  
13) In Bootstrap what are the two ways you can display the code?

In bootstrap you can display code in two ways

<code> tag : If you are going to display code inline, you should use <code> tag
<pre> tag: If you want to display the code as a standalone block element or it has multiple lines then you should use <pre> tag
14) Explain what are the steps for creating basic or vertical forms?

The steps for creating basic or vertical forms are

Add a role form to the parent <form> element
Wrap labels and controls in a <div> with class .form-group. To achieve optimum spacing this is needed
Add a class of .form-control to all texturl <input> , <textarea> , and <select> elements
15) Explain what is Modal plugin used for in Bootstrap?

A modal is a child window that is layered over its parent window. Using a custom Jquery Plugin, Bootstrap Modal are created. To enrich user experience and to add functionality to users, modal windows are created with the help of Modal plugin.

16) Explain what is Bootstrap Container?

Bootstrap container is a class which is useful and creates a centred area within the page where our site content can be put within. The advantage of the bootstrap .container is that it is responsive and will place all our other HTML code.

17) Explain what is Bootstrap collapsing elements?

Bootstrap collapsing elements enables you to collapse any particular element without writing any JavaScript code or the accordion markup. In Bootstrap to apply collapsing elements you have to add data-toggle= “collapse” to the controller element along with a data-target or href to automatically assign control of a collapsible element. Likewise, you can use .collapse (options), .collapse (‘show’) or .collapse (‘hide’)

18) Explain what is list group in Bootstrap and what is the use of it?

List groups are components to display both simple and complex element with custom content

For example, a simple list group is created using class .list-group to address the list, and class .list-group-item to address individual item.

19) How you can add badge to list group in Bootstrap?

To add badge to list group in Bootstrap you have to simply add <span class = “badge”> within the <li> element.

20) Explain what media object in Bootstrap is and what are their types?

Media objects in Bootstrap enables to put media object like image, video or audio to the left or right of the content blocks. Media element can be created using the class .media and the source is specified in using the class .media-object. Media-objects are of two types,

They are of two types

.media
.media-list
21) Explain what is Bootstrap well?

Bootstrap well is a container <div> that makes the content to appear sunken or an inset effect on the page. In order to create a well, wrap the content that you would like to appear in the well with a <div> containing the class of .well.

 

22) Explain how you can create Nav elements in Bootstrap?

Bootstrap offers various options for styling navigation elements all of them use the same markup and base class .nav.

To create Tabular Navigation or Tabs

Start with a basic unordered list with the base class of .nav
Then add class .nav-tabs
23) Explain what is the use of Bootstrap Carousel plugin?

The Carousel plugin is used to add a slider to your site. It is useful in condition where you want to display huge amount of contents within a small space on the web pages. Some of the standard carousel includes

.carousel (options)
.carousel (‘cycle’)
.carousel (‘pause’)
.carousel (‘number’)
.carousel (‘prev’)
.carousel (‘next’)




Ref 
:  https://career.guru99.com/top-25-bootstrap-interview-questions/

https://www.softwaretestinghelp.com/bootstrap-interview-questions/
https://www.tutorialspoint.com/bootstrap/bootstrap_interview_questions.htm
https://www.bestinterviewquestion.com/bootstrap-4-interview-questions
