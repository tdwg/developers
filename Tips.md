# Tips

_List here tips and lessons learned while developing Biodiversity Informatics related project._

## Modified Preorder Tree Traversal for storing taxonomic information in a RDBMS

I quite often have to store and query large taxonomic trees in an relational database. The naïve approach of having a `taxon` table with a recursive `parent_id` foreign key doesn't often works, for performance reasons. 

If it appears the reads are much more frequent than the updates, I've had good experiences with a different table structure known as *Modified Preorder Tree Traversal*. The technique is described [here](https://gist.github.com/tmilos/f2f999b5839e2d42d751), and in many other places on the web.

If your project is web-based and uses the [Django framework](https://www.djangoproject.com/), you can implement and query this data structure very easily using [django-mptt](https://github.com/django-mptt/django-mptt).