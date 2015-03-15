+++
title = "Another Hugo Post"
description = "Nothing special, but one post is boring."
date = "2014-09-02"
author = "Marko J"
gravatar = "b80c3d5ca185ffc0ed2e749fa8ac59c7"
twitter = "jurmarko"
github = "jurmarko"
categories = [ "example", "configuration" ]
tags = [
    "example",
    "hugo",
    "toml",
    "Marko J"
]
+++

TOML, YAML, JSON --- Oh my!
-------------------------

One of the nifty Hugo features we should cover: flexible configuration and front matter formats! This entry has front
matter in `toml`, unlike the last one which used `yaml`, and `json` is also available if that's your preference.

The `toml` front matter used on this entry:

```
+++
title = "Another Hugo Post"
description = "Nothing special, but one post is boring."
date = "2014-09-02"
categories = [ "example", "configuration" ]
tags = [
    "example",
    "hugo",
    "toml"
]
+++
```

This flexibility also extends to your site's global configuration file. You're free to use any format you prefer::simply
name the file `config.yaml`, `config.toml` or `config.json`, and go on your merry way.

JSON Example
------------

How would this entry's front matter look in `json`? That's easy enough to demonstrate:

```
{
    "title": "Another Hugo Post",
    "description": "Nothing special, but one post is boring.",
    "date": "2014-09-02",
    "categories": [ "example", "configuration" ],
    "tags": [
        "example",
        "hugo",
        "toml"
    ],
}
```
