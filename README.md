### pybuilder
---
https://github.com/pybuilder/pybuilder

```py
from pybuilder.core import use_plugin
use_plugin("python.core")
use_plugin("python.unittest")
use_plugin("python.coverage")
use_plugin("python.distutils")
default_task = "publish"


from pybuilder.core import use_plugin
use_plugin("pypi:<< plgin namegoes here >>")

use_plugin("pypi:pybuilder_external_plugin_demo")
```

```sh
pip install pybuilder
pip install --pre pybuilder
```

```
```


