---
layout: page
title: About
permalink: /About/
feature-img: "img/sample_feature_img_2.png"
---

# Fengzhichu Theme

A jekyll theme for personal blog which based on [Type theme](https://github.com/rohanchandra/type-theme) and [ibireme's blog](http://blog.ibireme.com). Add several useful features. Fengzhichu Theme is powered by [Jekyll](http://jekyllrb.com/) and freely
hosted in [Github pages](https://pages.github.com/).

## How to use it
* Star & Fork the [repo](https://github.com/fengzhichu/fengzhichu-theme).
* Rename repo as 'yourusername.github.io'.
* You can delete gh-pages branch if you want.
* Clone your <b>master branch</b> to local directory.
* Custom the '_config.yml' to your style.
* Run jekyll serve -w.

## Customization

### _config.yml
Some important configurations.

* imageurl: Randomly change image which display on top of site.
  * By default image changes everytime when open your site or reflash it. If you want to change image daily or weekly, just append '/daily' or 'weekly' to imageurl.
* title: Display on browse tab.
* hometitle: The first menu name of navigation bar.
* yoursitetitle: Your LOGO place here.
* visiblewords: Number of words which you want to display in post of homepage.
* sechby:
  * category: "Posted in" #Words before Category name.
  * tag: "with" #Words before Tag name.
  * example: Posted in 'Category name' with 'Tag name'.

### Tags
Add new tag.

* Annotate your post entry front-matter block as usual:

```
		---
		layout: post
		title: How To Use Tags And Categories On GitHub Pages Without Plugins
		category: programming
		tags: [github, github-pages, jekyll]
		---
```

* Add an entry in your _data/tags.yml for every tag.

```
		- slug: github-pages
		  name: GitHub Pages
```

* Create a .md file which name is your Tag slug for every tag.

```
		---
		layout: blog_by_tag
		tag: github-pages
		permalink: /blog/tag/github-pages/
		---
  ```

###Categories
Similar as Tags.

## Thanks
* Theme template: [type-theme](https://github.com/rohanchandra/type-theme)
* Navigation bar: [ibireme's blog](http://blog.ibireme.com)
* Features of Tag and Category: [HOW TO USE TAGS AND CATEGORIES ON GITHUB PAGES WITHOUT PLUGINS](http://www.minddust.com/post/tags-and-categories-on-github-pages/)

## Enjoy
- If you like, please star it. Thank you!
- Enjoy it!

## Copyright & License
Copyright (C) 2015 - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE. 
