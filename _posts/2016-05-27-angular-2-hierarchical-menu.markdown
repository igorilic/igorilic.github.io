---
layout: post
title: Angular 2 Hierarchical Menu
modified:
categories:
excerpt:
tags: []
image:
  feature:
date: 2016-05-27T21:54:06+02:00
---

Right now Angular 2 is in RC1 release. There is no timeline for the next
release (probably RC2), but is going to be in the following weeks, maybe
months. If you are coming from Angular 1 and you want to know what the
differences are, you can find it out
[here](https://dzone.com/articles/typed-front-end-with-angular-2) or check
Minko Gechev's book [Switching to Angular
2](https://www.packtpub.com/web-development/switching-angular-2/?utm_source=RP-mgechev&utm_medium=referral&utm_campaign=1785887114).

# Hierarchical Menu

If you are building any kind of application, there is a need for menu
component in your Angular 2 app. In a business application there is a
requisite for dynamic build of menu from data. Suppose there is a web
service (ReST web api i.e.) which is going to deliver such data. Our goal
is to dynamically build the menu. Let's assume that we are getting this
kind of data:

{% gist 1539555f1702a645d3095e5105e7402e %}
