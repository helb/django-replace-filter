django-replace-filter
=====================

https://djangosnippets.org/snippets/60/

```python
INSTALLED_APPS = (
…
    "replace_filter",
…
)
```

```
{% load replace %}
…
{{ foo|replace:"/old/new/" }}
```
