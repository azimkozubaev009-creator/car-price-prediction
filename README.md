🚗 Car Price Prediction App
Интерактивное веб-приложение на базе Streamlit и консольный инструмент для прогнозирования стоимости автомобилей с использованием машинного обучения.

📋 Описание проекта
Проект реализует модель Linear Regression (Линейная регрессия) для оценки рыночной стоимости авто на основе технических характеристик, таких как объем двигателя, мощность и вес.

🚀 Инструкция по запуску
1. Установка зависимостей
Bash
pip install -r requirements.txt
2. Обучение модели
Bash
python train.py
В результате появятся файлы model.pkl и plot.png.

3. Запуск веб-интерфейса (Streamlit)
Bash
streamlit run web_app.py
4. Консольный расчет (Альтернатива)
Bash
python predict.py
📊 Используемые признаки (Features)
enginesize — объем двигателя

horsepower — лошадиные силы

curbweight — снаряженная масса

carwidth — ширина кузова

highwaympg — расход топлива

🛠 Технический стек
Интерфейс: Streamlit

ML: Scikit-learn

Анализ данных: Pandas, NumPy

Визуализация: Matplotlib, Seaborn

📂 Структура репозитория
web_app.py — основной файл веб-приложения.

train.py — скрипт обучения модели.

predict.py — консольная версия предсказателя.

CarPrice_Assignment.csv — датасет с данными.

model.pkl — сохраненная обученная модель.
