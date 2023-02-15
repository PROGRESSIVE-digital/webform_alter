# webform_alter
Some changes to the webform, to better integrate select2 with the theme.

## How to include it in your Drupal project
Add the repository to your composer.json like this:
```json
"repositories": [
  {
      "type": "composer",
      "url": "https://packages.drupal.org/8"
  },
  {
    "type": "git",
    "url": "https://github.com/progressive-digital/webform_alter.git"
  }
]
```

And then require this module:
```bash
composer require 'progressive-digital/webform_alter:^1.0'
```
