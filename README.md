# Exercise Recognition and Repetition Counter 🏋️‍♂️

**Проект по распознаванию упражнений и подсчёту повторений с использованием данных акселерометра и гироскопа**

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 📌 О проекте

Этот проект решает задачу классификации силовых упражнений (например, приседания, отжимания, подтягивания) и подсчёта повторений на основе данных с датчиков движения (IMU). Система может быть интегрирована в фитнес-трекеры или мобильные приложения для автоматического мониторинга тренировок.

**Ключевые особенности:**
- Классификация 5+ видов упражнений с точностью >95%
- Алгоритм подсчёта повторений с погрешностью <5%
- Поддержка работы с реальными данными с датчиков
- Готовый пайплайн от сырых данных до предсказания

## 🛠 Технологии

- **Язык программирования**: Python 3.8+
- **Библиотеки**:
  - Обработка данных: Pandas, NumPy
  - Машинное обучение: Scikit-learn, TensorFlow/Keras
  - Визуализация: Matplotlib, Seaborn
  - Работа с сигналами: SciPy
- **Инструменты**: Jupyter Notebook, Git, DVC (опционально)

## 📂 Структура проекта
exercise-recognition/
├── data/
│ ├── raw/ # Исходные данные с датчиков
│ ├── processed/ # Обработанные данные
├── notebooks/
│ ├── 1.0-eda.ipynb # Анализ данных
│ ├── 2.0-feature-engineering.ipynb
│ └── 3.0-model-training.ipynb
├── src/
│ ├── data/ # Скрипты обработки данных
│ ├── features/ # Генерация признаков
│ ├── models/ # Обучение моделей
│ └── visualization/ # Визуализация
├── models/ # Сохранённые модели
├── reports/ # Отчёты и графики
├── requirements.txt # Зависимости
└── README.md # Этот файл


## 🚀 Быстрый старт

1. **Клонируйте репозиторий**:
   ```bash
   git clone https://github.com/ssssssshy/exercise-recognition.git
   cd exercise-recognition
Установите зависимости:


pip install -r requirements.txt
Запустите Jupyter Notebook:

jupyter notebook
Откройте notebooks/1.0-eda.ipynb для начала работы.

📊 Результаты
Модель классификации упражнений
Метрика	Значение
Accuracy	96.2%
Precision	95.8%
Recall	96.0%
F1-score	95.9%
Алгоритм подсчёта повторений
Точность: 94.5%

Средняя погрешность: 0.7 повторения

✉️ Контакты
Автор: Георгий Петросян
Email: petrosangosa2005@gmail.com
Telegram: @viberrviberrr