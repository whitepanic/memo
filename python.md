
- 1行 try catch pass [参考](https://code.i-harness.com/ja/q/62bb1c)
```
from contextlib import suppress

with suppress(IDontLikeYouException, YouAreBeingMeanException):
     do_something()
```
