# Описание проекта: #
На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.

# Задачи проекта: #
Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир.

# Навыки и инструменты: #
* Python
* Pandas
* Matplotlib
* предобработка данных
* исследовательский анализ данных
* визуализация данных

# Вывод: #
В результате проведения исследовательского анализа данных, удалось выяснить следующее:
* Общая площадь составляет от 12 квадратных метров до 900 квадратных метров.
* Жилая площадь составляет от 19 квадратных метров до 409 квадратных метров.
* Площадь кухни составляет от 7 квадратных метров до 112 квадратных метров.
  
Самая продаваемая недвижимость на рынке имеет:
* Общую площадь от 42 до 45 квадратных метров.
* Жилую площадь от 17 до 30 квадратных метров.
* Площадь кухни от 9 до 11 квадратных метров.
  
Эти значения соответствуют площади 1-комнатной квариры.

Также стоит отметить, что среди объектов недвижимости есть:
* Квартиры со свободной планировкой, для которых указана только общая площадь, а жилая площадь равна 0.
* Квартиры со свободной планировкой и квартиры-студии, для которых указана только общая площадь, а площадь кухни равна 0.
* Стоимость недвижимости варьируется от 430 тысяч рублей до 763 миллионов рублей. Средняя стоймость объекта недвижимости - 6,5 миллионов рублей.

Наиболее распространены:
* 1-комнатные квартиры - 8138 объявлений
* 2-комнатные квартиры - 7897 обяъвлений
* 3-комнатные квартиры - 5779 обяъвлений

Также стоит отметить, что есть 59 объектов недвижимости со свободной планировкой, у этих объектов число комнат равно 0.

Средняя высота потолков - 2,7 метра, хотя встречаются объекты с более высокими потолками до 5 метров.

* Преобладает недвижимость на втором, третьем и первом этажах.
* Большая часть объявлений - недвижимость не на первых и не на последних этажах.
* Объявлений о продаже недвижимости на последнем этаже немного больше, чем на первом этаже.

На рынке недвижимости представлены здания практически любой этажности от 1 этажных до 60 этажных, но, преобладают 5 и 9 этажные здания.

* Большая часть недвижимости находится на удалении 12000-17000 метров от центра.
* Среднее расстояние до аэропорта составляет 28000 метров.
* Среднее расстояние до парка составляет 490 метров.

На гистограмме можно увидеть два пика, первый начинается с февраля и идет на спад к маю. Это связано с тем, что с мая начинается сезон отпусков и продажи недвижимости снижаются.

Второй пик начинается с сентября и идет на спад к декабрю. Это связано с тем, что сезон отпусков заканчивается и продажи недвижимости возрастают до новогодних праздников.

В среднем квартира продается 180 дней, большинство квартир продается гораздо быстрее. Есть квартиры, которые продаются больше года, скорее всего они имеют какие то проблемы.

* Самая высокая стоимость недвижимости зафиксирована в Санкт-Петербурге - 114868 рублей за квадратный метр.
* Самая низкая стоимость недвижимости зафиксирована в Выборге - 58141 рублей за квадратный метр.

С удалением от центра стоимость недвижимости уменьшается от 245833 рублей за квадратный метр до 73551 рублей за квадратный метр.
