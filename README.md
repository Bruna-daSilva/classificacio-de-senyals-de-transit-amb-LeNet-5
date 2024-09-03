# Classificació de senyals de trànsit amb LeNet-5 
by **Bruna da Silva**

### Preparació:

Primerament, he creat un [entorn virtual](https://docs.python.org/es/3.8/library/venv.html) amb les comandes següents:

    python3 -m venv .venv
    source .venv/bin/activate

He instal·lat les llibreries següents:

- numpy
- opencv-python
- scikit-learn
- matplotlib
- tensorflow

Per assegurar que tens les mateixes versions de les llibreries, instal·la el fitxer [requirements.txt](requirements.txt) amb el codi següent:

    pip install -r requirements.txt


### El dataset:

En aquest projecte es fa servi el dataset "German Traffic Sign Recognition Benchmark" (GTSRB), que pot ser descarregat a través de la web seguent: 
https://benchmark.ini.rub.de/gtsrb_dataset.html#Downloads

### Referències:

- [Traffic-Sign-Classifier-using-Deep-Learning-LeNet-5](https://github.com/vikasnataraja/Traffic-Sign-Classifier-using-Deep-Learning-LeNet-5)
- [traffic_signs_classification](https://github.com/AndriiGoz/traffic_signs_classification/blob/master/traffic_signs_classification_lenet5.ipynb)
