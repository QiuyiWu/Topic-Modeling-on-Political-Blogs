# Topic Modeling on Political Blogs
Use different topic modeling approaches on Political Blogs to see the performance of diverse methods. 

## Type of Models in Comparison
* General LDA ([David Blei et al.](https://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf))
* Supervised LDA ([David Blei and Jon McAuliffe](https://proceedings.neurips.cc/paper/2007/file/d56b9fc4b0f1be8871f5e1c40c0067e7-Paper.pdf))
* Relational Topic Model ([Jonathan Chang](http://proceedings.mlr.press/v5/chang09a/chang09a.pdf), [R package](https://cran.r-project.org/web/packages/lda/lda.pdf))
* Topic Link Block Model ([Derek Owens-Oas](https://dukespace.lib.duke.edu/dspace/bitstream/handle/10161/16902/OwensOas_duke_0066D_14551.pdf?sequence=1))
* Poisson Factor Modeling ([Beta Negative Binomial Process Topic Model](http://people.ee.duke.edu/~lcarin/Mingyuan_PAMI_6.pdf))
* Dynamic Text Network Model ([Teague Henry et al.](https://arxiv.org/pdf/1610.05756.pdf))

## Key Values in Cleaned Blog Posts
After preprocessing the text extracted from blog posts:
* dates: string of the given date in mm/dd/yy format
* domains: string of the blog website where post was found  (remove "www.")
* links: string of other websites occured in the post as hyperlinks  (sorted alphabetically)
* words: filtered words from raw text in the blog posts  (TFIDF variance threading used)
* rawText: direct content from blog posts  (remove short posts and duplicate posts )
* words_stem: stemmed words using Hunspell stemmer  (e.g., apples -> apple)
