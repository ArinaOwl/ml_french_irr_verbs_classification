# ml_french_irr_verbs_classification

Приложение к выпускной квалификационной работе (ВКР) бакалавра "Нейросетевая классификация неправильных глаголов".

Численные эксперменты проводились с использованием интерактивного блокнота Jupyter Notebook. 

Блокноты и полученные данные разделены по директориям:
- [CREATE_IrrVerbs_dataset](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/tree/main/CREATE_IrrVerbs_dataset) - создание таблицы обучающих данных (раздел 2.2):
  - `IrrVerbs.xlsx` - таблица с отобранными в процессе анализа данных неправильными глаголами в форме инфинитива,
  - [Create_data.ipynb](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/blob/main/CREATE_IrrVerbs_dataset/Create_data.ipynb) - блокнот для автоматического создания таблицы обучающих данных,
  - `IrrVerbs(parsing).xlsx` - полученная таблица, содержащая выбранные временные формы и их транскрипции для глаголов из `IrrVerbs.xlsx`;

- [VEC_MODEL_LR_optimisation](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/tree/main/VEC_MODEL_LR_optimisation) - оптимизация способа векторизации, архитектуры модели и параметра скорости обучения (раздел 3.3):
  - [Experiments_1.ipynb](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/blob/main/VEC_MODEL_LR_optimisation/Experiments_1.ipynb) - блокнот с исходным кодом и инструкциями по вопроизведению данных эксперимента,
  - `IrrVerbs(parsing).xlsx` - таблица обучающих данных;

- [2_SAMPLES_experiment](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/tree/main/2_SAMPLES_experiment) - эксперимент по разбиению данных на две эквивалентные выборки равного размера (раздел 3.4):
  - [Experiments_2.ipynb](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/blob/main/2_SAMPLES_experiment/Experiments_2.ipynb) - блокнот с исходным кодом и инструкциями по вопроизведению данных эксперимента,
  - `IrrVerbs(parsing).xlsx` - таблица обучающих данных;

- [HID_DIM_optimisation](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/tree/main/HID_DIM_optimisation) - оптимизация размера скрытого слоя модели (раздел 3.5):
  - [Experiments_3.ipynb](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/blob/main/HID_DIM_optimisation/Experiments_3.ipynb) - блокнот с исходным кодом и инструкциями по вопроизведению данных эксперимента,
  - `IrrVerbs(parsing).xlsx` - таблица обучающих данных;

- [OVERFITTING_experiments](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/tree/main/OVERFITTING_experiments) - исследование эффекта "переобучения" (раздел 3.6):
  - [Experiments_4.ipynb](https://github.com/ArinaOwl/ml_french_irr_verbs_classification/blob/main/OVERFITTING_experiments/Experiments_4.ipynb) - блокнот с исходным кодом и инструкциями по вопроизведению данных эксперимента,
  - `IrrVerbs(parsing).xlsx` - таблица обучающих данных.

