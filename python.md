
### 1行 try catch pass [link](https://code.i-harness.com/ja/q/62bb1c)
```
from contextlib import suppress

with suppress(IDontLikeYouException, YouAreBeingMeanException):
     do_something()
```
---


### Python で多重ループを回避する [link](https://qiita.com/QUANON/items/bce7495be0e350911e66)
```
from itertools import product

years = range(2010, 2013)
integers = range(1, 3)
chars = ('a', 'b', 'c')

for year, i, char in product(years, integers, chars):
  print(year, i, char)
```
---

### logging handler [link](https://symfoware.blog.fc2.com/blog-entry-885.html)

### datetime [link](https://qiita.com/motoki1990/items/8275dbe02d5fd5fa6d2d)

