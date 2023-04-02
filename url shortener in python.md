# URL Shortener in Python Project


```python
pip install pyshorteners
```

    Requirement already satisfied: pyshorteners in c:\users\91630\anaconda3\lib\site-packages (1.0.1)
    Requirement already satisfied: requests in c:\users\91630\anaconda3\lib\site-packages (from pyshorteners) (2.27.1)
    Requirement already satisfied: charset-normalizer~=2.0.0 in c:\users\91630\anaconda3\lib\site-packages (from requests->pyshorteners) (2.0.4)
    Requirement already satisfied: certifi>=2017.4.17 in c:\users\91630\anaconda3\lib\site-packages (from requests->pyshorteners) (2021.10.8)
    Requirement already satisfied: idna<4,>=2.5 in c:\users\91630\anaconda3\lib\site-packages (from requests->pyshorteners) (3.3)
    Requirement already satisfied: urllib3<1.27,>=1.21.1 in c:\users\91630\anaconda3\lib\site-packages (from requests->pyshorteners) (1.26.9)
    Note: you may need to restart the kernel to use updated packages.
    


```python
import pyshorteners
url=input("Enter the url:")
def shortenurl(url):
    s=pyshorteners.Shortener()
    print(s.tinyurl.short(url))
shortenurl(url)
```

    Enter the url:https://www.thepythoncode.com/topic/using-apis-in-python
    https://tinyurl.com/y29hyjqq
    


```python

```


```python

```


```python

```
