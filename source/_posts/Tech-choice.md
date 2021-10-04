---
title: Tech-choice
date: 2021-10-02 08:59:36
tags:
---

The choices of technology available for Divvynotes to use are truly endless. 

# 1. Platform availability

As we have already discussed before, we will be focusing on the web version as the main front-end graphic user interface. This is more versatile, easier to handle, and universal. 

The programming skills associated with making a web interface is easily acquired (through vast resources already available online), and any device with a browser can access a website (though there may need to be minor adjustments). 

Furthermore, hybrid applications can be used on mobile devices, so we do not need to waste time trying to adapt our app into specific mobile devices. All we need is a some hybrid framework that can allow an app on its own to access our website without the use of an external browser. This is simple and can save us potentially lots time.

# 2. Computing

We can either host the needed computational resources locally, or through the cloud.

It is obvious that it is in our long-term interests to use a scalable cloud-based computing service, but to start, it is not ridiculous to host the serer for Divvynotes on a local device.

However, the only advantage of a local device is that running it is essentially free. Its consequences include security threats, lack of resources and scalability, and stability. Operating dedicated local machines is simply infeasible if we intend to grow our business as a startup.

There are many cloud-based options that are suitable for scalable purposes, including Google Cloud, Microsoft Azure, and Amazon Web Services, that cover all of the problems aforementioned. It is even more cost-effective once we reach a certain threshold. 

Thus, perhaps we could run the Divvynotes server on someone's desktop computer to start with, but it is **definitely** integral for us to move our server into the cloud if we intend to grow.

# 3. Development

I am not quite that familiar with actual doing things with cloud computing, nor do I have experience with create a server program that manages I/O from scratch, but I have a rough general idea of how we should develop.

On the front-end, as we are creating a web interface as the primary method of interacting between clients and the server, we will almost 100% be using HTML, CSS, and JavaScript. I have no experience with creating a dynamic site, so perhaps there may be some additional tools we may have to use on the front-end.

On the back-end however, the possibilities extend quite far. Again, I don't have real experience working with cloud-based computing, but I think we should use Java as our main language, in addition to using any additional tools like SQL maybe to assist with managing databases.

An interesting thing to note is that if we would like to have the Divvynotes suggest user-specific content, we may need to create an AI from scratch, which would most likely mean the usage of Python? I emphasize again that this is mostly just me thinking from intuition, in addition to this being a goal that will be far in the future.
