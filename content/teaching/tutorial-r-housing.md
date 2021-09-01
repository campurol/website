+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = false  # Activate this widget? true/false
weight = 15  # Order that this section will appear.

title = "Tutorial Hedonic Analysis with R"
subtitle = ""
date = "2020-03-28"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  gradient_start = "DarkGreen"
  gradient_end = "ForestGreen"
  
  # Background image.
  # image = "image.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
  padding = ["20px", "0", "20px", "0"]

[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

### 👋 Welcome!
Welcome to the companion website of the R Tutorial. This website includes the tutorial R-Markdown files that runs an hedonic analysis on house prices using transaction data.
 
### Why R?
- 👉 It’s one of the most popular tools used for data analysis
- It can handle large amounts of data (unlimited!)
- It's perfect for unstructured data (Twitter, Facebook, News, Reedit, Linkedin, IMBD, etc)
- It makes some of the best pictures in the business
- It records every step of your analysis (easier **replicability**!)
- It has a huge online community of users/supporters

### What will we do in the tutorial?
We will get an introduction to R by following the steps recommended by the book "R for Data Science" (reference below). 
These are basic steps that anyone wishing to embark in a data analysis project should follow:
- **Import** (from a file, a database, a website, etc)
- **Tidy** (mainly clean and make it consistent)
- **Understand**: Transform -> Visualize -> Model -> Repeat ... (Graphs, Statistical Models, Machine Learning, etc)
- **Communicate**

### What should I do before the tutorial?
You can get ready for the tutorial by either
{{% callout note %}}
- Installing [R](https://www.r-project.org/) and [R Studio](https://www.rstudio.com/) in your own computer
- Or Signing-up in [RStudio Cloud](https://rstudio.cloud/) before the tutorial. It's free. It's easy. It's in the cloud. If you want, you can log in, create a project and start playing with RStudio. 
- Then, the day of the tutorial (or before if you have the time). Please login into your RStudio Cloud account, create a project and upload the tutorial files to your new project.

[**Tutorial Files**](https://www.dropbox.com/s/jzobvxovvenbw9w/rtutorial-realestate.zip?dl=1)

{{% /callout %}}



### Useful References
- Grolemund, G. and Wickham, H. (2017) "[R for Data Science](https://r4ds.had.co.nz/)", O'Reilly Media
- [R Markdown Cheasheet](https://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf)
- [Tidyverse](https://www.tidyverse.org): a collection of the most commonly used packages used in data science 
- [Documentation of ggplot2](https://ggplot2.tidyverse.org/index.html): package to make nice looking graphs 
- [Documentation of PivotTabler](https://github.com/cbailiss/pivottabler): package to make pivot tables 
- [Documentation of glmnet](https://web.stanford.edu/~hastie/glmnet/glmnet_alpha.html): package that fits generalizable linear models   
