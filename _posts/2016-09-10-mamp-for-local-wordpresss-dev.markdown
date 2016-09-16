---
layout: post
title:  "Using Mamp for Local WordPress Development"
date:   2016-09-10 08:43:59
author: Chris Merrick
categories: Development
tags: development
cover:  "/assets/railroad.png"
---


I recently decided to test out the X-theme wordpress theme the and I wanted to use it locally, meaning on my computer instead of editing a live site. This is a good way to go because it's free and it's a quicker, faster environment to develop with than a live site online. Being that I use a Mac for development, I downloaded Mamp. This is a program that let's you serve up files to your localhost. Mamp is an acronym for Mac Osx, the database management system MySQL, the web server Apache, and PHP, Perl, or Python. Having downloaded Mamp can then launch your server with the click of a button which then hosts the files in your /Applictions/MAMP/htdocs folder onto the localhost.

Then the next step is to download Wordpress.org software and placing it into the folder you want to use it in. Downloading WordPress is actually a very streamlined process that let's you set up a account in about 2 minutes. Once you do this and you go to the correct directory in your path you can start experimenting with wordpress and getting to know how it works. You can install some pretty cool free themes and experiment with different formats but when I attempted to use the premium WordPresss theme I ran into a an error message. After some extensive searching I found the root of the problem, it was that the file size of the premium theme was bigger than the PHP configuration had allowed. I had to go into the file php.ini and edit the upload_max_filesize and my post_max_size both to 100M.

When I ran the theme again there was another error but this was different so at least I had solved the problem of getting the theme's memory allowed in. This turned out to be a simple fix though as I put the theme file in the wrong directory. I had added the entire downloaded folder instead of taking out the correct one. Once I corrected this I had a fast and free development environmrent to develop a website using the truly amzing X-theme.