# VKRB

## Материалы к защите

* Общие:
  * [Презентация](https://docs.google.com/presentation/d/1MzOalJdO02TUsW7RhA_qUI1lNIABO-QP/edit?usp=sharing&ouid=102555644707355348645&rtpof=true&sd=true)
  * [Текст выступления](https://docs.google.com/document/d/1qeGsBrGCw789F94dXFAGsD1qD3lXg9rw/edit?usp=sharing&ouid=102555644707355348645&rtpof=true&sd=true)
  * [Текст ВКР](https://docs.google.com/document/d/1GGQzMAUKQ98SWJiZdp8ueUtoRA5Dpgul/edit?usp=sharing&ouid=102555644707355348645&rtpof=true&sd=true)
  * [Ссылка на архив с эмбеддингами](https://drive.google.com/file/d/1M5eB7x7Opa-lQe9ppgbUSv2q7BGmfVZn/view?usp=sharing)
  * [Ссылка на сайт с архивом GloVe](https://nlp.stanford.edu/projects/glove/)
  

## Запуск ноутбуков

Чтобы начать обучение моделей, нужно выбрать в папке /ml/ конкретный ноутбук models_`N`.ipynb (где `N` - нужный эмбеддинг) с нужным эмбеддингом: 50, 100, 200, 300

В папке /ml/ также находится ноутбук preprocessing.ipynb с функциями предобработки этого датасета

В папке /ml/nlp/ должны лежать glove.6B.`N`d.txt (где `N` - нужный эмбеддинг), датасет my_dataset.csv и полученные после предобработки full_description.txt (текст) и labels.txt (метки)
