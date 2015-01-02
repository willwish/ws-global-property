ws-global-property
============

## Description
This is an element providing global space to store variable. It's developed to store the variable used across pages in [app-router](https://github.com/erikringsmuth/app-router);
When the element is crated, it will get variable from global level . If it is not exist, the default value will be applied.

## Bind global property
```html
<ws-global-property namespace="{{namespace}}" scope="{{scope}}" propertyName="pageNum" value="{{pageNum}}" defaultValue="0"></ws-global-property>
```