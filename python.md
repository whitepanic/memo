
### 1行 try catch pass [参考](https://code.i-harness.com/ja/q/62bb1c)
```
from contextlib import suppress

with suppress(IDontLikeYouException, YouAreBeingMeanException):
     do_something()
```
---


### Python で多重ループを回避する [参考](https://qiita.com/QUANON/items/bce7495be0e350911e66)
```
from itertools import product

years = range(2010, 2013)
integers = range(1, 3)
chars = ('a', 'b', 'c')

for year, i, char in product(years, integers, chars):
  print(year, i, char)
```
---

### Python logging handler [link](https://symfoware.blog.fc2.com/blog-entry-885.html)
