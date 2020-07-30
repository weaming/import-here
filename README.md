# Import Here

`import` module from same directory.

## Usage

```python
from import_here import import_module_here, export_all

# import file as a module
lib = import_module_here("foo.bar.com.py", "lib", file=__file__)
# export the exported variables in the lib's scope into current module scope
export_all(lib, locals())
```
