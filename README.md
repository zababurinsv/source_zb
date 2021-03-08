# source_zb

/**
 * Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi sodales ut est eu varius. Vivamus imperdiet aliquet risus, vel tincidunt massa     sagittis nec. In magna massa, maximus sit amet lectus id, venenatis viverra felis. Ut molestie nisl in mauris scelerisque, non hendrerit lacus gravida.
 * @module config
 */
```
{
  "plugins": [
    "plugins/markdown",
    "plugins/summarize"
  ],
  "recurseDepth": 10,
  "source": {
    "include": [
      "./docs/static/html/components/",
      "./docs/src/frontmatter.md"
    ],
    "includePattern": ".+\\.(js(doc|x)?|mjs)$",
    "excludePattern": "(^|\\/|\\\\)_"
  },
  "sourceType": "module",
  "tags": {
    "allowUnknownTags": true,
    "dictionaries": ["jsdoc","closure"]
  },
  "markdown": {
    "parser": "gfm",
    "hardwrap": true
  },
  "templates": {
    "search": true,
    "cleverLinks": false,
    "monospaceLinks": false,
    "default": {
      "outputSourceFiles": true,
      "includeDate": false
    },
    "scripts": [],
    "favicon": "",
    "css": []
  },
  "menu":{
    "Admin Documentation": {
      "href":"https://zababurinsv.github.io/admin/",
      "target":"_blank",
      "class":"menu-item",
      "id":"repository"
    }
  },
  "opts": {
    "template": "./docs/src/templates/docdash",
    "encoding": "utf8",
    "destination": "./docs/src/docs/",
    "recurse": true,
    "verbose": false
  },
  "docdash": {
    "static": false,
    "sort": true
  }
}

```
