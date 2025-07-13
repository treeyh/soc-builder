# 云海代码生成器

纯前端模板代码生成器，基于json定义的模板构造。

模板参考 [template.json](assets/resources/template.json)

模板为四层结构 `TemplateSeries` -> `TemplateGroup` -> `TemplateSet` -> `TemplateItem`.

变量占位符使用 `{{变量名}}` 定义. 模板占位符使用 `{#变量名#}` 定义。

页面基于模板动态生成。