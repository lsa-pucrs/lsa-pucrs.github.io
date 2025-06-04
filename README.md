Freelancer Jekyll theme  
=========================

Jekyll theme based on [Freelancer bootstrap theme ](http://startbootstrap.com/template-overviews/freelancer/)

## How to use
 - Place a image in `/img/portfolio/`
 - Replace `your-email@domain.com` in `_config.yml` with your email address. Refer to [formspree](http://formspree.io/) for more information.
 - Create posts to display your projects. Use the follow as an example:
```txt
---
layout: default
modal-id: 1
date: 2020-01-18
img: cabin.png
alt: image-alt
project-date: January 2020
client: The Client
category: Web Development
description: The description of the project

---
```

## Demo
View this jekyll theme in action [here](https://jeromelachaud.com/freelancer-theme)

## Screenshot
![screenshot](https://raw.githubusercontent.com/jeromelachaud/freelancer-theme/master/screenshot.png)

---------
For more details, read the [documentation](http://jekyllrb.com/)


## ENVIRONMENT SETUP

- use `rbenv` (see https://github.com/rbenv/rbenv) to install ruby `rbenv install 2.7.0`
- install jekyll requirements (see https://jekyllrb.com/docs/) 
- install jekyll and bundler gems `gem install jekyll bundler`
- install app dependencies `bundle install` (from app source dir)

## RUNNING THE APP

- `bundle exec jekyll serve --livereload`

