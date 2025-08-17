## Определение текста, поддельный или нет.

Задание взято с сайта [kaggle](https://www.kaggle.com/competitions/fake-or-real-the-impostor-hunt/submissions)

### Задача

Необходимо определить из двух текстов настоящий.   
В обучающей выборке 95 пар, в тестовой - 1068 пар.   
Для измерения качества модели используется метрика accuracy.

### Решение

1. Прочитал файлы и собрал датасеты.   
2. С помощью модели BERT перевел тексты в эмбеддинги.    
3. Обработал эмбеддинги с помощью PCA и обучил на них RandomForest.
4. Качество на тестовой выборке 0.88

### Описание файлов

>__main.ipynb__ - описание текстов, обучение и предсказание модели.   
__requirements.txt__ - список используемых библиотек.   
__preds.csv__ - предсказания модели.

### Библиотеки

<div id="badges">
  <img src="https://img.shields.io/badge/pandas-black?style=for-the-badge&logo=pandas"/>
  <img src="https://img.shields.io/badge/numpy-black?style=for-the-badge&logo=numpy"/>
  <img src="https://img.shields.io/badge/matplotlib-black?style=for-the-badge&logo=matplotlib"/>
  <img src="https://img.shields.io/badge/seaborn-black?style=for-the-badge&logo=seaborn"/>
  <img src="https://img.shields.io/badge/sklearn-black?style=for-the-badge&logo=scikit-learn"/>
  <img src="https://img.shields.io/badge/pytorch-black?style=for-the-badge&logo=pytorch"/>
  <img src="https://img.shields.io/badge/transformers-black?style=for-the-badge&logo=transformers"/>
</div>
