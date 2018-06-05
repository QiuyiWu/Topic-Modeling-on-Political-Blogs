# Topic-Modeling-on-Political-Blogs
Use different topic modeling approach on Political Blogs to see the performance of diverse methods. 

## Type of Models in Comparison
* General LDA
* Supervised LDA
* Relational Topic Model ([Jonathan Chang](http://proceedings.mlr.press/v5/chang09a/chang09a.pdf), [R package](https://cran.r-project.org/web/packages/lda/lda.pdf))
* Topic Link Block Model (Derek Owens-Oas)
* Poisson Factor Modeling ([Beta Negative Binomial Process Topic Model](http://people.ee.duke.edu/~lcarin/Mingyuan_PAMI_6.pdf))
* Dynamic Text Network Model ([Teague Henry et al.](https://arxiv.org/pdf/1610.05756.pdf))


* General LDA
* Supervised LDA 
* Relational Topic Model 
* Network Topic Model 
* Poisson Factor Modeling 
* Dynamic Topic Network Model

## Key Values in Cleaned Blog Posts
After preprocessing the text extracted from blog posts:
* dates: string of the given date in mm/dd/yy format
* domains: string of the blog website where post was found  (remove "www.")
* links: string of other websites occured in the post as hyperlinks  (sorted alphabetically)
* words: filtered words from raw text in the blog posts  (TFIDF variance threading used)
* rawText: direct content from blog posts  (remove short posts and duplicate posts )
* words_stem: stemmed words using Hunspell stemmer  (e.g., apples -> apple)
