# Custom i18n redirect module

Fixed issue when someone tried to access "node/123" in EN but original node language is different. It will create duplications, **i18n_redirect** should solve this but patch is not merged.

# Installation
1. Turn off i18n_redirect module
2. Enable custom_i18n_redirect module
3. Clear cache

# Issues
- https://www.drupal.org/project/globalredirect/issues/1653194  
- https://www.drupal.org/node/1514166#comment-11657665
