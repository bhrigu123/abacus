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
The banner image path and name is: `source/images/banner.jpg`. To change your banner, replace this pic with another one (make sure it's named *banner.jpg* only) & run `rake generate`.  
If you have a different format (eg png) banner, you can directly edit the source banner CSS at `sass/partials/_banner.scss` and edit the URL of `background-image` attribute under `#banner-image` css.

#### Google Adsense header
If you want to include your Google Adsense header directly via config, you can add your Adsense client ID in your `_config.yml` with attribute name **google_adsense_client**. For eg.  `google_adsense_client: ca-pub-xxxx`.

#### Cover image for sharing your pages / posts on social media
When you share your page or a blog post in social media (eg Facebook), you get an image in the shared link. Now, the social media platform might not always pick up the cover pic in the share from the images present in your post. Using this theme, you can define a specific image for cover pic of the sared post.  
To do that, in your page or post's source yml headers at the top (where there are *layout*, *title*, attributes present), add another attribute: *coverimage*, and give the relative path of your image from your source. For eg. `coverimage: /images/folder1/img.png`

### Snapshots
#### Banner

![banner](https://github.com/bhrigu123/bhrigu123.github.io/blob/source/source/images/theme/theme1.png)

#### Author

![autho](https://github.com/bhrigu123/bhrigu123.github.io/blob/source/source/images/theme/theme2.png)


Octopress version
=================

This theme aim to be compatible with Octopress 2.0, (should work with 3.0 too)  
the `master` branch from https://github.com/bhrigu123/abacus
(documented at http://octopress.org/).


This theme is inspired from Medium and was originally a fork of [octostrap3](https://github.com/kAworu/octostrap3).



## The MIT License
> Copyright (c) 2017 Bhrigu Srivastava http://bhrigu.me

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
