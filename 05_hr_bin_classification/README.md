# Моделирование коэффициента удовлетворённости работников и прогнозирование оттока работников

## Цель работы

Разработать модели, предсказывающие уровень удовлетворённости работника и его увольнение из компании.

## Планируемое использование результата работы

Результаты работы будут использованы заказчком при оптимизировации процессов управления персоналом. 

## Входные данные

Заказчик предоставил данные с характеристиками работников компании. Данные представляют собой перечень работников, прошедших тест-опросник. Для указанных работников был рассчитан коэффициент удовлетворенности работой: от 0 до 1, где 0 — совершенно неудовлетворён, 1 — полностью удовлетворён. Среди представленых работников имеются данные об уволившихся. Целевым признаком для разработки моделей являются коэффициент удовлетворенности и отметка об увольнении работника.

## Задачи работы

1. Разработать модель машинного обучения, которая предскажет уровень удовлетворённости работника.
2. Разработать модель машинного обучения, которая предскажет увольнение работника из компании.

## Теги
`Python`, `Pandas`, `Matplotlib`, `Scikit-learn`, `shap`, `feature importance`

## Достижение цели работы

Были выявлены некоторые проблемы с входными данными, требующие предобработки: пропуски в данных, возможные дубликаты. Проведена предобработка данных, их исследовательский анализ и подготовка к обучению.
В результате работы были выбраны лучшие модели для обеих задач. Критерии качества достигнуты.