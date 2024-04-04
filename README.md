# README

Code repository for Laura Moset Estruch's paper titled "Neología Semántica y Contexto: Un estudio de la detección de los neologismos semánticos tóxico, unicornio y hibernar usando corpus diacrónicos" for the Terminology, Neology and Society course at UPF (2024)

### Requirements

The code is written using Python 3.10 in Colab's version published on 2024-02-21. Thus, the author recommends also using Colab for easier and better performance.
You can access the original Colab with this [link](https://colab.research.google.com/drive/1xgduDZjQ_HIF9fz_xCfnNqvxyjH7TEw-?usp=sharing).

Packages required:
* Downloading the datasets:
   * gdown== 4.7.3
   * csv==1.0
* Preprocessing and tokenization:
   * re==2.2.1
   * spacy==3.7.4
      * spaCy trained pipeline: es_core_news_lg
* Counting frequency:
   * collections

### Data attribution
The data was obtained using Sketch Engine's corpora "Spanish Web 2011 (esTenTen11, Eu + Am)" and "Timestamped JSI web corpus 2021-22 Spanish".
The .csv files are automatically downloaded when the code is run using _gdown_ in Colab or using the _descargar\_csv.py_ file. 
>[!NOTE]
>If there is any problem with the download, please feel free to contact the author at laura.moset01@estudiant.upf.edu.

