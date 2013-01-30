---
title: EditorImageBrowserSchemaModelFieldsSize
slug: php-EditorImageBrowserSchemaModelFieldsSize
tags: api, php
publish: true
---

# \Kendo\UI\EditorImageBrowserSchemaModelFieldsSize

A PHP class representing the size setting of EditorImageBrowserSchemaModelFields.


## Methods

### field
The name of the field.
#### Parameters

##### $value `string`



#### Example 
    $size = new \Kendo\UI\EditorImageBrowserSchemaModelFieldsSize();
    $size->field('value');

### parse
Specifies the function which will parse the field value. If not set default parsers will be used.
#### Parameters

##### $value `\Kendo\JavaScriptFunction`



#### Example 
    $size = new \Kendo\UI\EditorImageBrowserSchemaModelFieldsSize();
    $size->parse(new \Kendo\JavaScriptFunction('function() { }'));
