# 🚗 Jovanni | Анализ вторичного авторынка в России с помощью Big Data и ML

## 📌 Тема ВКР: Маркетинг и продажи  
**Название проекта:** _Анализ предпочтений покупателей и ценообразование автомобилей на вторичном рынке с применением Big Data и ML_  

🔍 **Цель проекта**  
Исследование спроса на автомобили по регионам России и построение модели оценки цен подержанных автомобилей на основе открытых данных и онлайн-объявлений (Auto.ru, Avito, Drom и др.).

---

## 👨‍💻 Команда проекта Jovanni

| Участник            | Роль                                  | Обязанности |
|---------------------|---------------------------------------|-------------|
| **Орехов Кирилл**   | 🎯 Аналитик рынка / Руководитель проекта | - `Формулировка ТЗ и маркетинговой цели` - `Сегментация по регионам и категориям`  - `Интерпретация результатов` - `Подготовка отчётов и рекомендаций` |
| **Черкашин Кирилл** | 🛠️ Data Engineer / Web Scraper         | - `Разработка парсеров (Auto.ru, Avito, Drom)` - `Очистка и нормализация данных`  - `Хранение в SQL/NoSQL` - `Гео-привязка и обновления` |
| **Мовчан Антон**    | 📊 Data Analyst / BI Specialist         | - `Кластеризация регионов` - `Тепловые карты, визуализация спроса`  - `Тренды и динамика интереса` - `Интерактивные дашборды (Tableau, Dash)` |
| **Мороз Роман**     | 🤖 ML-инженер / Data Scientist          | - `Создание ML-модели оценки цены` - `Обучение моделей (XGBoost, RF и др.)` - `SHAP-анализ, отбор признаков` - `Кросс-валидация, настройка` |
| **Краснобриж Дмитрий** | 🌐 Fullstack Developer                 | - `Веб-интерфейс для ввода параметров` - `API-интеграция модели (Flask/FastAPI)` - `Прототип системы рекомендаций` |

---

## 🧩 Стек технологий

#### 🖥️ Языки программирования  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)  
![SQL](https://img.shields.io/badge/SQL-003B57?style=flat&logo=postgresql&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)  

#### ⚙️ Библиотеки и ML  
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)  
![XGBoost](https://img.shields.io/badge/XGBoost-EC3E29?style=flat&logo=xgboost&logoColor=white)  
![SHAP](https://img.shields.io/badge/SHAP-black?style=flat&logo=interpretable&logoColor=white)  
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)  
![Dash](https://img.shields.io/badge/Dash-00BFFF?style=flat&logo=plotly&logoColor=white)  

#### 🧹 Парсинг данных  
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-3c3c3c?style=flat&logo=python&logoColor=white)  
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat&logo=selenium&logoColor=white)  
![Requests](https://img.shields.io/badge/Requests-20232a?style=flat&logo=python&logoColor=white)  

#### 💾 Хранение данных  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)  
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)  

#### 📊 BI & Визуализация  
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)  
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)  
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)  

#### 🔬 ML & API  
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)  
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)  
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)  
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)  

#### 🛠️ Инфраструктура и DevOps  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)  
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)  
![CI/CD](https://img.shields.io/badge/CI%2FCD-4285F4?style=flat&logo=githubactions&logoColor=white)  

---

## 📂 Структура проекта

Jovanni-Project/
├── 📁 data/         — Сырые и обработанные данные

├── 📁 notebooks/    — Исследовательские Jupyter-ноутбуки

├── 🕸️ parsers/      — Парсеры для Auto.ru, Avito, Drom и др.

├── 🧠 model/         — ML-модели, пайплайны и веса

├── 📊 dashboard/    — BI-отчёты, визуализации и дашборды

├── 🔌 api/          — Код для API и фронтенда

├── 📚 docs/         — Презентации, отчёты, техническая документация

└── 📄 README.md     — Документация проекта



---

## 🧠 Ключевые задачи

- 📥 Сбор больших массивов данных с популярных автомобильных площадок  
- 🧹 Очистка, нормализация и обогащение данных (гео и категории)  
- 📈 Анализ предпочтений покупателей в регионах  
- 🧠 Обучение моделей предсказания стоимости  
- 🖥️ Разработка интерфейса для оценки стоимости  
- 💡 Разработка маркетинговых рекомендаций на основе анализа данных

---

## 🗺️ География проекта

Проект охватывает **все регионы России**, с возможностью фильтрации и кластеризации по:

- Федеральным округам  
- Крупнейшим городам  
- Категориям авто (бюджетные, премиум, внедорожники и др.)

---

## 📌 Контакты

📧 Связь: [напишите нам в Issues или Discussions](https://github.com/Jovanni-org/REPO-NAME/discussions)  
📍 Организация: **Jovanni** — платформа для дата-проектов студентов и энтузиастов

---

## 🚀 Статус проекта

> 🔄 В активной разработке  
> 🧪 Ведётся сбор и предварительный анализ данных  
> 📊 Первая версия ML-модели — готова  
> 🌐 MVP-интерфейс — в разработке

---

## ⭐ Благодарности

Проект выполнен в рамках выпускной квалификационной работы с использованием открытых данных и современных технологий анализа и визуализации.

---

