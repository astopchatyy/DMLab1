# Лабораторна робота з Data Mining actual problems

## Опис проекту
Цей проект є лабораторною роботою для курсу **Data Mining actual problems**. Робота полягає в обробці датасету [Mobile Price Classification](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification).

Датасет містить дані про телефони різних моделей, які класифікуються як належні до однієї із 4 цінових категорій.

Для класифікації використовуються наступні методи:
- One Rule
- Naive Bayes
- KNN
- Decision Tree

## Виконання проєкту
### 1. Створення віртуального середовища
```bash
python -m venv venv
```

### 2. Активація віртуального середовища
- **Windows:**
```bash
venv\Scripts\activate
```
- **Mac/Linux:**
```bash
source venv/bin/activate
```

### 3. Встановлення бібліотек із requirements.txt
```bash
pip install -r requirements.txt
```

### 4. Встановлення Jupyter Notebook
```bash
pip install notebook ipykernel
```

### 5. Запуск файлу DMLab_1.ipynb
```bash
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
jupyter notebook DMLab_1.ipynb
```


