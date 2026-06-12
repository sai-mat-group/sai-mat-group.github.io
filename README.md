# <b> Simulations And Informatics of MATerials Group</b><br>

This is the repository containing the website of the research group of [Prof. Sai Gautam Gopalakrishnan](https://materials.iisc.ac.in/faculty-list). 

## Build site
The website uses the framework of [GitHub Pages](https://pages.github.com) along with [Jekyll](https://jekyllrb.com) to render a collection of [Markdown](https://daringfireball.net/projects/markdown/syntax) files. While the HTML and CSS files are made available publicly here, please email [me](mailto:saigautamg@iisc.ac.in) for access to the full repository containing all the Jekyll build and Markdown files.

To build the website, please install Ruby dependencies by running `bundle install` from within the `root` directory. After this, the site can be built with:
```
bundle exec jekyll build
```
If there are errors until this stage, please ensure that your `bundle` version is compatible with the `Gemfile`. Further help can be obtained [here](https://jekyllrb.com/docs/installation/).

Once the build is complete, the site can be viewed by running
```
bundle exec jekyll serve
```
and opening a browser to `http://localhost:4000/`.

## Contribute

Research/publications posts just require YAML top matter that looks something like:

```
---
layout: post
title: Document-title
author: Sai Gautam Gopalakrishnan
link: <relevant-link>
image: <associated-image>.png
---
```

The `layout`, `title` and `author` tags are required, while `link` and `image` are optional.  Just save a Markdown file with this top matter as something like `papers/_posts/2020-08-22-my-new-paper.md`, where `2020-08-22` is the date of the post and `my-new-paper` is the short title.  This short title is used in the URL of the post, so this becomes `papers/my-new-paper/`, so the short title should be long enough and unique enough not to cause conflicts with other posts.

## For more information

* Look over the [metadata format guide](http://bedford.io/guide/format/)
* Look over the [Markdown style guide](http://bedford.io/guide/style/)


# <b>License</b><br>

MIT License

Copyright (c) 2020-present Sai Gautam Gopalakrishnan.

The source files used to build this repository are adapted from [Bedford Lab](https://bedford.io).

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
