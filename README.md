# awesome-python-snippet
Beautiful python implementations that are worth collecting


### Check Palindromic string
``` python
def is_palindromic(s):
    return all(s[i] == s[~i] for i in range(len(s) / 2)) 
```
