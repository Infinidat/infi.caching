Overview
========
infi.caching encapsulates the caching mechanisms used in various Infinidat projects.
This project was splitted from infi.pyutils.lazy, while the latter is being phased out of use.

Usage
-----
Add infi.caching to the buildout.cfg file of your project.
Import various mechanisms into your code and use them.

```bash
# add infi.caching to buildout.cfg
projector requirements add infi.caching
```

```python
# use infi.caching mechanisms in your project
from infi.caching import cached_function
@cached_function
def sample_cached_function(number):
    return number
```

