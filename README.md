# Joint ACP and GdR RO Summer School 2017

### About 

This is the website of the [13th ACP Summer School](http://school.a4cp.org/summer2017) (ACPSS 2017).
    
It will be held September, 18-22th, 2017 on the [Porquerolles island]((www.porquerolles.com/)), France.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Copyright for portions of project ACPSS 2017 are held by 
Copyright (c) 2014 Oleh Zasadnyy, Vitaliy Zasadnyy
as part of project Zeppelin.

All other copyright for project ACPSS 2017 are held by
Copyright (c) 2017 Arnaud Malapert, Université Nice Sophia Antipolis.
All rights reserved.

#### Website based on the Project Zeppelin

[Project Zeppelin](https://github.com/gdg-x/zeppelin/) allows you to setup awesome GDG DevFest site in 5 minutes. 

Project is built on top of [Jekyll](http://jekyllrb.com/) - simple, blog-aware, static site generator. Jekyll also happens to be the engine behind GitHub Pages, which means you can use Jekyll to host your website from GitHub’s servers for free. [Learn more about Jekyll](http://jekyllrb.com/).

Template is brought by [GDG Lviv](http://lviv.gdg.org.ua/) team.


### Features
* Easy to setup
* Simple and responsive design
* Integrated speakers and sessions management
* SVG icons
* SEO friendly


### Quick-start guide
1. [Fork](https://github.com/arnaud-m/acpss2017) this repo
2. Clone locally
3. Update ```_config.yml``` 
4. Update ```_data``` 
5. Push changes to ```master``` branch
6. Enjoy your awesome ACPSS site at ```http://[your github name].github.io/acpss2017/```


## Local development

Check if you have [all requirements for local environment](http://jekyllrb.com/docs/installation/).
To install all development dependencies install [Bundler](http://bundler.io/).
```bash
    gem install bundler
``` 
and run next command from root folder:

```bash
  bundle install
```  

To start Jekyll run:
```bash
    jekyll serve -w
```
Site will be available at http://127.0.0.1:4000/acpss2017/ or http://localhost:4000/acpss2017/ (on Windows)

**NOTE:** in this mode all changes to html and data files will be automatically regenerated, but after changing ```_config.yml``` you have to restart server.

### Sass(Compass) support
**Note:** You need to install [Node.js](http://nodejs.org/download/)

To watch changes of `.sass` files and compile it to the `.css` on a fly change property `safe: true` to `safe: false` in `_config.yml`.
**Note: It works only on local machine, because GitHub runs Jekyll in `--save` [mode](https://help.github.com/articles/using-jekyll-with-pages/#configuration-overrides)**

Learn more about Sass development from [documentation](https://github.com/gdg-x/zeppelin/wiki/Sass-development).


### Resource optimizations (optional)

You can optimize images and minify css and javascript automatically (for now only on Windows).
But for Mac OS users available amazing tool - [imageoptim](https://imageoptim.com/). Thanks [@raphaelsavina](https://github.com/raphaelsavina) for link.
Optimize all images by running this script from `/automation/images/` folder:
```bash
    all_image_optimization.bat -d -jtran -pout -pquant -optip -gsicle -svgo
```

To minify CSS and JS run `minify_js.bat` (for Windows) and `minify_js.sh` (for Linux and MacOS) from `/automation/minifying/` folder:
```bash
    minify_js.bat
```

Learn more about available optimization options from [documentation](https://github.com/gdg-x/zeppelin/wiki/Resources-optimizations).

### Used libraries
* [Bootstrap](https://github.com/twbs/bootstrap)
* [Animate.css](https://github.com/daneden/animate.css)
* [Waves](https://github.com/publicis-indonesia/Waves)
* [jquery.appear](https://github.com/bas2k/jquery.appear)
* [jQuery countTo Plugin](https://github.com/mhuggins/jquery-countTo)
* [Typed.js](https://github.com/mattboldt/typed.js)
* [Sticky-kit](https://github.com/leafo/sticky-kit)


### Contributors
* Design and web development: [Arnaud Malapert](https://github.com/arnaud-m)
* Bug fixing and support: 

### License
Project is published under the [MIT license](https://github.com/arnaud-m/acpss2017/blob/master/LICENSE.txt). Feel free to clone and modify repo as you want, but don't forget to add reference to authors :)

### Credits
* Images of Porquerolles: [commons.wikimedia.org](https://commons.wikimedia.org/wiki/Category:Porquerolles)

