# plaga
A WordPress starter theme based on Timber library and Bootstrap. (Forked from [Timber Starter Theme](http://github.com/Upstatement/timber-starter-theme))

Features
---
- Based on Timber library. 
- Uses Bootstrap and is responsive 
- Uses Less 
- Uses lessphp compiler

Theme Prerequisites
---
Timber-library WordpPress plugin. Get it from [here](https://wordpress.org/plugins/timber-library/) or [here](https://github.com/jarednova/timber)

Configure for development
---

- Clone the repo in to the themes directory of your development WordPress installation.

    `git clone https://github.com/sevir/plaga.git your-theme-name`
    
- Change to the `your-theme-name` directory
- Remove the `.git` directory and run `git init` to initialize your own git repo
- Open up `style.css` and modify theme name and other details to your liking
- Execute in command line less compiler

  `bin/less.php.phar -w --compress less/site.less css/site.less`

Happy theming y'all!!
