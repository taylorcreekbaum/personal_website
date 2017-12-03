---
title: About Me
feature_text: |
  ## Taylor Creekbaum
  An electrical engineer and programming enthusiast looking to use my skills to make a positive impact on the world around me.
feature_image: "https://unsplash.it/1300/400?image=971"
excerpt: "I have a desire to my best and to do right by others in all things I do."
---

I'm Taylor, an aspiring electrical engineer and hobbyist programmer. This is my personal website and on it you can find some information about me, my career, hobbies, interests, and side projects. Additionally, the site includes a blog where I hope to document some of the fun experiences I am fortunate enough to have. But first, check out what I'm up to on social media (hint: not much):

{% include button.html text="Twitter" icon="twitter" link="https://twitter.com/wartree88" color="#1DA1F2" %} {% include button.html text="LinkedIn" icon="linkedin" link="https://linkedin.com/in/taylorcreekbaum" color="#0077B5" %} {% include button.html text="Facebook" icon="facebook" link="https://facebook.com/tcreekbaum" color="#3B5998" %} {% include button.html text="Instagram" icon="instagram" link="https://www.instagram.com/taylorcreekbaum/" color="#E1306C" %}

## Career Interests

I am an electrical engineer with 5+ years of experience in the power industry. I have experience with low and medium voltage electrical distribution systems that includes both design and reliability aspects. Click the button to see more detailed information about my professional background!

{% include button.html text="Career" link="/career/" %}

## Examples

Here are a few examples of Alembic out in the wild being used in a variety of ways:

- [bitpodcast.com](https://bitpodcast.com/)
- [joelcagedesign.com](https://joelcagedesign.com/)
- [bawejakunal.github.io](https://bawejakunal.github.io/)
- [case2111.github.io](http://case2111.github.io/)
- [www.10people.co.uk](http://www.10people.co.uk/)
- [hrkeni.me](http://hrkeni.me/)
- [venuthatikonda.github.io](https://venuthatikonda.github.io/)
- [ccs17.bsc.es](https://ccs17.bsc.es/)
- [karateca.org](http://www.karateca.org/)

## Installation

### As a Boilerplate / Fork

1. [Fork the repo](https://github.com/daviddarnes/alembic#fork-destination-box)
2. Clone down the repo with `git clone git@github.com:username/reponame.git`
3. Replace the `Gemfile` in the root of the repo with the one in `demo/Gemfile`
4. Delete the following unnecessary files/folders: `demo/`, `CODE_OF_CONDUCT.md`, `CONTRIBUTING.md`, `LICENSE`, `screenshot.png` and `alembic-jekyll-theme.gemspec`
5. Change the `logo.svg` and `default-social-image.png` in the `assets/` folder to your own branding
6. Configure your site settings using the `_config.yml`, more info can be found in [Configuration](#configuration)
7. Change the `CNAME` record to your projects' record
8. Install bundler with `gem install bundler`
9. Install gems with `bundle install`
10. Run Jekyll with `bundle exec jekyll serve --watch`
11. Begin hacking for your project

### As a Jekyll 3.3 theme gem

1. Download the starter `/demo` content, [quick download link](https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/daviddarnes/alembic/tree/master/demo)
2. Configure your site settings using the `_config.yml`, more info can be found in [Configuration](https://github.com/daviddarnes/alembic#configuration)
3. Create a `logo.svg` and `default-social-image.png` in a new `assets/` folder
4. Install bundler with `$ gem install bundler`
5. Install gems with `$ bundle install`
6. Run Jekyll with `$ bundle exec jekyll serve --watch`
7. Begin hacking for your project

### Boilerplate & Theme differences

The boilerplate kit is better for more drastic hacking and changes, a project that's quite different to any other and needs a lot of custom work done. Additionally you'll only be able to use this method if you want to host it on GitHub Pages, as [themes can't be submitted](https://pages.github.com/themes/)... yet.

Using the theme will allow you to receive updates made and will be more programmatic. To make your own changes you'll need to overwrite the files with your own. For example: If I want to change the colours and typography of my site I'll need to copy the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file and create my own in `_sass/_settings.scss` with my own changes. This is the same for all files within the theme, which means your own project will be more lean than if you were to use the boilerplate.
