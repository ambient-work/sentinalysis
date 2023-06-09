# Sentilalysis


[![ambient-work - WFA3.0](https://img.shields.io/badge/ambient--work-Sentinalysis-2ea44f?style=for-the-badge&logo=github)](https://github.com/ambient-work/wfa3.0/)
[![Extrempty - Dev](https://img.shields.io/badge/Extrempty-Dev-89CFF0?style=for-the-badge&logo=telegram)](https://github.com/ambient-work/wfa3.0/)
[![Made with - Python](https://img.shields.io/badge/Made_with-Python-C0C2C9?style=for-the-badge&logo=python)](https://github.com/ambient-work/wfa3.0/)
[![in - Development](https://img.shields.io/badge/in-Development-ac3ccf?style=for-the-badge&logo=visualstudiocode)](https://github.com/ambient-work/wfa3.0/)



## overview
Sentilalysis is a collection of Jupyter notebooks that use popular sentiment analysis Python libraries to analyze text. The goal of this project is to provide a simple and accessible way to perform sentiment analysis using different tools and compare the results.

## Libraries used



| Library | Description | Colab Notebook |
| --- | --- | --- |
| [vaderSentiment](https://github.com/cjhutto/vaderSentiment) | A Python library for sentiment analysis | [![Open In Colab](https://img.shields.io/badge/Open%20in-Colab-orange.svg)](https://colab.research.google.com/drive/174X_S5SLDQNAFffOvQKYzVIY8dLRIHD_?usp=sharing) |
| [textblob](https://textblob.readthedocs.io/en/dev/) | A Python library for processing textual data | [![Open In Colab](https://img.shields.io/badge/Open%20in-Colab-orange.svg)](https://colab.research.google.com/drive/1fSb6gny8RlqcpaCWNDZjrN3HYFlO2dE9?usp=sharing) |
| [flair](https://github.com/flairNLP/flair) | A Python library for NLP tasks such as named entity recognition | [![Open In Colab](https://img.shields.io/badge/Open%20in-Colab-orange.svg)](https://colab.research.google.com/drive/1IIk1DtElZoQZTodhH40-k9fQ_lOLGuGG?usp=sharing) |
| [NLTK](https://github.com/flairNLP/flair) | A Python library for comprehensive natural language processing tasks | [![Open In Colab](https://img.shields.io/badge/Open%20in-Colab-orange.svg)](https://colab.research.google.com/drive/1FljbnD-iEw9eAPfa7blAVAJtEsAZJzDY?usp=sharing) |
| [Node-NLP](https://github.com/flairNLP/flair) | A Node.js package that provides natural language processing (NLP) capabilities. Like extracting meaning from text, perform sentiment analysis, etc | [![Open In Colab](https://img.shields.io/badge/Open%20in-Colab-cyan.svg)](https://colab.research.google.com/drive/19Cd1-jHMANOIfqP-6rW8UuVaHMRdmjnq?usp=sharing) |


## Usage
To run the notebooks, you will need to install the required libraries. You can do this by running the following command:

```
pip install -r requirements.txt
```
<sub>Use the latest python version</sub>

## Example

```python
analyzer = SentimentIntensityAnalyzer()
for sentence in sentences:
    vs = analyzer.polarity_scores(sentence)
    print("{:-<65} {}".format(sentence, str(vs)))
```


## Contributing
Contributions are welcome! If you would like to contribute to this project, please create a pull request with your changes.

## External Resources
- [Sentiment analysis with bert, on colab](https://colab.research.google.com/drive/1PHv-IRLPCtv7oTcIGbsgZHqrB5LPvB7S)
- [The Best Python Sentiment Analysis Package (+1 Huge Common Mistake)](https://towardsdatascience.com/the-best-python-sentiment-analysis-package-1-huge-common-mistake-d6da9ad6cdeb)

## License
This project is licensed under the terms of the [BANI license](LICENSE).

---

Created by [ambient-work](https://github.com/ambient-work)