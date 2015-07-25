---
layout: post
title: "Animations and Context in UI Design"
date: 2015-07-28 10:00:00 -0500
categories: ui design animation web apps
---

I just read [this post](https://medium.com/@sophie_paxtonUX/stop-gratuitous-ui-animation-9ece9aa9eb97) complaining of "superflous" animation in user interfaces, and felt compelled to respond. The author seems to throw out any and all animation, discounting all of the benefits due to a few bad implementations.

I agree that the examples given - Mac OS's full screen transition in particular - are quite slow, and even a bit unhelpful. But remember that we humans have a reaction time inherent in any context change. So any time the UI changes from one place to another in a dramatic way, it takes a short moment for users to understand what's going on. Web interfaces - including the "fixed" examples in the post - appear clunky and incomplete when they lack the animation between modals.

But in my experience, users recover better from these context changes when I animate between them. It softens the blow a bit. Even a fast animation is better than no animation at all. I suspect the author has a difficulty-of-implementation bias against animations in interfaces. Depending on the library you're working with for UI, it can be tough to implement. Some developers dislike them because they find it to be extra work, and they don't understand the reasoning behind it. But I can show you examples from my user testing - animations between full-screen or modal interfaces significantly help users, especially users not otherwise comfortable with technology.