# Self-citations analysis using sentence embeddings # 

The purpose of citation indexes and metrics is intended to be a measure for scientific innovation and quality for researchers, journals, and institutions. However, those metrics are often prone to abuse and manipulation by excessive and unethical self-citations induced by authors, reviewers, editors, or journals. Identifying whether there are or not legitimate reasons for self-citations is normally determined during the review process, where the participating parts may have intrinsic incentives, rendering the legitimacy of self-citations, after publication, questionable. In this paper, we conduct a large-scale analysis of journal self-citations while taking into consideration the similarity between a publication and its references. Specifically, we look into PubMed Central articles published since 1990 and compute similarities of article-reference pairs using sentence embeddings.  We examine journal self-citations with an aim to distinguish between justifiable and unethical self-citations.

## Repository ##

This repository includes:

- The [journal_stats.csv](Journal%20Stats/journal_stats.csv) provides the full list of journals (3886) with their average semantic similarity and ReLy score as described in the paper
- The [publication_stats.csv](Publication%20Stats/) provides the full list of publications (3959546) considered in this study with their average semantic similarity between references and ReLy score as described in the paper