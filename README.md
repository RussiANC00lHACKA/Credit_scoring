# Проект по кредитному скорингу

## Описание проекта

Этот проект посвящен разработке модели кредитного скоринга с использованием алгоритмов машинного обучения. Основной целью является предсказание кредитоспособности клиентов на основе предоставленных данных.

## Задачи проекта

- Изучение и подготовка данных (предобработка, заполнение пропусков, кодирование категориальных признаков).
- Построение моделей машинного обучения для решения задачи классификации:
  - Случайный лес
- Оценка качества моделей с использованием метрик: точность, полнота, F1-мера, ROC-AUC.

## Задача для студентов

### Описание задачи

Студенты должны:
1. Проанализировать датасет и подготовить его для моделирования (пропущенные значения, масштабирование, кодирование).
2. Построить модель кредитного скоринга с использованием логистической регрессии или случайного леса.
3. Оценить качество модели и интерпретировать результаты.
4. Представить результаты в формате отчета или презентации.

### Шаги выполнения

1. Загрузите предоставленный датасет и выполните его анализ (например, используя pandas и seaborn).
2. Выполните предобработку данных (масштабирование, кодирование категориальных переменных, удаление или заполнение пропущенных данных).
3. Постройте модель:
   - Случайный лес
4. Оцените качество модели:
   - Разделите данные на обучающую и тестовую выборки.
   - Рассчитайте метрики (точность, ROC-AUC и другие).
5. Сравните производительность моделей и сделайте выводы.

## Используемые библиотеки

- Python 3.x
- pandas
- scikit-learn
- matplotlib
- seaborn
- numpy

## Как начать

1. Клонируйте репозиторий:
   ```bash
   git clone https://github.com/your-username/credit-scoring.git
