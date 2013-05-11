# Require-Dust

### [RequireJs](http://requirejs.org/) plugin for [Dust.js](http://linkedin.github.com/dustjs/) ###

---

## Motivation ##
Tried [dustjs-requirejs-plugin](https://bitbucket.org/manuel_martin/dustjs-requirejs-plugin) but could not get it to work with requirejs v2, also didn't like the fact that it puts the entire dust.js source code as part of the plugin. This plugin takes the advantage of AMD and loads dust.js as a module.

## Features ##
- works the same way as [require-cs](https://github.com/jrburke/require-cs)
- pre-compile as part of requirejs optimization
- exclude plugin logic once optimized (using requirejs "stubModules" feature in v2.0.0+)
- Works perfectly with the r.js optimizer.

---

## License ##
[WTFPL](http://sam.zoy.org/wtfpl/)

---
