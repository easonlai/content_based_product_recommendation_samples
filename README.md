# Content Based Product Recommendation Samples

The sample code repository leverages [Azure Text Analytics](https://docs.microsoft.com/en-us/azure/cognitive-services/language-service/key-phrase-extraction/quickstart?pivots=programming-language-python) to extract key phrases from the product description as additional product features. And perform text relationship analysis with [TF-IDF (Term Frequency – Inverse Document Frequency)](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) vectorization and [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity) for product recommendation.

* azure_text_analytics_key_phrase_extract_demo.ipynb <-- Read product descriptions and pass them to Azure Text Analytics to extract key phrases.
* content_based_product_recommendation_sample_1.ipynb <-- Perform text relationship analysis with [TF-IDF (Term Frequency – Inverse Document Frequency)](https://en.wikipedia.org/wiki/Tf%E2%80%93idf) vectorization and [Cosine Similarity](https://en.wikipedia.org/wiki/Cosine_similarity) for product recommendation
* .\data\data_v2.csv <-- Origional sample dataset.
* .\data\data_v3a.csv <-- Curated dataset after key phrased extraction.
* .\data\data_v3b.csv <-- Curated dataset after key phrased extraction and basic data cleaning.

Enjoy!