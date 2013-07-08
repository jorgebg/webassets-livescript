[webassets](https://webassets.readthedocs.org) filter for [livescript](http://livescript.net/)

Installation:
```bash
pip install webassets-livescript
```

Usage:
```python
#...
from webassets_livescript import LiveScript

environment.register('js', 'app.ls', filters=(LiveScript,), output='js/app.js')
```