---
layout: post
title: "Shipyard: UI Refresh"
description: ""
category: applications
tags: ["shipyard", "docker"]
---
{% include JB/setup %}

[Shipyard](https://github.com/ehazlett/shipyard) just received a significant user
interface "refresh".  Behind the scenes I moved to almost all standard templating
instead of so much AJAX.  Visibly it has been updated to Bootstrap3 and has more polish.
Pages like container details have more information and it is not quite so bland.

Here are a few screenshots:

## Login

![Login](http://i.imgur.com/8WGsK2Gh.png)

## Containers

![Containers](http://i.imgur.com/5DAMDw8h.png)

## Container Details

![Container Details](http://i.imgur.com/QFDtF7Ch.png)

_...more screenshots on Github..._

With the refresh I wanted to add a better base feel to it.  Granted it needs
a lot more love (pull requests welcome!) but I think it is better than before.

The roadmap is packed with goodness.  Next up I want to start gathering
statistics for containers and hosts.  After that will be an API and then "Blueprints".
I will go into detail in another post but a blueprint is essentially a way
to map and connect containers (dependencies, environment variable injection, etc.)

You can launch the new Shipyard by `docker run ehazlett/shipyard` (make sure to
`docker pull ehazlett/shipyard` if you already have the image to get the latest).

For more information and updated screenshots source is on [Github](https://github.com/ehazlett/shipyard).

As usual, thanks to the [Docker](http://docker.io) team for kicking so much ass :)
