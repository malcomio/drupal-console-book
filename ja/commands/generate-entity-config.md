# generate:entity:config
Generate a new config entity

**Usage:**
```
drupal generate:entity:config [options]
gec
gecg
```

## Available options
Option | Details
-------|-------------
--module | モジュール名
--entity-class | The config entity class
--entity-name | The config entity name
--base-path | The base-path for the config entity routes
--label | The label
--bundle-of | Acts as bundle for content entities

## Examples
* Generate config entity specifying the module, the entity class, the entity name, its path and label
```
drupal generate:entity:config  \
  --module="modulename"  \
  --entity-class="DefaultEntity"  \
  --entity-name="default_entity"  \
  --base-path="/admin/structure"  \
  --label="Default entity"
```
