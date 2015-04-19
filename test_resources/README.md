The basic idea is to generate documentation from a document in rst and one in markdown,
then compare the results.

* Redirecting.txt : example in rst
* Redirecting.md  : equivalent in MD

## Generate HTML

Install docutils:

```
pip install docutils
```

Run docutils on Redirecting.txt

```
rst2html.py Redirecting.txt > Redirecting_from_rst.html
```

Run remarkdown on Redirecting.md

```
cm2html test_resources/Redirecting.md > test_resources/Redirecting_from_md.html
```

Are they the same?