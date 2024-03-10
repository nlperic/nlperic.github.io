---
title: Readme
...

- Create the html files by simply running

```python
python jemdoc -c mysite.conf -o www/ *.jemdoc
```

at the home directory.

- Solution to charset problem of CJK

> 1. generate the html files, now there may exist unrecognized characters;
> 2. recover the files to other enconding with special characters, for example, GBK; 
> 3. convert to the utf-8 encoding.

- Convert markdown files to html format

```
pandoc source.md -o destination.html --template=easy_template.html
```