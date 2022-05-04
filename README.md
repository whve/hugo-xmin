# HUGO XMIN

## *Keep it simple, but not simpler*

``` r
blogdown::new_site(theme = "whve/hugo-xmin") 
```

``` bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

           5 ./layouts/404.html
          12 ./layouts/_default/single.html
          20 ./layouts/_default/list.html
          13 ./layouts/_default/terms.html
           0 ./layouts/partials/foot_custom.html
           0 ./layouts/partials/head_custom.html
           9 ./layouts/partials/footer.html
          20 ./layouts/partials/header.html
          51 ./static/css/style.css
           7 ./static/css/fonts.css
         137 total

I can certainly further reduce the code, for example, by eliminating the CSS, but I believe a tiny bit of CSS can greatly improve readability. You cannot really find many CSS frameworks that only contain 50 lines of code.

[![Screenshot](https://github.com/yihui/hugo-xmin/raw/master/images/screenshot.png)](https://xmin.yihui.org)
