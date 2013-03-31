# yaml4-sass

YAML4-Sass is the official Sass/Compass port of the CSS framework YAML, created and maintained by its developer Dirk Jesse.

YAML ist also availabe in a static CSS version, that can be downloaded at: <http://www.yaml.de>

## Recent Version
yaml4-sass: 4.1.0b

## Quick Start
You need to have [Node.js](http://nodejs.org/download/) and [Compass](http://compass-style.org/install/) installed. Run `npm install` once in the root directory of yaml4-sass.

* **compile once** `grunt` starts a single run to compile sass/scss files to CSS.
* **edit** `grunt watch` starts the watcher that recompiles your sass/scss files on every change.
* **build** `grunt build` compiles and optimizes all static YAML4 CSS files for release/production.

## Overview
The Sass port is built in a way that allows you to create a fully customized version of YAML's framework files.

The Sass port creates all CSS files in the following folders:

* demos/css/
* docs/assets/css/
* yaml/

Please keep in mind, that the /yaml/ folder also contains serveral JavaScript files. So, don't delete this folder, as it's content is not completely generated by Sass.

## Docs
Download or clone this project and open file "docs/index.html" in your browser.

## Licenses
### YAML under Creative Commons License (CC-BY 2.0)

The YAML framework is published under the Creative Commons Attribution 2.0 License (CC-BY 2.0), which permits
both private and commercial use (<http://creativecommons.org/licenses/by/2.0/>).

Condition: For the free use of the YAML framework, a backlink to the YAML homepage (<http://www.yaml.de>) in a
suitable place (e.g.: footer of the website or in the imprint) is required.

In general it would be nice to get a short note when new YAML-based projects are released. If you are highly
pleased with YAML, perhaps you would like to take a look at my Amazon wish list?
<https://www.amazon.de/gp/registry/wishlist/108Q0YYJ49UC2/>

### YAML under Commercial Distribution License (YAML-CDL)

If you are a commercial software developer and you want to release your software under a different license
than CC-BY 2.0, you may purchase commercial licenses. By purchasing commercial licenses, we offer you the
freedom to choose between the following license models.

- Project Related License, 59.50 EUR (incl. 19% taxes)
- General License, 119.00 EUR (incl. 19% taxes)
- OEM License, 599.00 EUR per anno (incl. 19% taxes)

Full license texts and contact information are available at: <http://www.yaml.de/license.html>

##TODO

* add variables to form-module and form-theme
* more flexible vertical rhythm generator
