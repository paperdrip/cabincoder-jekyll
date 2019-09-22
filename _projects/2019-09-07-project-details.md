---
title: 'Cabin Coder'
subtitle: 'An experiment on the plane'
date: 2019-09-07 06:00:00
featured_image: '/images/cabin-square.jpg'
excerpt: What am I able to do with my iPad and the in plane WiFi over a 10 hours flight? This page shows everything about the experiment I am doing in the cabin, from my intention to the project details and the result.
---

![](/images/waiting-to-takeoff.jpg)

## Introduction
I enjoy the feeling of being able to do geeky stuff at remote location - be it on the mountain after a hike, a small table on the train or in a cabin on the sky!

The feeling of constraint by the machines or the bandwidth available makes the experience even more interesting, in a condition that I could get my work done! 

So, here I am, in the cabin up on the sky, preparing this little experiment of building a blog and writing several entry through the 10+ hours. 

## Experiment
Come to think about the criteria, better said what I am able to do. Something I am able to develop on my iPad (don't want to rely on remote development, first is about the cost and secondly want to test out what's the limit of local development) and latency for sure. 

Regarding to the topic, what would be interesting in this 10 hours are the happening over this period of time? Blogging sounds like a good idea as I can capture this journey and all the things happened in this 10 hours. Besides, maybe I can build a blogging workflow, together with the blog entry which seems to be an achievable thing - not too technical but complex enough to try out the limitation.

There are two options I am considering,
- Using  Pythonista and install a framework as a base to finish my workflow
- Building a static website using Ghost / Jekyll

The static website feels more interesting to me and this set the stage of the experiment.

> "Constraint sets a boundary but it is also a fuel on creativity. We have to think and thinking it hard to get around, or even over, the constraint in achieving our goal."

### Provision a server in the sky, NOT
Originally, I would envision myself setting up a workflow in iOS to provision a new server through Digital Ocean and then automate the setting up of the environment with Ansible script or Dockerfile. But I ended up going back to Netlify.com, leveraging their free hosting for this project.

The free plan is good enough for this experiment, and it already comes with,
- SSL certificate through Letsencrypt
- Load balanced DNS through the NS1 infrastructure, another company that I enjoy using for both the performance and feature (site monitoring and notification in particular).
- Integration with GitHub which ease my publication and modification workflow
- Deploy globally with CDN acceleration

And since I have already registered my own website (https://ronniek.me) in Netlify.com and thus, I can just add a new site and point it to my GitHub repo.

### Domain Creation
I could stay with a domain provided by Netlify.com but having a custom domain would make it more complete. And "Freenom" (stand for Free Name) offers free domain ended with TLD as ".tk" for up to 12 months of usage. It's more than enough for me.

So the naming process begins. Someone coding in the cabin so it's natural to use "cabin-coder" as the domain. Signing up a domain in Freenom.com is also straight forward, sign up an account, pick the name and also the duration then ta-da, all set. Since I am using the name server of Netlify, I need to update the entry in Freenom.com as well. 

All set for the domain creation.

### Finding a theme and setting up the repository
Paid theme on Jekyll Themes is nice (https://simples.jekyllthemes.io) but shelling out $49 for an experiment is a bit too much so I am picking a free theme which seems to work for this experiment.

Update : The more I look at it, the more I like the "Simples" theme. So yes, I shelled out the money, download the zip and save it to File. Next, I need to add "Working Copy" as a Locations to access within File. From there, I can then copy the themes to the repository created and start working!



