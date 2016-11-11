# SearchAnalysisForOutdoorWebSiteQueries

## Background
Client has a log of all keyword searches that have been submitted to their outdoors site for years.

The search results include a number of semicolon-separated columns, but the only data column of interest right now are the search query terms submitted by site users.

Each search query submission is a single string of one or more space-separated words.

Client already has a set of lists of the names of Towns and other identifying categories.  They would like to know the frequency (proportion) of searches that:
- are one or another type of {rivers, towns, trips or runs} e.g. "ohio" = {river} [assuming no word exists in > 1 list/category]
- for each category, which list entry is most frequently requested e.g. "colorado" is the most frequently-searched river
- only request one type of data (only strings that are included in the category lists) vs. those requests that include filtering terminology (e.g. "x river" vs "x river rafting")
