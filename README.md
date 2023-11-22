JSON schemas for PMM YAML files

How to use it:
Add this line to the top of your config.yml:
```
# yaml-language-server: $schema=https://raw.githubusercontent.com/chazlarson/pmm-yaml-schema/main/config_schema.json
```
That's all you need with VSCode anyway.  Some other editor might require something else.

limitations:

- template variables not cased for specific default file
- template variables with keys are wildcarded
- "position" attribute has no validation
- "streaming" default has no validation

TODO:

- schema for metadata yaml
