# Queste theme

[Bootstrap 5](https://www.drupal.org/project/bootstrap5) subtheme.

## Development.

### CSS compilation.

Prerequisites: install [sass](https://sass-lang.com/install).

To compile, run from subtheme directory:

````bash
sass scss/style.scss css/style.css && sass scss/ck5style.scss css/ck5style.css
````

#### Add to composer repositor

````bash
composer config repositories.queste vcs https://github.com/kainuk/queste.git
````
