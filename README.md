# Links-database
its an simple database for your program
# how to use?
first, you need to download 1 of them\
if you downloaded links.txt:\
type this:\
```python
with open('links.txt','r') as fp:
    links = fp.split('/')
```
Else, you downloaded the links.pkl:\
```python
import pickle
with open('links.pkl','rb') as fp:
    links = pickle.load(fp)
```
