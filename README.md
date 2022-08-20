# NEZU

NEZU is a Typlog built-in theme. It is a single column theme. This theme supports
both blog posts and podcast episodes.

## Install

Head over to **Settings → Themes & Design** and select **Nezu** theme.

## Configure

> This is the advanced configuration, only available for Pro subscribers.

Create an **asset** JSON in admin portal, set slug to `_config/nezu`. Here is an example of the configration:

```json
{
    "logo": {
        "light": "https://path/to/logo.svg",  // logo for light theme
        "dark": "https://path/to/logo-alt.svg"    // logo for dark theme
    },
    "css_files": [],
    "primary_nav": [],
    "secondary_nav": [],
    "foot_nav": []
}
```

Here is our demo's configration:

```json
{
  "logo": {
    "dark": "https://typlog.com/assets/logo-white.svg",
    "light": "https://typlog.com/assets/logo-black.svg"
  },
  "primary_nav": [
    {
      "title": "Show Cases",
      "links": [
        {"title": "By tag", "subtitle": "List of posts tagged with template", "url": "/topic/template/"},
        {"title": "By author", "subtitle": "Articles and podcasts by cat", "url": "/by/cat/"}
      ]
    },
    {"title": "Elements", "url": "/blog/elements"}
  ],
  "secondary_nav": [
    {"title": "Source", "url": "https://github.com/typlog/nezu"}
  ]
}
```

## License

Copyright of the design and code is reserved.
