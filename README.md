# blankRmd

This is a R package created on 20190627. Installing this package will create a Rmarkdown template that only contains the setting chunk from the default Rmarkdown file. This saves about 5 seconds for every Rmarkdown file created because one does not have to delete everything thereafter. 

## Installation
This package depends on Rmarkdown (obviously). A simple way to install is through ` devtools::install_github("liutiming/blankRmd")`. This requires you to have `devtools`, which is a useful development package by Hadley and can be installed by `install.packages("devtools")`. This package is not published on CRAN because I highly doubt the maintainers will let me publish a package without a function (and more reason below).

## Development notes:
In terms of simplicity, it should not be an independent R package because it really does not do much. An ideal situation is that Rmarkdown package itself provides such a template or the default Rmarkdown file is just a blank page. 

However, if something more is to be done with this package, it will be to add a function that creates a blank Rmarkdone file in the folder. Currently a user still has to move to the template menu and find this template.
