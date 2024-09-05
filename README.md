# Classificació de senyals de trànsit amb LeNet-5 
 by **Bruna da Silva**

---
### Preparació:

Primerament, he creat un [entorn virtual](https://docs.python.org/es/3.8/library/venv.html) amb les comandes següents:

    python3 -m venv .venv
    source .venv/bin/activate

He instal·lat les llibreries següents:

- [**numpy**](https://numpy.org/): Permet treballar amb arrays, que representen conjunts d'un mateix tipus de dades amb diverses dimensions, i manipular-les fàcilment i ràpidament. Ho farem servir per manipular les nostres dades; les imatges i les seves etiquetes.
- [**opencv-python**](https://opencv.org/): És una llibreria que serveix per efectuar tasques de visió per computador, processament d'imatges i machine learning. Ho farem servir sobretot per carregar imatges, canviar la seva mida i convertir-les a RGB.
- [**scikit-learn**](https://scikit-learn.org/stable/): Proporciona múltiples eines de machine learning. Ho farem servir per separar les dades en diferents conjunts i manipular-los.
- [**matplotlib**](https://matplotlib.org/): Permet crear gràfics i visualitzacions. Servirà per mostrar algunes de les nostres imatges i prediccions.
- [**tensorflow**](https://www.tensorflow.org/): Serveix per construir i entrenar models de deep learning. Ho farem servir per construir el nostre model.

Per assegurar que tens les mateixes versions de les llibreries, instal·la el fitxer [requirements.txt](requirements.txt) amb el codi següent:

    pip install -r requirements.txt

---
### El dataset:

En aquest projecte es fa servi el dataset "German Traffic Sign Recognition Benchmark" (GTSRB), que pot ser descarregat a través de la web següent: 
https://benchmark.ini.rub.de/gtsrb_dataset.html#Downloads

---
### Referències:

- [Traffic-Sign-Classifier-using-Deep-Learning-LeNet-5](https://github.com/vikasnataraja/Traffic-Sign-Classifier-using-Deep-Learning-LeNet-5)
- [traffic_signs_classification](https://github.com/AndriiGoz/traffic_signs_classification/blob/master/traffic_signs_classification_lenet5.ipynb)
