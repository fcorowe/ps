This is a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). 

Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)".

Compile gitbook
> bookdown::render_book('index.Rmd', 'bookdown::gitbook')

Compile pdf
> bookdown::render_book('index.Rmd', 'bookdown::pdf_book')

Compile
> bookdown::render_book('index.Rmd', bookdown::gitbook(lib_dir = 'libs'))

Compile pdf
> bookdown::render_book('index.Rmd', bookdown::pdf_book(keep_tex = TRUE))

You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

You can find the preview of this example at https://bookdown.org/yihui/bookdown-demo/.
