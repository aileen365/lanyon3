# [Did](https://mdo.github.io/did)

[Did](http://mdo.github.io/did) is a [Jekyll](http://jekyllrb.com) theme, designed and built by [@mdo](https://twitter.com/mdo). It's based on another theme, [Hyde](http://andhyde.com). Did is designed to showcase your content first and foremost. Navigation and extraneous information remains offscreen until the reader requests it.

![Did screenshot](https://f.cloud.github.com/assets/98681/1817392/308428d0-6f99-11e3-9d2c-e15e212ba291.png)

The name originates from a rather well-known, and unsurprisingly relevant, psychiatric condition, [dissociative identity disorder](http://en.wikipedia.org/wiki/Dissociative_identity_disorder). (Protip: It's just like Dr. Jekyll & Mr. Hyde.)


## Usage

### 1. Install Jekyll

Did is built for use with Jekyll, so naturally you'll need to install that. On Macs, it's rather straightforward:

```bash
$ gem install jekyll
```

**Windows users:** Windows users have a bit more work to do, but luckily [@juthilo](https://github.com/juthilo) has your back with his [Run Jekyll on Windows](https://github.com/juthilo/run-jekyll-on-windows) guide.

You may also need to install Pygments, the Python syntax highlighter for code snippets that places nicely with Jekyll. Read more about this [in the Jekyll docs](http://jekyllrb.com/docs/templates/#code_snippet_highlighting).

### 2a. Quick start

To help anyone with any level of familiarity with Jekyll quickly get started, Did includes everything you need for a basic Jekyll site. To that end, just download Did and start up Jekyll.

### 2b. Roll your own Jekyll site

Folks wishing to use Jekyll's templates and styles can do so with a little bit of manual labor. Download Did and then copy what you need (likely `_layouts/`, `*.html` files, `atom.xml` for RSS, and `public/` for CSS, JS, etc.).

### 3. Running locally

To see your Jekyll site with Did applied, start a Jekyll server. In Terminal, from `/did` (or whatever your Jekyll site's root directory is named):

```bash
$ jekyll serve
```

Open <http://localhost:4000> in your browser, and voilà. You're done.


## Options

Did includes a some customizable options, typically applied via classes on the `<body>` element.

### Sidebar menu

Create a list of nav links in the sidebar by assigning each Jekyll page the correct layout in the page's front matter.

```
---
layout: page
title: About
---
```

### Reverse layout

Reverse the page orientation with a single class.

```html
<body class="layout-reverse">
  ...
</body>
```


## Author

**Mark Otto**
<https://github.com/mdo>
<https://twitter.com/mdo>


## License

Open sourced under the [MIT license](LICENSE.md).

<3