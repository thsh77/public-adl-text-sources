# Public ADL text sources

The [Archive for Danish Literature, ADL,](http://www.adl.dk/) comes to you via a collaboration between

* [Det Danske Sprog- og Litteraturselskab (DSL)](http://dsl.dk/)
* [Danish Royal Library](http://www.kb.dk)

As of writing, the corpus comprises 498 volumes with in total 165512
pages of Danish literature.  The whole corpus has been encoded using
TEI, but only about two-thirds of the pages have been subject to OCR
and text encoding. This repository contains all those texts. 

We also describe our data and particular our encoding practices. We
also give information on how we envisage submissions could be
structured.

* [The ADL work](work.md)
* [Connecting works with metadata](work-metadata.md)
* [Connecting text to facsimile](facsimile-text.md)
* [Submission of documents connecting text to facsimile](submission-facsimile-text.md)
* [Workflows and requirements for new documents](workflows.md)

## Contributing documents

Projects with relevant scope can contribute documents to ADL, provided the

* Copyright issues are resolved
* They are accepted by DSL and KB
* The TEI is valid XML

A contribution can be received by branch and pull request in github as
is the practice on GitHub.  If the contribution includes facsimiles
the TEI document should absolute URIs to uncompressed TIF or JPEG2000
image files via the TEI documents <pb/> elements.

Alternatively, the contribution can be submitted in the [BagIt format
(v0.97 or better)](https://tools.ietf.org/html/draft-kunze-bagit-14),
and hence include valid manifest files (site maps).


