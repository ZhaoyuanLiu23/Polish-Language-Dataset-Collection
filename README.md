# Polish Language Datasets Collection

## Introduction

This repository contains a curated metadata collection of publicly available Polish language datasets.

It is designed to help NLP researchers, linguists, and students quickly locate resources for various tasks such as text classification, named entity recognition, sentiment analysis, machine translation, question answering, and other Polish NLP research tasks.

## Key Metadata Fields

- **Dataset Name**: The official name of the resource.
- **Verified Dataset URL**: Valid dataset address link (manually verified for accessibility).
- **Dataset URL from Citing/Cited Papers**: Dataset links referenced in related academic papers (may include archived or alternative sources).
- **Modality**: The type of data (e.g., Text, Speech, Multimodal).
- **Tasks**: Applicable NLP tasks (comma-separated for multi-task support).
- **Dataset Description**: A detailed summary of the dataset's content, scale, and collection method.

## Data Access

The complete dataset collection is provided in:

- `Polish-Language-Dataset-Collection.csv`

Tip: Click on the CSV file above to view the full, searchable table directly in GitHub.

## Data Preview

Below is a preview of the first 5 datasets included in the collection:

| Dataset Name | Verified Dataset URL | Dataset URL from Citing/Cited Papers | Modality | Tasks | Dataset Description |
|---|---|---|---|---|---|
| **Leyzer** | https://github.com/CLARIN-PL/Leyzer | https://doi.org/10.18778/0867-6356.2021.45 | Text | Named Entity Recognition, Historical Text Analysis | A morphosyntactically annotated corpus of Polish historical texts from the 16th to 19th centuries, focusing on religious and literary works. Contains over 2 million tokens with detailed linguistic annotations. |
| **KGr10** | https://clarin-pl.eu/dspace/handle/11321/771 | https://doi.org/10.18778/0867-6356.2012.01 | Text | Text Classification, Topic Modeling | A corpus of modern Polish texts covering 10 thematic categories (e.g., politics, science, culture). Includes 10,000 documents with manual topic labels, suitable for benchmarking text categorization models. |
| **PSC** | https://github.com/ipipan/polish-sentiment-corpus | https://doi.org/10.18653/v1/P19-1483 | Text | Sentiment Analysis, Emotion Classification | A Polish sentiment corpus with 5,000 user-generated texts (reviews, forum posts) labeled for positive/negative sentiment and 5 basic emotions (joy, sadness, anger, fear, surprise). |
| **ParCor** | https://clarin-pl.eu/dspace/handle/11321/664 | https://doi.org/10.18778/0867-6356.2018.38 | Text | Paraphrase Detection, Semantic Similarity | A dataset of Polish paraphrase pairs, including 3,000 manually annotated sentence pairs labeled as "paraphrase" or "non-paraphrase". Used for evaluating semantic similarity models in Polish. |
| **PolEmo2.0** | https://github.com/sdadas/polish-nlp-resources#polemo20 | https://doi.org/10.18653/v1/2020.lrec-1.827 | Text | Sentiment Analysis, Emotion Recognition | An extended Polish sentiment and emotion dataset with 10,000 product and movie reviews. Annotations include 4 sentiment categories (positive, negative, neutral, mixed) and 6 emotion labels. |

*(Please download the `Polish-Language-Dataset-Collection.csv` file to view the complete list of datasets.)*

## Notes

- **URL Validity**: "Verified Dataset URL" is updated quarterly; if a link is invalid, check "Dataset URL from Citing/Cited Papers" for alternative access paths.
- **Encoding Requirement**: The CSV file uses UTF-8 encoding to ensure correct display of Polish special characters (ą, ć, ę, ł, ń, ó, ś, ź, ż).
- **Usage Compliance**: This metadata collection provides links to external datasets—always comply with the original dataset’s license terms (e.g., non-commercial use restrictions) when downloading and using the actual data.
- **Manual Verification**: A small number of entries may require additional manual checks (e.g., archived links); refer to the dataset’s original source for the latest updates.
