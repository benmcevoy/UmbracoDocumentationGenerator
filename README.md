UmbracoDocumentationGenerator
=============================

Tool to help generate documentation for Umbraco builds.

uSync can pull out all document type definitions (amoung other things) as a set of XML files.

We project the document type to a model and then can template it out as an HTML file via T4.

A nice example of T4 for me as well.  Using @include to push all the logic out of the template and leave the actual .tt to just do the templating.
