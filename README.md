# PoliMediaCRO-2025
Dataset for verification of results presented in "Large Language Models for Targeted Sentiment Classification Toward Political Entities in Media Texts" academic paper.

It contains 2 separate files:
1. **links.txt** file – contains all links of articles scraped from selected portals
2. **dataset.csv** file – contains extracted entities across 12 months with following columns
    - **month**: month when the article was published from which the given entity was extracted
    - **entity**: extracted named entity
    - **sentiment**: sentiment of the entity within a sentence from an article (values: _positive_, _negative_, _neutral_)
    - **portal**: portal containing article from which the given entity was extracted
    - **person**: determines whether the extracted entity is person or not (values: _1_ if it's person, _0_ otherwise)
