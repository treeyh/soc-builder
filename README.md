# 云海代码生成器

纯前端模板代码生成器，基于json定义的模板构造。

模板参考 [template.json](assets/resources/template.json)

## 说明

### 模板结构

模板为四层结构 `TemplateSeries` -> `TemplateGroup` -> `TemplateSet` -> `TemplateItem`.

### 模板占位符

变量占位符使用 `{{变量名}}` 定义. 模板占位符使用 `{#变量名#}` 定义。

### 模板code

同级的code需要唯一不允许重复，code不能含除“_”外的特殊字符。

### 模板参数说明

如果参数不填，默认参数值会从剪贴板中取值。
