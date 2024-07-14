---
title: Note-taking system using Obsidian and the PARA method
date: 2024-07-13T11:53:11-03:00
draft: false
description: 'In this blog post I explain the PARA method and how you should take notes using Obsidian'
---

## Introduction

I'm the type of person that forget things easily (not _that_ easily, but you
know what's like) and sometimes I thought I need something to write down what
I need to remember later. What I really need to remember I generally create an
event in Google Calendar, so I don't miss it. But what about the new ideas
I have? And the things I want to do? All these things I eventually forget and
don't remember anymore. That's bad.

But what I need to get started? Well, I really wanted the most frictionless way
possible to create my notes and store it somewhere. I already tried
[Notion](https://www.notion.so/) (as everyone else tried, I think) and saw some
productivity videos. Way too complicated. I needed something simpler.
And that's where I found [Obsidian](https://obsidian.md/).

What I like about Obsidian? Well, there's some advantages of using Obsidian
over another note-taking app:

* **Markdown format**: this is a big win for me, as Markdown is the most simple
  format to write text. In which format the READMEs are written in? You guessed
  it: Markdown. Also, I'm able to write in any Markdown-compatible editor. In
  fact, I'm writing this post in Vim :)
* **Ease of editing**: It's really easy and simple to write notes in Obsidian.
  It formats the Markdown files the way I want.
* **Local files**: Everything I write is stored as local files, not in the
  cloud. This way, who owns the knowledgement (i.e., the files) is me, not some
  company.
* **Portability**: Obsidian also offers a mobile app. This way I cant write
  down what I need and see it later on my mobile phone. You can sync your
  computer with your phone using the paid service Obsidian offers. But you can
  sync your notes using something else. I'm using
  [Syncthing](https://docs.syncthing.net/intro/getting-started.html) to sync my
  notes between my laptop and my smartphone.

> I will write a post about syncing notes using Syncthing soon, so stay tuned.

## PARA method

The PARA method is a way of organizing your life and not just notes. It's
a method created by Tiago Forte in his book [Building a Second
Brain](https://a.co/d/cJWvCuL).

PARA is an acronym for:

* **P**rojects
* **A**reas
* **R**esources
* **A**rchive

### Projects

You can think of a _project_ as an order of tasks that need to be done to
achieve a certain goal. A project also has a clearly end state and a period of
some months. For example, planning a vacation could be a project, as well as
creating a blog.

In the PARA method, there would be a "Projects" folder and you would collect
information towards completing a certain goal (i.e., a _project_). To do so,
you would write notes for your small tasks, could be a single note for
a certain task or a lot of notes for another certain task, depending on the
complexity of the task.

### Areas

An area is a project that never ends. Think of an area as an area of your life,
i.e., it envolves an ongoing engagement and will play a important role in your
life. It can be: family, work, friends, your health.

So, you can take notes on how you are doing or how you can do better. Actually,
you can take a note of anything related to some of your areas.

Realize that these folders can be moved into another folders. Maybe you want to
buy a new house. It's just a plan with certain tasks. So, it fits better in the
_Projects_ folder. As time goes, you accomplish the tasks, and you bought the
house. Now, you have to take care of it, and you don't know how much time
you'll have the house. It's a project and has no end time. So, you can move
this folder you named "House" to your _Areas_ folder.

### Resources

Resources are collections of information can be useful in the future, i.e.,
they are references. Well, to give you an example, I used to gather this kind
of information in my browser bookmarks. I have various collections of folders
in my bookmarks, like _Linux_, _Programming_, _Animes/Manga_, etc. In the
folder of Linux there are another folders related to Linux. These are all link
I found useful and/or interesting. Don't know, maybe I will use it in the
future or it'll be useful for someone else asking me for help.

### Archive

This is where you place notes that are not useful currently or in the near
future but you either don't want to throw them away.

Imagine you have made a 3 years old note. You don't find it so useful anymore
but, who knows, it can be useful in the future. So, it's an note you put in the
_Archive_ folder.

Sometimes you will make an unexpected link between a note you are writing
right now with this vary note you've made 3 years ago, and this will be
magical. It's also good to see how we evolved over time, what we used to
thought back then, and how we think _now_.

Also, you can move a _project_ or even an _area_ to the Archive folder, as it's
something you don't really need anymore.

### Extra: Inbox

Remember when I said that I wish something frictionless to write notes? Imagine
you wrote a note. Where to put this note? Well, don't waste your time thinking
this. If the folder it's not obvious, put it in the _Inbox_ folder.

The Inbox folder is the place you put a note you just made and know where it
should be.

Of course, later on, you have to take some time to think on where the notes on
Inbox folder should be, so you don't accumulate a lot of notes in there. This
way, you can take a note whenever you want and place it in the right place when
you will have time to do so. Remember: it's your note-taking system, the
importance of it is to take notes and not organize it the best way possible
right away.

### Structure of folders

In my Obsidian Vault (the _root_ of your folders and files), I organize the
folders like so:

```text
+ Obsidian Vault
  |
  +-- 0 Inbox
  +-- 1 Projects
  +-- 2 Areas
  +-- 3 Resources
  +-- 4 Archive
```

As you can see, everything is under my `Obsidian Vault` and there are five
folders bellow it. I've numbered my folders so when I `ls` on the folders, they
are on the order I want.

### Pitfalls and principles

* **Make decisions quickly**: don't overthink, write a note and put it in the
  Inbox folder. If you know where the note should be, it shouldn't take more
  than 3 seconds to decide where it should be.
* **Avoid moving files around all the time**: you will sometimes think: well,
  this note would be better here and there, and this one in there, and so on.
  It feels like productivity, but generally it's a waste of time. It's okay to do
  this rarely.
* **Your note-taking should be efficient to you**: If you always overthink
  where a certain note should be, maybe you have to stop and reflect on what
  you want, and even maybe the PARA method is not for you. And that's ok. But
  give it a few months.

## Conclusion

The PARA method really help us organizing our notes as it grows. Obsidian, on
the other hand, is by far the best Markdown editor available. Markdown is
a dead simple format to learn, so take notes should not be a problem. The
important thing is: take a note. That's just it.

I'm myself a beginner on this: on both taking notes and doing it on Obsidian.
I wrote this blog so I can reference and know what I should be doing. It's also
a way of taking notes, because the posts themselves are written in Markdown.

> Note: I'm not a English-native speaker, so maybe there are some typos I've
made.

## Links

I highly recommend you to check out these links:

* [(video) Note-taking with the PARA method - Best for Beginners](https://youtu.be/oxUVn37-Igk?si=S0kjK8jslyoLRLJk)
* [(docs) Obdisian Help](https://help.obsidian.md/Home)
