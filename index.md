## Testing

Link to [repo](https://github.com/rcavalcante/rcavalcante.github.io).

### Start from markdown

* Link to rendered `html`: [Module02_QC.md](./html/Module02_QC.html)

```r
render('Module02_QC.md', output_dir = 'html')
```

### Start from rmarkdown

* Link to `Rmd`: [Module08_DESeq2DE.Rmd](./Module08_DESeq2DE.Rmd)
* Link to rendered `html`: [Module08_DESeq2DE.md](./html/Module08_DESeq2DE.html)

```r
# Remove keep_md: true in header
render('Module08_DESeq2DE.Rmd', output_dir = 'html')
```
