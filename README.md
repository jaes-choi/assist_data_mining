# x-mas-eve-2019
```python
from bs4 import BeautifulSoup
from urllib.request import urlopen

url = 'https://brunch.co.kr/@hklim/16'

html = urlopen(url)
soup = BeautifulSoup(html, 'html.parser')
```


```python
blocks = soup.find_all('p')
```
