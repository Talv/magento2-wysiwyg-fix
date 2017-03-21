# Magento2 WYSIWYG media URLs fix

Fix for Magento 2.1 WYSIWYG embedding media with incorrect URLs - not transforming them into *media* tags.
Related issue: https://github.com/magento/magento2/issues/6138

## Installation

```
composer config repositories.talv/magento2-wysiwyg-fix vcs https://github.com/talv/magento2-wysiwyg-fix/
composer require talv/magento2-wysiwyg-fix
bin/magento module:enable 
bin/magento setup:upgrade --keep-generated
```