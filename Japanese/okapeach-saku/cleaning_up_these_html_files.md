Put return characters in between all the tags that are on the same line:

```
:%s/></>\r</g
```

Delete everything between the `<body>` tag and the `<article>` tag.
Similarly delete everything between `</article>` and `</body>`.
Then re-indent everything:

```
gg=G
```

