

repo hosting git page: https://shu251.github.io/sarah-hu/

#  Quarto website


Initial instructions: https://quarto.org/docs/websites/
in terminal
```
quarto create-project mysite --type website
```

File navigation

```_quarto.yml```: set up and navigation doc 

Set up each page with a .qmd document. Select Render and it will populate ```docs``` directory. Launch git page from this directory.

When adding new pages add .qmd file to render list at the top of _quarto.yml

Set up git page to /docs

## Themes

Set to built in 'minty' theme, output to ```custom.scss```.

