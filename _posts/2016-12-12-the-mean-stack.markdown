---
layout: post
title:  "Getting started with the MEAN stack"
date:   2016-12-12 09:23:59
author: Chris Merrick
categories: MEAN Stack
tags: mean_stack
cover:  "/assets/mean-stack-2-638.jpg"
---

# Getting Started
The MEAN stack is a technology stack composed of four main parts. The "M" stands for Mongo Database, the "E" stands for Express which is a web framework that sits on top of Nodejs. The "A" stands for Angular which is a front end framework used to show dynamic pages. The "N" stands for Nodejs which is javascript that can run in the terminal with a few extras that regular javascript doesn't have like file processing and the ability to send and receive http requests. Together these four technologies make a rapid development prototyping environment where a developer can implement a simple version of an application in a day or less in some cases.

# My Project
So the first project that I undertook using the MEAN stack was a simple task list manager that had create, read, update, and delete database capabilities. It may have been simple and it certainly wasn't the coolest thing I could have made but it was a great choice for someone that just wants to understand the technology stack. The next project I am going to build using this stack is going to be a voting or customer feedback app of some sort where users can suggest topics and then vote on them.

# The Next Project
So I decided to build a customer feedback web application where you can drop a hyperlink in a post and have your readers give you feedback or vote on something and you get the results in real time. This "Polling App" as I will refer to it for now is ideal for the Mean stack because Mongo database can handle the high amount of traffic that might be generated if many people are logging their vote at the same time and it can process it very quickly. One down side of Mongo is that some pieces of data can be lost due to a sacrifice it makes to achieve these extremely high speeds. This data persistence problem is not a deal breaker altogether though, you simply need to know what use cases Mongo is suited for and which ones it isn't. For example, it would be unwise to use it for a financial transaction system only to have problems where transactions just seem to disappear. Do not put yourself in this type of position and always choose your technology wisely.

# In Conclusion
I really am finding the MEAN stack to be an awesome full web stack. It is a pleasure to develop in and it continues to be built upon and improved. Also having many big companies like Google backing parts of the technology and there are other big companies getting involved as well so it seems that the mean stack will be here for awhile, I recommend you give it a look, you might like what you see.
