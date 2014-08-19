pandoc-schemata
===============

JSON Schema files for Pandoc JSON. More information on JSON Schema [here](http://json-schema.org/) and [here](http://spacetelescope.github.io/understanding-json-schema/). More information on Pandoc JSON [here](http://johnmacfarlane.net/pandoc/scripting.html).

* `default.json` validates minimal Pandoc JSON file
* `title_block.json` validates file with Pandoc title block: `title`, `author`, `date`
* `jekyll.json` validates [Jekyll](http://jekyllrb.com/) YAML header (`layout` and `title` are required)
* `jats.json` validates [JATS](http://jats.nlm.nih.gov/publishing/tag-library/1.0/index.html) (currently a limited subset)
* `citeproc.json` validates references formatted with [pandoc-citeproc](https://github.com/jgm/pandoc-citeproc) (currently a limited subset)

## Validators

* **Javascript**: [JSV](https://github.com/garycourt/JSV)
* **Haskell**: [aeson-schema](https://github.com/timjb/aeson-schema)
* **Python**: [jsonschema](https://python-jsonschema.readthedocs.org/en/latest/)
* **Ruby**: [json-schema](https://github.com/hoxworth/json-schema)
* **Online**: [JSON Schema Lint](http://jsonschemalint.com/)

More validators are listed on the [JSON Schema implementations](http://json-schema.org/implementations.html) page.

### Licence

[Creative Commons CC 0](LICENSE).
