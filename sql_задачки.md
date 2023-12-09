напишите запрос который вернет:

superhero_name всех героев мужчин = 519
количество героев женщин = 203

средний рост и вес всех мужчин = gender(519), height(292), weight(19213)

средний рост и вес всех добрых героев = alignment(504), height(216), weight(19944)
средний рост и вес всех злых героев = alignment(212), height(404), weight(454952)

superhero_name всех героев superhero_name которых начинаются с буквы s = 80

superhero_name и рост всех героев, рост которых больше 180, отсортированный по убыванию

SELECT superhero_name, height_cm
FROM superhero
WHERE height_cm > 180
ORDER BY height_cm DESC;

какой цвет глаз встречается чаще других? = 35


