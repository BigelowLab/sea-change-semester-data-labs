Lab 2 C: Working with Oceanographic Data in R Markdown
================

# R Markdown

You can create documents that have text, figures and R code all in the
same document using R Markdown. These R Markdown files (or R Notebooks -
more later) are really useful for reproducible science because you can
put all the information into one document in a clear, presentable way. I
do all my research using these - I think of them as lab books, I don’t
keep a pen and paper lab book anymore. And all the lab scripts I’ve
written for this course were done in R Markdown.

## What is Markdown?

(adapted from
[markdownguide.org](https://www.markdownguide.org/getting-started/))

Markdown is a lightweight markup language that you can use to add
formatting elements to plaintext text documents. Created by John Gruber
in 2004, Markdown is now one of the world’s most popular markup
languages.

Using Markdown is different than using a WYSIWYG (what you see is what
you get) editor. In an application like Microsoft Word, you click
buttons to format words and phrases, and the changes are visible
immediately. Markdown isn’t like that. When you create a
Markdown-formatted file, you add Markdown syntax to the text to indicate
which words and phrases should look different.

For example, to create **bold** text you would type
`**this text is bold**`.

To create your final document, you need to **render** your markdown
file.

## R Markdown and R Notebooks

In RStudio, you can create a R Notebook or a R Markdown file. In terms
of how you write or code in them, they are the same. The difference
comes in how they are rendered.

R Markdown files need to be **knitted**. When you knit a file, it runs
all the code chunks, and formats all your text. You can knit a R
Markdown file into a PDF or a html file or some other formats.

Whereas, a R Notebook file’s default output is HTML. This means you can
**Preview**, rather than knit, the file to render it. This is much
faster because it doesn’t run all the code, it just displays the output
from the last time the code was run.

To start either a R notebook or R markdown file, press the symbol on the
toolbar that has a green plus and white sheet of paper. Then select
either ‘R Notebook’ or ‘R Markdown’. In each case, the new file will
have default/example text and information that explains how to create
the file.

There’s lots of information online about R Markdown, check out the
[RStudio R Markdown
website](https://rmarkdown.rstudio.com/lesson-1.html), [this reference
sheet](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdfhttps://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf)
which shows examples of lots of different text formatting you might want
to do, and [this cheat
sheet](https://raw.githubusercontent.com/rstudio/cheatsheets/master/rmarkdown-2.0.pdf).

# Lab Assignment

Create an R Notebook which imports the DaRTS CTD data, and produces the
3 following figures:

1.  A temperature profile for Station 1 from the Cruise on Sept 11th
    2012. *Hint:* you’ll need to **filter** your data frame.

2.  Temperature profiles for all the Stations from the Cruise on Sept
    11th 2012, with all profiles on the same plot. *Hint:* you’ll need
    to convert the station numbers to **factors**.

3.  Profiles from all the stations for a cruise and variable of your
    choice.

Label all your axes and include the units.

Include a short introduction (a couple of sentences / short paragraph)
describing the DaRTS dataset (e.g. oceanographic time series from the
Damariscotta River between years XX and YY, measuring variables
ZZZZZZZ).

It’s up to you how to layout your notebook, but please include:

1.  At least two different sections with headers
2.  A list (e.g. of the variables in the data set, or the figures you
    are going to plot)
