# Tasker

Tasker is a simple Android app that customizes the experience of using Trello, converting it into a 
task list or TODO app, along with other minor modifications.

*Please note that this app was just built for fun and targeting some very specific use cases, that
 might well not suit your needs.*

## The Build

**"How do I get a copy of the app?"**

So far, I have not released the app through Google Play, but I'll probably upload some builds 
somewhere so you don't need to install the whole Android development system to get your `.apk`.

*This is free, open source software. Check the license information in the [LICENSE](./LICENSE) 
file.* Feel free to get the sources from this very same repository and build it on your own!

## What does Tasker do?

Tasker is meant to provide a layer of abstraction on top of my favourite task management system:
[Trello](https://trello.com). When configured, its purpose is to retrieve information from a 
particular Trello board and present it in a different way.

* **Why Trello?** Because I find it convenient for most of my projects management. Because I 
don't have to develop and maintain the backend. And because, whenever necessary, I can always 
check the same information in a browser, which is much easier than in a smartphone.

* **Why not standalone Trello?** Because there are some missing features for me. Basically, a 
simple TODO list, with priorities and automatic reminders in my phone (which Trello wasn't built 
for! And I am glad it is that way, really.)

* **Why not any other TODO apps?** Because either they suck or they don't work anymore on my 
Gingerbread device.

### Planned Features

The following is a description of the features I am thinking to incorporate! (as of 6th Feb, 2016)

#### TODO

A selected list from the board is transformed into a TODO list, with easy task deletion and 
creation processes.

Trello labels (possibly custom ones) can be used to indicate different task priorities.

Automatic reminder system. Very annoying for some, but necessary for me, because I always forget 
to check my personal task management apps. It doesn't happen at work... Weird. 

If a task has a deadline, it'd be great to create a calendar event, possibly using some Google 
Calendar API (not checked yet).

#### ???

(work in progress)

### Architecture and libraries

(work in progress)

* [Dagger](http://square.github.io/dagger)
* [Android Times Square](https://github.com/square/android-times-square)
* [Retrofit](http://square.github.io/retrofit)
* [Picasso](http://square.github.io/picasso)
* [Otto](http://square.github.io/otto)