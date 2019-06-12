---
layout: post
title: Example content
tags:
  - jekyll
  - dactl
description: >
  Howdy! This is an example blog post that shows several types of HTML content
  supported in this theme.
hero: https://source.unsplash.com/collection/145103/
overlay: green
published: true
---

Cum sociis natoque penatibus et magnis <a href="#">dis parturient montes</a>, nascetur ridiculus mus. *Aenean eu leo quam.* Pellentesque ornare sem lacinia quam venenatis vestibulum. Sed posuere consectetur est at lobortis. Cras mattis consectetur purus sit amet fermentum.
{: .lead}

Etiam porta **sem malesuada magna** mollis euismod. Cras mattis consectetur purus sit amet fermentum. Aenean lacinia bibendum nulla sed consectetur.
<!–-break-–>

> Curabitur blandit tempus porttitor. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit.

Etiam porta **sem malesuada magna** mollis euismod. Cras mattis consectetur purus sit amet fermentum. Aenean lacinia bibendum nulla sed consectetur.
{: .notice}

## Inline HTML elements

HTML defines a long list of available inline tags, a complete list of which can be found on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

- **To bold text**, use `**To bold text**`.
- *To italicize text*, use `*To italicize text*`.
- Abbreviations, like HTML should be defined like this `*[HTML]: HyperText Markup Language`.
- Citations, like <cite>&mdash; Mark otto</cite>, should use `<cite>`.
- ~~Deleted~~ text should use `~~deleted~~` and <ins>inserted</ins> text should use `<ins>`.
- Superscript <sup>text</sup> uses `<sup>` and subscript <sub>text</sub> uses `<sub>`[^1].

Most of these elements are styled by browsers with few modifications on our part.

## Heading

Vivamus sagittis lacus vel augue rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.

## Code

Cum sociis natoque penatibus et magnis dis `code element` montes, nascetur ridiculus mus.

~~~js
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those
// arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
~~~

## Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

* Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
* Donec id elit non mi porta gravida at eget metus.
* Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

HyperText Markup Language (HTML)
: The language used to describe and define the content of a Web page

Cascading Style Sheets (CSS)
: Used to describe the appearance of Web content

JavaScript (JS)
: The programming language used to build advanced Web sites and applications

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo. Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.
{: .notice-alert}

