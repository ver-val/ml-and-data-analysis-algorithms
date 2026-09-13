# Machine Learning and Data Analysis Algorithms

Репозиторій містить виконані лабораторні роботи з аналізу даних і машинного навчання. Ноутбуки можна запускати локально в Jupyter Notebook або JupyterLab.

## Лабораторні роботи

| № | Тема | Ноутбук |
|---|---|---|
| 1 | Аналіз даних про доходи населення | [lab1](lab1/lab_1.1_1.2_pandas_salary_ua.ipynb) |
| 2 | Аналіз даних про пасажирів лайнеру «Титанік» | [lab2](lab2/lab_1.3_1.4_pandas_titanic_ua.ipynb) |
| 3 | Візуальний аналіз даних про публікації на сайті | [lab3](lab3/lab_2.2_visual_habr.ipynb) |
| 4 | Візуальний аналіз даних про пасажирів «Титаніку» | [lab4](lab4/lab_2.1_visual_titanic.ipynb) |
| 5 | Аналіз демографічних даних | [lab5](lab5/lab_3.1_3.2_decision_trees.ipynb) |
| 6 | Ідентифікація користувача за допомогою логістичної регресії | [lab6](lab6/lab_3.3_3.4_intruder_detection.ipynb) |
| 7 | Аналіз великих наборів даних кредитного скорингу на основі алгоритму випадкового лісу | [lab7](lab7/lab_4.1_credit_scoring_random_forest.ipynb) |
| 8 | Вивчення метрик якості класифікації | [lab8](lab8/lab_4.2_quality_metrics_classification.ipynb) |
| 9 | Оцінювання інформативності ознак за допомогою градієнтного бустінгу | [lab9](lab9/lab_4.3_xgb_flight_delays.ipynb) |
| 10 | Робота з незбалансованими вибірками | [lab10](lab10/lab_4.4_imbalanced_problems.ipynb) |
| 11 | Налаштування гіперпараметрів регресійних моделей для оцінювання якості вина | [lab11](lab11/lab_11_wine_quality.ipynb) |
| 12 | Прогнозування затримок вильоту літаків з використанням різних алгоритмів бустінгу | [lab12](lab12/lab12.ipynb) |

## Дані та результати

Датасети зберігаються у відповідних папках `data`. Згенеровані прогнози та інші результати зберігаються у папках `results`, якщо вони передбачені конкретною лабораторною роботою.

## Запуск

Встановлення основних залежностей:

```bash
python3 -m pip install --user jupyter pandas numpy matplotlib seaborn scikit-learn xgboost
```

Запуск Jupyter:

```bash
jupyter notebook
```

Для лабораторної роботи 10 додатково може знадобитися:

```bash
python3 -m pip install --user imbalanced-learn
```

У ноутбуках передбачено локальні шляхи до даних, тому Google Colab для запуску не потрібен.
