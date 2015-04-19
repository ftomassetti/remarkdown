We use CommonMark + kramdown

## Headings

These are in order of priority the headings in rst

```
# with overline
-/* with overline
= no overline
- no overline
^ no overline
“ no overline
```

The will be mapped to # to ###### in order

Example:

```rst
=========
 rst2man
=========
```

becomes:
```markdown
# rst2man
```

## Links

Example:
```rst
`python <www.python.org>`_
```

Markdown:
```
[python](www.python.org)
```


## Tables