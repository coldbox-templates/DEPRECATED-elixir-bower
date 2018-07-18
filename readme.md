# DEPRECATED TEMPLATE

This template has been deprecated, please use the (Elixir Template)[https://github.com/coldbox-templates/elixir] instead.

# Elixir + Bower Template

This advanced template leverages (ColdBox Elixir)[https://github.com/ColdBox/elixir] and Bower for asset management and compilations.  You can place all your static assets in the `resources/assets` folder and Elixir will combine, version, copy, and even babelify your code to their appropriate location in the `includes` folder.

Please check out the ColdBox Elixir documentation for further information: https://github.com/ColdBox/elixir/wiki

## Included Bower Dependencies
* Bootstrap
* jQuery

## License
Apache License, Version 2.0.

## Important Links

Source Code
- https://github.com/coldbox-templates/elixir

## Quick Installation

This template includes several components which each need to be installed to build up the stack.

First, review the `box.json` which leverages [CommandBox](http://www.ortussolutions.com/products/commandbox) for its dependencies.  Type:

```
box install
```

This will setup all the needed dependencies for each application template.

You can then type:

```
box server start
```

And run the application.

## ColdBox Elixir Installation

You will find a `package.json` and a `Gulpfile.js` in the root of this template. You can install ColdBox elixir by typing

```
npm install
```

Just make sure that you have [Gulp](http://gulpjs.com/) and [Bower](https://bower.io/) installed globally as well: `npm install -g gulp bower`.  Then a `node_modules` folder will be created will all the needed dependencies for ColdBox Elixir.  

To download all the javascript dependencies, type:

```
bower install
```

You can then just run `gulp` for asset combination and management.  Run `gulp --production` so it can do minification of assets as well. Run `gulp watch` for starting watchers in all ColdBox convetions for changes and asset recompilation.

---
 
###THE DAILY BREAD
 > "I am the way, and the truth, and the life; no one comes to the Father, but by me (JESUS)" Jn 14:1-12
