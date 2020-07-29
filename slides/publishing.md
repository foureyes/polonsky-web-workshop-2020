---
layout: slides
title: "Publishing on the Web"
---

<section markdown="block" class="intro-slide">
# {{ page.title }}

### {{ site.vars.course_number}} {{ site.vars.course_name }}

<p><small></small></p>
</section>

<section markdown="block">
## Publishing on the Web Topics

We'll talk about three different ways to publish your content on the web:

1. {:.fragment} As a __static site__
2. {:.fragment} Through a __Content Management System__ (CMS) or _web publishing platform_
3. {:.fragment} Using speciality services

</section>
<section markdown="block">
## Overview


To make your content available on the web...

* {:.fragment} You'll need to put that content on a computer (a _server_) that can _talk HTTP_
* {:.fragment} Usually, this means a computer running specialized software for serving web content (this software is called a __web server__ or an __HTTP server__)
* {:.fragment} Also:
	* {:.fragment} (the computer should also be on the internet)
	* {:.fragment} (you may want a domain name)

</section>


<section markdown="block">
## Your Computer or Someone Else's

__That computer may be your own or someone else's computer!__ &rarr;

* {:.fragment} __Self hosted__ or __on premise__ 🏠...
	* {:.fragment} implies that the content is served on from a server that you _own_  from a location that you own or rent (or even a share of a server's resources) 
	* {:.fragment} in addition to maintaining the content, you also maintain the server software (and possibly the server itself)
* {:.fragment} __Hosted__ or __cloud__ ☁️...
	* {:.fragment} implies that the content is served from _someone else's_ server
	* {:.fragment} you are only responsible for the content, not the server or server software
</section>

<section markdown="block">
## A hosted / cloud option is usually the best choice! (why 🤷?)
{:.question}
</section>

<section markdown="block">
## Uploading Files Example

__Let's see what "using someone else's computer" to host web content (as simple HTML files) may look like__ 👀⬆️ &rarr;

* {:.fragment} __demo__: uploading files via ftp / sftp to a remote server
	* {:.fragment} (for example, hosting provided by your school)
* {:.fragment} __demo__: using a service that provides _static_ file hosting
	* {:.fragment} (for example, GitHub Pages) 

</section>


<section markdown="block">
## Static Sites

The previous demonstrations were examples of __static sites__. &rarr;

* {:.fragment} the content delivered to the user is the same as the file stored on the server
* {:.fragment} these files are usually HTML, CSS, JavaScript and images
* {:.fragment} this implies that content _does not change_ (it's _likely_ the same content regardless of context - such as user, time, etc.) 

</section>

<section markdown="block">
## What are some examples of sites that are likely NOT static? Why do you think they're not static?
{:.question}
</section>

<section markdown="block">
## Dynamic / Database Driven

Sites where content is generated on the fly (based on user, data, time, etc.) are called __dynamic sites__. &rarr;

* {:.fragment} these sites assemble and generate HTML as needed
* {:.fragment} typically, content is drawn from a database and injected into an HTML template
* {:.fragment} consequently, your content is no longer file based...
* {:.fragment} instead, you need some method of inserting and editing your content in a database

</section>

<section markdown="block">
## Wait, How❓

__A database driven website delivers content by__ &rarr;

1. {:.fragment} accepting a request from a browser
2. {:.fragment} reading or modifying data from a database
3. {:.fragment} using that data to create HTML markup and content
4. {:.fragment} sending back the resulting document

</section>

<section markdown="block">
## How do we get data into the database? Are we writing SQL now?
{:.question}

</section>
<section markdown="block">
## Content Management Systems

__Rather than dealing with flat HTML files, Content Management Systems provide a graphical user interface to administering your site and its content__ &rarr;

* {:.fragment} Many Content Management Systems cater to a specific kind of content
* {:.fragment} For example, [Omeka](https://omeka.org/) is set up specifically for collections management
* {:.fragment} But some Content Management Systems have facilities for more generic content
* {:.fragment} For example, [WordPress](https://wordpress.org/) was originally a blogging platform (a post is the primary building block), but its features allow for any kind of web content

</section>

<section markdown="block">
## Additional Features

__Content Management Systems may also provide the following features__ &rarr;

* {:.fragment} __plugin__ system
* {:.fragment} __data model__ extensibility
* {:.fragment} themes
* {:.fragment} __WYSIWG editor__
* {:.fragment} administrative __user management__
</section>

<section markdown="block">
## Other Factors

__When choosing a CMS, you may also consider some non-techical attributes, suchs as__ &rarr;

* {:.fragment} ease-of-use
* {:.fragment} community / userbase
* {:.fragment} development activity
* {:.fragment} documentation

</section>

<section markdown="block">
## What are some Content Management Systems that you've heard of?
{:.question}

</section>

<section markdown="block">
## Popular Content Management Systems

* [WordPress](https://wordpress.org/) - blogging, but a lot more!
* [Omeka](https://omeka.org/) - digital collections; plugin system allows for mapping
* [Squarespace](https://www.squarespace.com/), [Wix](https://www.wix.com/), [Weebly](https://www.weebly.com/) - all generic website builders for creating an _online presence_
* [Joomla](https://www.joomla.org/) and [Drupal](https://www.drupal.org/) - generic CMS
</section>

<section markdown="block">
## What are some advantages and disadvantages of static sites and dynamic sites (such as one used by a CMS)?
{:.question}
</section>

<section markdown="block">
## Specialized Services

__Of course, publishing on the web doesn't mean you need a _whole_ website.__

If you're looking to quickly put up some data analysis or mapping research online, you can use specialized services. For example...

* {:.fragment} [StoryMaps](https://storymaps.arcgis.com/)
* {:.fragment} [AirTable](https://airtable.com/)
* {:.fragment} Online Counterpart of Desktop Tools ([Tableau Online](https://www.tableau.com/products/cloud-bi), [ArcGIS Online](https://www.esri.com/en-us/arcgis/products/arcgis-online/overview))
</section>

<section markdown="block">
## Before we put stuff online, though, [we should... ](project-planning.html)
{:.question} 

</section>
