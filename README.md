# PoliMediaCRO-2025
Dataset for verification of results presented in "Large Language Models for Targeted Sentiment Classification Toward Political Entities in Media Texts" academic paper.

It contains 72,602 rows (number of non-distinct extracted named entities) with 4 columns:
- **link**: URL of article from which the named entity was extracted
- **entity**: extracted named entity
- **sentiment**: sentiment of the entity within a sentence from an article (values: _positive_, _negative_, _neutral_)
- **person**: determines whether the extracted entity is person or not (values: _1_ if it's person, _0_ otherwise)