## Images

Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![1200x700](http://placehold.it/1200x700 "Large example image"){:.oversize}
![800x400](http://placehold.it/800x400 "Large example image"){:.lead}
![400x200](http://placehold.it/400x200 "Medium example image")
![200x200](http://placehold.it/200x200 "Small example image")

## Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

| Name     | Upvotes   | Downvotes |
|----------|-----------|-----------|
| Alice    |        10 |        11 |
| Bob      |         4 |         3 |
| Charlie  |         7 |         9 |
|Totals    |        21 |        23 |

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.


You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`.
{: .lead}
<!–-break-–>
This launches a web server and auto-regenerates your site when a file is updated.  
To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

~~~ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
~~~

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll’s dedicated Help repository][jekyll-help].

[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help





By default dactl has a couple of special classes which will turn a paragraph into a notice block when added to it. Read on for information on how to use it.
{: .lead}

## How to create a notice block
Creating notices from your paragraphs works the same way as creating [leading post paragraphs](LINKILYNKI).  
You need to add a correct class **after** the paragraph:
<!–-break-–>
~~~
Sea otters [hold each other’s paws](https://www.youtube.com/watch?v=eTvX-CkfqRo) when they sleep so they don’t drift apart.  
That is a fact, look it up on Wikipedia if you don't believe me.
{: .notice}
~~~

## Available options
### Regular notice block
`{: .notice}`

Sea otters [hold each other’s paws](https://www.youtube.com/watch?v=eTvX-CkfqRo) when they sleep so they don’t drift apart.  
That is a fact, look it up on Wikipedia if you don't believe me.
{: .notice}

### Alert notice block
`{: .notice-alert}`

If one examines the capitalist paradigm of context, one is faced with a
choice: either accept textual narrative or conclude that reality serves to
exploit the Other.
{: .notice-alert}

### Success notice block
`{: .notice-success}`

If one examines the capitalist paradigm of context, one is faced with a
choice: either accept textual narrative or conclude that reality serves to
exploit the Other.
{: .notice-success}

## Multi-paragraph notice blocks
The easiest solution I found to wrapping more than paragraph into a notice is just inserting it into a markdown-enabled `div` tag, like this:
```html
<div class="notice" markdown="1">
If one examines the capitalist paradigm of context, one is faced with a
choice: either accept textual narrative or conclude that reality serves to
exploit the Other.

A number of dematerialisms concerning textual objectivism
exist. However, if textual narrative holds, we have to choose between
precultural theory and the conceptual paradigm of consensus.
</div>
```

Which, when processed by kramdown, shows up like this:
<div class="notice" markdown="1">
If one examines the capitalist paradigm of context, one is faced with a
choice: either accept textual narrative or conclude that reality serves to
exploit the Other.

A number of dematerialisms concerning textual objectivism
exist. However, if textual narrative holds, we have to choose between
precultural theory and the conceptual paradigm of consensus.
</div>












All of the dactl's configurations has to be set in `_config.yml` file. Read on for explanation of all of the features that you can toggle, including configuring the layout.
{: .lead}

I've split dactl's `_config.yml` into two parts. First part should be configured by you, second contains important Jekyll & build settings and you should leave it alone, unless you know what you are doing.
<!–-break-–>

Let's go through each line in the first, configurable part:

~~~yaml
# Base blog settings
blog:
  title                      : dactl
  description                : >
                               this should contain a proper description
# Layout configuration
  logo_path                  : "assets/img/dactl.svg" # path to logo file
  search_path                : # "yourgitusername.github.io"
                               # needed for searchbox in archive page
  hero_layout                : true # turn on hero layout for blog and posts
  hero_placeholder           : "assets/img/generic_hero.jpg" # placeholder for hero
  excerpts                   : true # show excerpts instead of full post content on blog page
  inline_footnotes           : true # enable/disable barefoot inline footnotes
  titles_only                : false # titles only on main blog page

# Fonts
font                         : '"Rubik", -apple-system, BlinkMacSystemFont, "Helvetica Neue", sans-serif'
load_google_fonts            : 'Rubik:400,400italic,700,700italic'

# Author info
author:
  fullname                  : Your Name
  rss                       : true # generate RSS feed and show it's icon in header
  mail                      : your@email.com # change to your e-mail address
  twitter                   : twitter-user-name
  github                    : github-user-name
  youtube                   : youtube-user-name
  stackoverflow             : stackoverflow-user-name
  disqus                    : dactl # your disqus site name
  google_analytics          : # 'UA-XXXXXXXX-X'
  photo                     : "uploads/me2.png"
  photo2x                   : "uploads/me.png"

baseurl                      : "/dactl/" # the subpath of your site, e.g. /blog/, set to '' in case of hosting on GitHub pages
                                  # i.e. `http://<username>.github.io`
url                          : "" # the base hostname & protocol for your site
~~~

## Base blog settings
* `title` - title of your blog, both in `<title>` tag and in the header.
* `description` - descriptionof your blog, shown in the footer

## Layout settings
* `logo_path` - Path to an .svg image used as logo
* `search_path` - Path to your blog, needed for the DuckDuckGo's searchbar found in Archive page.
* `hero_layout` - true / false - Turn the hero image layout on or off. When turned off you don't need to supply images and overlays in post's YAML front matter and the layout gets slightly adjusted.
* `hero_placeholder` - Path to an image which will be used as a placeholder when there is no hero set for post, optional.
* `excerpts` - true or false - Turn post excerpts on or off. When set to `false` you will see full text content for each post on blog page.
* `inline_footnotes` - true or false - When set to `false` you will turn off Barefoot.js inline footnotes.
* `titles_only` - true or false - When set to true Jekyll will generate blog layout with post titles only. `hero_layout` and `excerpts` are overidden by `titles_only` when it's set to `true`.

## Fonts
* `font` - Name of the font family used for theme's typography.
* `load_google_fonts` - Choose what font family should be loaded, served by [google fonts](https://fonts.google.com).
In order to change the font you need to supply it's name and variants - font weight of 400 and 700 are required.  

## Author info
* `fullname` - Your name and surname or nick, used throughout the blog.
* `rss` - true or false - Turn the RSS feeds on or off.
* `mail` - Your e-mail address.
* `twitter` - Your twitter username
* `github` - Your Github username
* `youtube` - Your YouTube username
* `stackoverflow` - Your Stackoverflow username
* `disqus` - Your Disqus site name.
* `photo` - Avatar or photo of you, used on About page.
* `photo2x` - Same as above but in higher resolution.

## Google Analytics
* `google_analytics` - Supply your Google Analytics ID here, if you want to use it.
* `baseurl` - Subpath of your blog, e.g. `/blog`, leave it empty in case of hosting on Github pages - `yourusername.github.io`





















## Math


Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.
Nullam id [^2] dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

[^1]: You can insert footnote marks using `[^1]`, `[^2]`, etc and write the footnote text at the bottom of your file like this: `[^1]: You can also insert footnote marks...`

[^2]: Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo. Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

*[HTML]: HyperText Markup Language
*[CSS]: Cascading Style Sheets
*[JS]: JavaScript



