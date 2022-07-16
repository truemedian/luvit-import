
# Luvit 3.0 Import

This is a Luvit 2.x library intended to replace the current require with a possible alternative for the future.

## Usage

Add to your dependencies with `lit install truemedian/import`. 

Then add the following code to the top of your luvit entrypoint (The file you pass to luvit on the commandline).

```lua
_G.require = require
module, import = require('import')(module)
```
