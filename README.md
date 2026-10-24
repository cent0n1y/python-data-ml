<div align="center">

# Python · Data · ML

**Нейросети на PyTorch, оптимизация Python-кода и обработка больших данных на Dask**

![Python](https://img.shields.io/badge/Python-0d0d0d?style=flat-square&logo=python&logoColor=c6ff00)
![PyTorch](https://img.shields.io/badge/PyTorch-0d0d0d?style=flat-square&logo=pytorch&logoColor=c6ff00)
![Keras](https://img.shields.io/badge/Keras-0d0d0d?style=flat-square&logo=keras&logoColor=c6ff00)
![Dask](https://img.shields.io/badge/Dask-0d0d0d?style=flat-square&logoColor=c6ff00)
![Numba](https://img.shields.io/badge/Numba-0d0d0d?style=flat-square&logo=numba&logoColor=c6ff00)
![pandas](https://img.shields.io/badge/pandas-0d0d0d?style=flat-square&logo=pandas&logoColor=c6ff00)
![SQLite](https://img.shields.io/badge/SQLite-0d0d0d?style=flat-square&logo=sqlite&logoColor=c6ff00)
![NetworkX](https://img.shields.io/badge/NetworkX-0d0d0d?style=flat-square&logoColor=c6ff00)

</div>

---

Учебные и исследовательские ноутбуки: от нейрона, собранного вручную на тензорах, до сверточных сетей, transfer learning и распределённой обработки данных. Каждый ноутбук можно открыть в Google Colab в один клик.

<p align="center">
  <img src="assets/fashion-mnist-predictions.png" width="62%" alt="Предсказания CNN на Fashion-MNIST">
  <img src="assets/koch-graph.png" width="35%" alt="Граф Коха">
</p>

## Содержание

### 01 · Deep Learning

| Ноутбук | Что внутри | |
|---|---|---|
| [nn-from-scratch-backprop](01-deep-learning/nn-from-scratch-backprop.ipynb) | Нейрон, полносвязный слой, ReLU / softmax / ELU, MSE и cross-entropy, L2-регуляризация и обратное распространение ошибки, написанные вручную на тензорах PyTorch, SGD и пакетный градиентный спуск | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/01-deep-learning/nn-from-scratch-backprop.ipynb) |
| [cnn-image-classification](01-deep-learning/cnn-image-classification.ipynb) | Классификация Fashion-MNIST и CIFAR-10 полносвязными и сверточными сетями, свои датасеты из архивов, transfer learning на VGG16, матрицы ошибок | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/01-deep-learning/cnn-image-classification.ipynb) |

### 02 · Performance

| Ноутбук | Что внутри | |
|---|---|---|
| [profiling-vectorization-numba](02-performance/profiling-vectorization-numba.ipynb) | Профилирование (`line_profiler`), векторизация NumPy / pandas и ускорение циклов через Numba со сравнением времени | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/02-performance/profiling-vectorization-numba.ipynb) |
| [multiprocessing](02-performance/multiprocessing.ipynb) | Параллельные вычисления на `multiprocessing`: частотный анализ текста и обработка CSV в несколько процессов | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/02-performance/multiprocessing.ipynb) |

### 03 · Big Data · Dask

| Ноутбук | Что внутри | |
|---|---|---|
| [dask-array](03-big-data-dask/dask-array.ipynb) | Массивы, которые не помещаются в память: чанки, ленивые вычисления, HDF5 | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/03-big-data-dask/dask-array.ipynb) |
| [dask-bag-mapreduce](03-big-data-dask/dask-bag-mapreduce.ipynb) | Map-Reduce на Dask Bag: разбор текста и JSON | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/03-big-data-dask/dask-bag-mapreduce.ipynb) |
| [dask-dataframe](03-big-data-dask/dask-dataframe.ipynb) | Датафреймы на множестве файлов: пропуски, группировки, агрегаты | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/03-big-data-dask/dask-dataframe.ipynb) |
| [dask-delayed](03-big-data-dask/dask-delayed.ipynb) | Параллельные пайплайны на `dask.delayed`: архивы, парсинг HTML (BeautifulSoup) | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/03-big-data-dask/dask-delayed.ipynb) |

### 04 · Databases

| Ноутбук | Что внутри | |
|---|---|---|
| [sqlite-pandas](04-databases/sqlite-pandas.ipynb) | SQL-запросы к базе Chinook через `sqlite3`, выгрузка в pandas и CSV | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/04-databases/sqlite-pandas.ipynb) |

### 05 · Fractal Graphs

| Ноутбук | Что внутри | |
|---|---|---|
| [fractal-graphs](05-fractal-graphs/fractal-graphs.ipynb) | Рекурсивная генерация графов на NetworkX: граф Коха, фрактальное дерево, 3D-пирамида и распределения степеней вершин | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/05-fractal-graphs/fractal-graphs.ipynb) |
| [graph-basics](05-fractal-graphs/graph-basics.ipynb) | Ориентированный граф и его визуализация | [![Colab](https://img.shields.io/badge/Open_in_Colab-0d0d0d?style=flat-square&logo=googlecolab&logoColor=c6ff00)](https://colab.research.google.com/github/cent0n1y/python-data-ml/blob/main/05-fractal-graphs/graph-basics.ipynb) |

<p align="center">
  <img src="assets/fashion-mnist-confusion.png" width="66%" alt="Матрица ошибок">
  <img src="assets/pyramid-3d.png" width="31%" alt="3D-пирамида">
</p>

## Запуск локально

```bash
pip install torch torchvision numpy pandas matplotlib seaborn scikit-learn numba line_profiler "dask[complete]" h5py networkx beautifulsoup4 nltk
jupyter lab
```

Датасеты для заданий с собственными изображениями лежат на Яндекс Диске, ссылки указаны внутри ноутбука.

---

<p align="center"><sub>part of <a href="https://github.com/cent0n1y">cent0n1y</a> · 01</sub></p>
