---
layout: post
title: "Hello, My EV3 kiki"
quote: "Do you want a cute rodulf delivering your coffee?"
image:
      url: https://images.pexels.com/photos/250177/pexels-photo-250177.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500
      
video: false
comments: true
theme_color: 302F2D
---

# Thinny 2.1, HELLO MY EV3 kiki

KIKI is the name of coffe delivery model made my J, S and N in Hanyang University at Ansan. 
In this post, I'll let you know about our cute delivery service, kiki


{% include image.html url="https://s1.narvii.com/image/nxeigvbxdqldsifavaxnc3qao6p36hdr_hq.jpg" width="100%" description="The motive of our robot, kiki's delivery service" %}

This picture above is our robot's motive, the movie 'Kiki's delivery service'. We wanted to make an adorable robot to deliver coffees to customers with joy and happiness in cafes.

## Usage

### Main variables

The global variables are set on the `_config.yml`[^1] file.

To start, you need to change at least the variable `url` on the file.

#### Social links

To add a social link you just need to add the following code inside the variable `social`:

~~~
  - icon:   [the genericon name for the social network]
    url:    [the url to follow]
    desc:   [a small description for the link (e.g. "Follow me on twitter")]
~~~

#### Menu

To add a menu item you just need to add the following code inside the variable `menu`:

~~~
  - title:  [title of the menu item]
    url:    [the url to follow]
~~~

#### Others

You'll find a lot of other variables inside the file, e.g.:

- the site `title`, `description`, `icon` and default `cover` image.
- text of the `copyright` message.
- the number of posts per page (`paginate`).
- the `permalink`'s structure (see [the docs](http://jekyllrb.com/docs/pagination/)).


### Default YAML tags

- `layout:`<i>`post, page`</i> `or `<i>`fullscreen`</i>: defines the layout of the page.
- `title: [string]`: title of the post.
- `quote: [string]`: a small description of the post to be shown above the title.
- `dark:`<i>`true`</i> `or `<i>`false`</i>: use black font (instead of white) for the header (default value is false).
- `image: [url] or `<i>`false`</i>: a cover image for the post (default value is _false_).
- `video:`<i>`true`</i> `or `<i>`false`</i>: add a cover video for the post (default value is _false_).
- `video_mp4: [url]`: the URL for the mp4 video.
- `video_webm: [url]`: the URL for the webm video.
- `video_ogv: [url]`: the URL for the ogv video.

## Versions

Here is a table with all Thinny's versions:

|----
| Version | Codename | Platform | Release date
|:-:|:-:|:-:|:-:
| [0.3](https://github.com/camporez/Thinny/releases/tag/v0.3-alexandra) | [Alexandra](http://nikita2010.wikia.com/wiki/Alexandra_Udinov) | Ghost 0.3.x |November 2013
| [2.0](https://github.com/camporez/Thinny/releases/tag/v2.0-bianca) | [Bianca](http://memoriaglobo.globo.com/programas/entretenimento/novelas/caras-bocas/caras-bocas-bianca-isabelle-drummond.htm) | Jekyll | January 2014 |
| [2.1](https://github.com/camporez/Thinny/releases/tag/v2.1-cosette) | [Cosette](http://lesmiserables.wikia.com/wiki/Cosette) | Jekyll | February 2014
| 2.2 | [Dolores](http://en.wikipedia.org/wiki/Dolores_Haze) | Jekyll | _Soon..._[^2]
|----

## Download

> Thinny 2.1 is already [available for download on GitHub](https://github.com/camporez/Thinny/releases).

-----
Want to see something else added or report a bug? [Open an issue](https://github.com/camporez/camporez.github.io/issues/new).

[^1]: This file is placed in your root directory. It's the main file of configuration. For more information, read [the docs](http://jekyllrb.com/docs/configuration/).
[^2]: See the [issues list](https://github.com/camporez/camporez.github.io/issues?milestone=3).
