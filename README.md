# yaml-parser (for Polymer)

By Yarmo Mackenbach

(DEMO)[https://yarmom.github.io/yaml-parser/]

## Usage

Just add

`<link rel="import" href="/bower_componenents/yaml-parser/yaml-parser.html">`

to the top of your Polymer element or page, then include

`<yaml-parser yaml="" valid-yaml="" json=""></yaml-parser>`

somewhere in your template or page.

You can now set the `yaml` attribute of the `yaml-parser` element to any string of valid YAML and immediately read the outputted JSON by reading the `json` attribute.

To know if your YAML was valid, just read the `valid-yaml` tag and make sure it's true.
