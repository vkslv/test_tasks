# Тестовое задание для на позицию Intern/Analyst Natural Resources Consulting&IndustryX в Axenix
| Описание           | Используемые библиотеки                     |
| :--------------------- |:---------------------------|
| Требуется провести разведочный анализ данных, выбрать критерий для точности модели, указать степень важности (информативности) каждой из 10 входных переменных с точки зрения точности модели. Дополнительно: Что еще можно предложить чтобы улучшить получившийся результат? | pandas, matplotlib, numpy, sklearn

## Вывод

- Были изучены данные на предмет аномалий, ошибок и выбросов, выявлены наиболее важные фичи с помощью корреляционной матрицы;
- Обучена модель Линейной Регрессии (без гиперпараметров и их подбора);
- Рассчитаны MAE и R^2;
- Были предложены варианты улучшения модели с помощью:
  1. Сокращения признаков которые не оказывают сильного влияния на таргет
  2. Подбора гиперпараметров
  3. Добавления новых признаков
- Для тестирования предположений были удалены маловлияющие признаки;
- Удаление маловлияющих признаков улучшило показатель MAE на 0.002, что является малозначимым.
