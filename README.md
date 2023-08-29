# resume

Uses [`resumed`](https://github.com/rbardini/resumed) to generate HTML from a JSON file. To install run

```
npm install -g resumed jsonresume-theme-elegant jsonresume-theme-full
```

For updating the site on Pages using theme Elegant:

```
resumed render resume.json --theme jsonresume-theme-elegant -o index.html
```

For creating a version suitable for PDF printing using theme Full:

```
resumed render resume.json --theme jsonresume-theme-full -o forpdf.html
```
