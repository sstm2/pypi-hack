# pypi-hack

Using github to host problematic pip packages. Created 2023-03-15 to deal with a broken 
version of lerc-4.0.0 that was pushed out. In the future we can probably put our hacked 
version of streamlit-aggrid and other problem pip packages here.

# To use

1. Put the .tar.gz here
2. Change your reference in requirements.txt to be something like: 
```
streamlit-aggrid @ https://github.com/sstm2/pypi-hack/blob/main/streamlit-aggrid-0.3.3+s2.tar.gz?raw=true
```
    - Replace streamlit-aggrid with your package name
    - Replace streawmlit-aggrid-0.3.3+s2.tar.gz with your gzip tarball

