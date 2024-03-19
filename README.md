# pith-pack-toastr
Pack Toastr for Pith front-end

-------

# About

This project packs Toastr so that it can be used on the front-end with the Pith Framework.

For info on Toastr, see https://codeseven.github.io/toastr/, and the demo at https://codeseven.github.io/toastr/demo.html.


For info on Pith, see the Pith website at https://pith-framework.org/

# Install

Install to an existing Pith Framework project

Use Composer to install pack to the `vendor` folder.
```bash
php composer.phar require pith-front/pith-pack-toastr
```

Add new route to your Route List:

```php
public array $routes = [
    // Other routes....
    // ...
    
    // Add route to call Toastr resources from
    ['route', 'GET', '/resources/vendor/library/toastr/{filepath:.+}', '\\PithFront\\PithPackToastr\\ToastrResourceRoute'],
];
```

-------------


# Licensing Info

### Toastr
- Toastr 2.1.4 *(Needs jquery to work)*
- MIT License
- Copyright © 2012-2014 Hans Fjällemark, John Papa & Tim Ferrell. Copyright (c) 2012-2017 Toastr Maintainers (Current maintainers are John Papa and Tim Ferrell) 
- Authors: John Papa, Hans Fjällemark, and Tim Ferrell. 
- ARIA Support: Greta Krafsig.
- Project: https://codeseven.github.io/toastr/
- Demo: https://codeseven.github.io/toastr/demo.html 
- Repo: https://github.com/CodeSeven/toastr



### pith-pack-toastr
- pith-pack-toastr
- The MIT License (MIT)
- Copyright (c) Ian Maurmann
- Link: https://github.com/pith-front/pith-pack-toastr
