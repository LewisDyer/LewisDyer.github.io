---
title: Projects
permalink: /projects/
---

This page details a few projects I've worked on.

# Modelling and Analysing Stochastic Games

## Level 4 Individual Project, supervised by Dr. Gethin Norman

My dissertation is focused on a field called model checking, which concerns itself with formally modelling systems (for instance, via extended finite state machines), and formally verifying these systems for certain properties. This is especially useful for domains such as safety-critical systems, where errors may be rare enough that conventional simulation techniques may give misleading results, but where regulatory bodies often seek guarantees on the reliability or performance of a system.

Specifically, my dissertation is focused on dice-based stochastic games. Many boardgames and videogames involve dice as a central mechanic, since they're a common, universal way to include random elements in a game. The aim of my dissertation is to consider various dice-based games, develop probabilistic models of each game using the PRISM model checker, and analyse various properties of each game in order to evaluate the design of each game (for instance, to determine if various dominant strategies exist, or whether some game mechanics are too strong or too weak), along with considering the impact of different modifications to the game (for instance, via the use of biased dice).


Details of the project are not currently available, since it's a piece of ongoing coursework. However, when the project has concluded, I'll include a link to the GitHub repo including the dissertation and source code, and I also plan to make a few blog posts about it as well.

# Lippy - PyTorch-based lipreading system

## Level 3 Team Project in conjunction with Bedia

As part of my 3rd year team project, I worked as part of a group of 5 to develop Lippy, a lipreading system built using PyTorch, in conjunction with Bedia, a Glasgow-based startup focused on automated transcription. Bedia work with a number of clients, such as the Scottish Parliament, and we developed a system which would allow them to batch process archival footage from the Scottish Parliament to determine what people are saying without sound (for instance, where the original audio is lost or corrupted).

This project involved a lot of background research, since lipreading is an active area of research and our team had little to no previous experience with machine learning. In particular, my main role in the project was to develop a batch processing system, where YouTube videos could be automatically clipped and separated into distinct words, using the speaker's lips, which could be processed by the machine learning system.

A public version of the project is available on [GitHub](https://github.com/bedia-tv/lippy/). This project also received the Combined Honours Project Prize in the School of Computing Science.

# PackingCircles

## Generative art based on circle packing with PyCairo

Generative art is the process of algorithmically generating art using a predefined system, such as a computer program. These programs normally include some use of random elements, such as the position or colour of shapes.

This project is based on circle packing, where circles are packed into a defined space to fill as many gaps as possible. My project extends on this idea, providing different shapes, palettes and the use of layers to generate interesting images, such as the one shown below. The system also includes a layer and shape specification system, so that creating new images and tweaking parameters is relatively easy.

This project is publically available on [GitHub](https://github.com/bedia-tv/lippy/).

![Example output of circle packing](/assets/packingcircles.png)

# Messenger Visualisation

## Visualising group chats on Facebook Messenger using NetworkX and PyViz

This project takes in a folder containing information from a Messenger chat (which can be downloaded directly from Facebook), and outputs an interactive graph showing various properties of the chat, such as the most engaged people in the chat, or especially popular images. This is especially interesting for chats with a large number of people, since you can identify cliques who tend to interact between each other.

This project is publically available on [GitHub](https://github.com/LewisDyer/messengervisualisation). An image of the sorts of graphs the program generates will be available soon, once the graphs can be sufficiently anonymised.

# SettleMySettle

## Django-based website for Web Application Development 2

I worked with a team of 4 students to develop SettleMySettle, a website for discussing various strategy games. This website was built in Django, and includes user authentication, use of the Steam API for providing more information about games, and a number of other features. In particular, my main responsibility was building the website's tagging system, which allows users to add tags to their posts to represent games they're playing, favourite tags to see a personalised feed of games they enjoy, and suggest tags which administrators can edit and include on the site.

This website is publically available on [PythonAnywhere](http://settlemysettle.pythonanywhere.com/settle/), and the source code of the website is available on [GitHub](https://github.com/settlemysettle/SettleMySettle). (Note that the PythonAnywhere site requires regular reauthorisation to remain operational. I should keep on top of this, but if you try and access the site and it isn't available, feel free to get in contact and I'll be happy to rehost it).