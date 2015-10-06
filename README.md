# lowlandsjs

## What is it?

It's a site for listing all js related events in the Netherlands.

## How can I add my event?

You send in a pull request _or_ you can create an issue,
then we will add it for you.

## If I send in a pull request, what should I do?

### Clone this repository

```bash
$ git clone https://github.com/lowlandsjs/lowlandsjs.github.io.git
```

### Add a post in `_posts`

The filename should be formatted like so:

```bash
$ {year}-{month}-{day}-{title}.md
```

This boils down to the following:

```bash
$ 2018-01-01-wowjs.md
```


```md
---
layout: default
title: "wowjs"
date:   2018-01-01
venue: "The Barnhouse Amsterdam"
ticket: "free"
time: "7:30pm"
href: "http://www.meetup.com/asdasdasdasd"
---

```


### What is this `pull request` you are talking about?

We can explain this, but github can [explain it better](https://help.github.com/articles/using-pull-requests/).
If you'd just like to get your hands dirty, [check here](https://help.github.com/articles/creating-a-pull-request/)
