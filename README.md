# doi2citation
Just a one-liner shell script to query the API available at [doi.org](https://doi.org) for the citation text for a DOI.

## Style
- The citation style defaults to `chicago-fullnote-bibliography`
- To use a different style, use the environment variable `DOI2CITATION_STYLE`
- Available styles can be found at http://data.crossref.org/styles

# Usage

``` shell
doi2citation 10.1111/tpj.14140
# Use MLA style instead
DOI2CITATION_STYLE=mla doi2citation 10.1111/tpj.14140
```

# See also
[DOI Content Negotiation](https://citation.crosscite.org/docs.html)
