# README

Code repository for Laura Moset Estruch's paper titled "Neología Semántica y Contexto: Un estudio de la detección de los neologismos semánticos tóxico, unicornio y hibernar usando corpus diacrónicos" for the Terminology, Neology and Society course at UPF (2024)

### Requirements

The code is written using Python in Colab's version published on 2024-01-29. Thus, the author recommend also using Colab for easier and better performance.
You can access the original Colab with this [link](https://colab.research.google.com/drive/1xgduDZjQ_HIF9fz_xCfnNqvxyjH7TEw-?usp=sharing).

Packages required:
* Downloading the datasets:
   * gdown
   * csv
* Preprocessing and tokenization:
   * re
   * spacy
      * es_core_news_lg
* Counting frequency:
   * collections

### Data
The txt files are automatically downloaded when the code is run using _gdown_. The data was obtained using Sketch Engine's corpora "Spanish Web 2011 (esTenTen11, Eu + Am)" and "Timestamped JSI web corpus 2021-22 Spanish".
>[!NOTE]
>If there is any problem with the download, please feel free to contact the author at laura.moset01@estudiant.upf.edu.

