# Debet Esse

Debet Esse is a simple Hugo theme used for personal websites and blogs. A live demo of
the theme can be found at [https://miikanissi.com/](https://miikanissi.com/).

![Screenshot of theme in light mode](https://github.com/miikanissi/debet-esse/blob/master/docs/screenshot-light.png?raw=true)
![Screenshot of theme in dark mode](https://github.com/miikanissi/debet-esse/blob/master/docs/screenshot-dark.png?raw=true)

## Features:

- Homepage with a list of posts
- Responsive design for mobile devices
- Syntax highlighting
- Automatic or manual dark theme mode
- No JavaScript, no web fonts, no external dependencies
- Search Engine Optimized (SEO) with relevant descriptions and JSON-LD schema
- RSS Feed for posts
- Internationalization: Create custom translations

## Installation:

To install `debet-esse`, download the repository into the `themes` folder in the root of
your Hugo site.

With an existing git repository:

```
git submodule add https://github.com/miikanissi/debet-esse.git themes/debet-esse
```

Without a git repository:

```
git clone https://github.com/miikanissi/debet-esse.git themes/debet-esse
```

To try out the theme:

```
hugo server -t etch
```

Use the
[sample configuration](https://github.com/miikanissi/miikanissi.com/blob/master/config.toml)
as a starting point to enable theme for production use.
