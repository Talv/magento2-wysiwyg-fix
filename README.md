# Magento2 WYSIWYG media URLs fix

Fix for Magento 2.1 WYSIWYG embedding media with incorrect URLs - not transforming them into *media* tags.
Related issue: https://github.com/magento/magento2/issues/6138

> Magento finally fixed this bug in `2.1.8`. https://github.com/magento/magento2/pull/10131 \
> Thus this package is obsolete - unless you're using older version (such as `2.1.7` etc.)

## Installation

```
composer config repositories.talv/magento2-wysiwyg-fix vcs https://github.com/talv/magento2-wysiwyg-fix/
composer require talv/magento2-wysiwyg-fix
bin/magento module:enable Talv_WysiwygFix
bin/magento setup:upgrade --keep-generated
```
