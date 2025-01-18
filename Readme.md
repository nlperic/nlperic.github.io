---
title: Readme
...

- Create the html files by simply running

```python
% python jemdoc -c mysite.conf -o www/ *.jemdoc
python jemdoc.py -i ./jemdocs -o ./www -c mysite.conf

```

at the home directory.

- Solution to charset problem of CJK

> 1. generate the html files, now there may exist unrecognized characters;
> 2. recover the files to other enconding with special characters, for example, GBK; 
> 3. convert to the utf-8 encoding.

- Convert markdown files to html format

```
pandoc --standalone --css=jemdoc.css xxx.md -o xxx.html 
```
---
