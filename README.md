# Анализ рынка труда IT-специалистов в России

## Описание проекта
В связи с пандемией коронавируса и общей экономической ситуацией, а также переходом бизнеса в онлайн-формат, резко возрос спрос на специалистов в сфере IT. Как следствие, рынок труда в России претерпел заметные изменения, которые не могли не сказаться на условиях труда и требованиях, предъявляемых к соискателям. Образовательные программы ВУЗов не всегда готовят специалистов, соответствующих новым требованиям рынка, в частности в сфере  IT, что приводит к невостребованности выпускников. В связи с этим появилась необходимость исследовать рынок труда в сфере IT в России.

## Задача проекта
Определить какие специалисты наиболее востребованы на рынке IT-профессий и какие квалификационные требования к ним предъявляются. 

## Используемый стек
![Static Badge](https://img.shields.io/badge/requests-red)
![Static Badge](https://img.shields.io/badge/json-red)
![Static Badge](https://img.shields.io/badge/os-red)
![Static Badge](https://img.shields.io/badge/nltk-red)
![Static Badge](https://img.shields.io/badge/pandas-red)
![Static Badge](https://img.shields.io/badge/numpy-red)
![Static Badge](https://img.shields.io/badge/matplotlib-red)
![Static Badge](https://img.shields.io/badge/seaborn-red)

---

## Итоги

В результате работы был проведен анализ рынка труда IT специалистов в России на примере интернет-рекрутмента hh.ru. Результаты анализа отражены в графическом <a href = "https://github.com/ArtemV0ronin/analysis_of_the_IT_vacancies_market/blob/main/report.pdf">ОТЧЕТЕ</a> .

Ход выполнения проекта:

1. Сначала путем <a href = "https://github.com/ArtemV0ronin/analysis_of_the_IT_vacancies_market/blob/main/parsing.ipynb">парсинга</a> были получены сырые данные с интернет-рекрутмента hh.ru по вакансиям в сфере IT:

![data_raw](https://github.com/ArtemV0ronin/analysis_of_the_IT_vacancies_market/blob/main/media/data_raw.jpg)

2. Затем данные были очищены и обработаны. Финальный вид:

![data_clean](https://github.com/ArtemV0ronin/analysis_of_the_IT_vacancies_market/blob/main/media/data_clean.jpg)
   
3. В финальном виде данные были сохранены в файл. Вся дальнейшая работа и анализ проходили с этим файлом.

4. Определены наиболее востребованные актуальные квалификационные требования по каждому из IT направлений:
  - аналитик
  - тестировщик
  - системный инженер
  - гейм дизайнер
  - разработчик
  - 
Ноутбук анализа по направлениям лежит в файле <a href = "https://github.com/ArtemV0ronin/analysis_of_the_IT_vacancies_market/blob/main/analysis.ipynb">parsing.ipynb</a>

5. Проведен общий анализ вакансий с распределением по:
- городам
- сферам
- графику работы
- стажу
- зарплатам

6. Построен итоговый <a href ="https://datalens.yandex/e1r1pnmzbv3a7?state=287df231396">дашбор</a> на платформе Yandex DataLens



