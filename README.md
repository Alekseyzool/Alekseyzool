# 👋 Привет! Меня зовут Алексей Язев  

**Chief Metrologist · Data Analyst · AI & Automation Enthusiast**

Я совмещаю инженерное мышление с аналитическим подходом: автоматизирую рутину, выстраиваю метрики, анализирую данные и внедряю решения на основе нейросетей.  
Работаю в сфере метрологии и аналитики данных (VXI-Systems), а в свободное время развиваю pet-проекты с AI-агентами, ClickHouse-дашбордами и телеграм-ботами.  

---
## 🧠 Стек и инструменты

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?logo=matplotlib&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFA500?logo=catboost&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-20B2AA?logo=lightgbm&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC00?logo=clickhouse&logoColor=black)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visual-studio-code&logoColor=white)

---

## 🚀 Проекты и учебные работы

### 🧰 **Pet-projects**
> **Мои собственные инструменты и проекты, созданные для автоматизации и аналитики.**

| Проект | Описание | Стек |
| --- | --- | --- |
| [FGIS Arshin](https://github.com/Alekseyzool/arshin) | Цель — автоматизировать загрузку метрологических данных; собрал пайплайн импорта поверок и типов СИ из ФГИС в ClickHouse, добавил проверку дубликатов и интерфейс на Streamlit. | `Python`, `Streamlit`, `Requests`, `Pandas`, `clickhouse-driver` |
| [E-commerce OLIST](01_pet_projects/E-commerce_OLIST/E-commerce%20OLIST%20analysis.ipynb) | Цель — удержать покупателей маркетплейса; выгрузил данные, провел когортный анализ, приоритизировал гипотезы и посчитал ключевые A/B-метрики для продуктовых решений. | `Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `SQLAlchemy` |
| [Trade Bot](01_pet_projects/trade_bot/README.md) | Цель — автоматизировать ручную торговлю на Bybit; реализовал управление ордерами и уведомления, подключил историю сделок и ускорил котировки через Rust-расширение. | `Python`, `python-telegram-bot`, `PyBit`, `SQLite`, `Rust` |

---

### 🎓 **Образовательные проекты**

#### [**Karpov.Courses**](02_karpov_courses/README.md)
> Небольшая коллекция ноутбуков по аналитике и прогнозированию; подробности — в README каталога.

| Проект | Описание | Стек |
| --- | --- | --- |
| [AA & AB Simulator](02_karpov_courses/AA_AB_karpov_simulator.ipynb) | Цель — проверить корректность сплитования и статистических тестов; построил симулятор AA/AB, исследовал влияние разбалансировки на CTR и визуализировал результаты для команды. | `Python`, `Pandas`, `NumPy`, `SciPy`, `Matplotlib`, `Seaborn`, `clickhouse-connect`, `swifter` |
| [Final Project · Pricing](02_karpov_courses/Final_project_Karpov.ipynb) | Цель — оценить влияние новой цены на премиум; очистил данные, посчитал продуктовые метрики, построил бутстрап uplift и подготовил рекомендации. | `Python`, `Pandas`, `NumPy`, `SciPy`, `Statsmodels`, `Matplotlib`, `Seaborn` |
| [Predicting Server Loads](02_karpov_courses/Predicting_server_loads.ipynb) | Цель — прогнозировать нагрузку на сервис; подготовил временные признаки, обучил Orbit и CatBoost, сравнил метрики и описал сценарии мониторинга. | `Python`, `Pandas`, `NumPy`, `Orbit`, `CatBoost`, `clickhouse-connect` |

#### [**Yandex Practicum**](03_yandex_practicum/README.md)
> Серия учебных аналитических проектов с бизнес-контекстом.

**Основные проекты**

| Проект | Описание | Стек |
| --- | --- | --- |
| [Telecom Tariff](03_yandex_practicum/04_tariff_telecom/tariff_telecom.ipynb) | Цель — сравнить тарифы «Смарт» и «Ультра»; подготовил очищенную выборку, исследовал выручку по сегментам и проверил статистические гипотезы для рекомендаций. | `Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `SciPy` |
| [Bank Customer Churn](03_yandex_practicum/07_churn_customer_bank/churn_customer_bank.ipynb) | Цель — снизить отток клиентов; проанализировал факторы риска, сбалансировал классы и обучил модели классификации для прогнозов. | `Python`, `Pandas`, `NumPy`, `scikit-learn` |
| [Taxi Order Forecasting](03_yandex_practicum/12_taxi_order_forecasting/taxi_order_forecasting.ipynb) | Цель — прогнозировать часовые заказы такси; создал лаговые признаки, протестировал бустинг и ARIMA, выбрал модель с наименьшим MAPE для планирования автопарка. | `Python`, `Pandas`, `NumPy`, `scikit-learn`, `CatBoost`, `Statsmodels` |
| [Oil Production Regions](03_yandex_practicum/08_region_oil_production/region_oil_production.ipynb) | Цель — выбрать прибыльный регион добычи; построил модель качества скважин, провел bootstrap для оценки риска и предложил инвестиционную стратегию. | `Python`, `Pandas`, `NumPy`, `scikit-learn` |
| [Toxic Comments](03_yandex_practicum/13_toxic_comments/toxic_comments.ipynb) | Цель — автоматизировать модерацию комментариев; собрал корпус, подготовил TF-IDF-признаки и обучил логистическую регрессию для выявления токсичности. | `Python`, `Pandas`, `NumPy`, `scikit-learn`, `NLTK` |

<details>
<summary>Дополнительные проекты Яндекс Практикума</summary>

<br>

| Проект | Описание | Стек |
| --- | --- | --- |
| [Music Service](03_yandex_practicum/01_music_service/music_service.ipynb) | Цель — сравнить музыкальные предпочтения городов; очистил логи и проверил гипотезы по плейлистам Москвы и Петербурга. | `Python`, `Pandas` |
| [Bank Borrowers](03_yandex_practicum/02_bank_borrowers/bank_borrowers.ipynb) | Цель — оценить влияние семейного статуса и детей на просрочки; подготовил данные и построил анализ факторов риска. | `Python`, `Pandas` |
| [Real Estate Market](03_yandex_practicum/03_real_estate_market/real_estate_market.ipynb) | Цель — изучить факторы стоимости жилья; исследовал объявления, выявил ключевые параметры и центровую надбавку. | `Python`, `Pandas`, `Matplotlib` |
| [Age Determination](03_yandex_practicum/05_age_determination/age_determination.ipynb) | Цель — автоматизировать проверку возраста покупателей; обучил ResNet50, оценил точность и подготовил pipeline. | `Python`, `TensorFlow`, `Pandas`, `NumPy`, `Matplotlib` |
| [Telecom Clients](03_yandex_practicum/06_telecom_clients/telecom_clients.ipynb) | Цель — рекомендовать тарифы абонентам; сгенерировал признаки потребления и обучил классификаторы для подбора предложения. | `Python`, `Pandas`, `scikit-learn` |
| [Gold Refining](03_yandex_practicum/09_gold_refining/gold_refining.ipynb) | Цель — повысить качество обогащения золота; построил модели этапов технологической цепочки и оценил метрики восстановления. | `Python`, `Pandas`, `NumPy`, `scikit-learn` |
| [Game Success](03_yandex_practicum/10_game_success/game_success.ipynb) | Цель — прогнозировать успешность игр; исследовал рынки по платформам и жанрам, проверил гипотезы по рейтингам. | `Python`, `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `SciPy` |
| [Car Cost](03_yandex_practicum/11_car_cost/car_cost.ipynb) | Цель — автоматизировать оценку стоимости авто; сравнил LightGBM и CatBoost, подобрал оптимальные гиперпараметры. | `Python`, `Pandas`, `NumPy`, `scikit-learn`, `LightGBM`, `CatBoost` |

</details>

#### [**Kaggle Experiments**](04_kaggle/README.md)
> Каталог соревновательных ноутбуков и черновиков для Kaggle.


| Проект | Описание | Стек |
| --- | --- | --- |
| [Spaceship Titanic](04_kaggle/spaceship_titanic/Spaceship_Titanic_master.ipynb) | Цель — предсказать, какие пассажиры будут перенесены в альтернативное измерение; провёл фич-инжиниринг, настроил CatBoost; топ 20 в соревновании. | `Python`, `scikit-learn`, `CatBoost`, `LightGBM`, `Optuna` |

--- 



### 💬 Контакты

📧 **Email:** [zoolrmx@gmail.com](mailto:zoolrmx@gmail.com)  
💬 **Telegram:** [@Yazev_Aleksey](https://t.me/Yazev_Aleksey)  
💬 **Kaggle:** [@yazevaleksey](https://www.kaggle.com/yazevaleksey)  
---

⭐️ *GitHub — моё рабочее портфолио. Здесь я систематизирую обучение, pet-проекты и эксперименты с AI-агентами. Если вы ищете аналитика, который умеет не только считать, но и строить инфраструктуру вокруг данных — вы по адресу.*
