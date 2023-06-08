# Data Science Course Material

This repository contains a collection of all the data science course slides. 

Check out the jupyter book side [here](https://curly-adventure-y24rglw.pages.github.io/).


## Costumize
In order to link `.css`-file to a jupyter notebook do one of the following:
* `rise.css` gets automaticly loaded if it is in the same directory as the notebook. In case of changes in the css-file, you need to either restart the kernel or reload the notebook.
* A `css`-file gets automaticly loaded if it has the same name of the notebook and is in the same directory as the notebook. In case of changes in the css-file, you need to either restart the kernel or reload the notebook.
* You can load any `.css`-file with the fellowing command as the first cell of the notebook:
```html
<link rel="stylesheet" href="path-to-css/costumize.css"/>
```

Resourses:

[RISE documentation](https://rise.readthedocs.io/en/stable/customize.html#adding-custom-css)

[RISE github repo with examples](https://github.com/damianavila/RISE/blob/master/doc/customize.md)