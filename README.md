# abacus

A new octopress theme created by taking the best out of everything.

Simple, good readability, less clustered and beautiful.

Check the live demo here: [http://bhrigu.me](http://bhrigu.me)


### Quick install


```
  % cd octopress
  % git clone https://github.com/bhrigu123/abacus .themes/abacus
  % rake install['abacus']
  % rake generate
```

### Setting up the theme
After you have followed the above steps, do the following to finish setting up the theme:

1. Set up your site title, subtitle and author in your `_config.yml` file (if you haven't already).

2. Open file `source/_includes/custom/navigation_links.html` and edit the given list items. These will be in your navigation bar and home page. Edit/add/remove the anchor tags and their links.

3. In the folder `source/images`, replace the given `avatar.jpg` image file with your own pic. This pic will be displayed in the author info section of your blog posts.

4. Run `rake generate` once more.



`Note:` If your date format is not appearing properly on your site (it can happen that it shows "ordinal" written instead of date), then open your `_config.yml` file and edit the `date_format` parameter and change its value to:<br>
`date_format: "%a %e %b %Y, %l:%M %p" `


### More customizations

#### Changing the banner 
The banner image is present here: `source/images/banner.jpg`. To change your banner, replace this pic with another one & run `rake generate`.



### Snapshots
#### Banner

![banner](https://github.com/bhrigu123/bhrigu123.github.io/blob/source/source/images/theme/theme1.png)

#### Author

![autho](https://github.com/bhrigu123/bhrigu123.github.io/blob/source/source/images/theme/theme2.png)


Octopress version
=================

This theme aim to be compatible with Octopress 2.0,
the `master` branch from https://github.com/bhrigu123/abacus
(documented at http://octopress.org/).


This theme is inspired from Medium and was originally a fork of [octostrap3](https://github.com/kAworu/octostrap3).



## The MIT License
> Copyright (c) 2015 Bhrigu Srivastava http://bhrigu123.github.io

> Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
