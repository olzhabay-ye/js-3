Задача на Codewars: "Сколько воды мне нужно?"

Описание:

Моя стиральная машина использует количество воды для стирки (в JavaScript и Python) или max_load (в Ruby) количества одежды. Вам дается определенное количество одежды для стирки. Для стирки каждого отдельного предмета одежды сверх загрузки стиральная машина будет использовать на 10 % больше воды (мультипликативно).

Например, если загрузка равна 10, необходимое количество воды равно 5, а количество белья для стирки равно 14, то вам потребуется 5 * 1,1 ^ (14 - 10) количества воды.

Напишите функцию HowMuchWater (JS)/how_much_water (Python и Ruby), чтобы определить, сколько воды необходимо, если у вас есть определенное количество одежды. Функция будет принимать 3 аргумента: — вода, нагрузка (или max_load в Ruby) и одежда.

Моя стиральная машина старой модели, которая может выдерживать только двойную загрузку (или максимальную загрузку). Если количество одежды более чем в 2 раза превышает стандартное количество загрузки (max_load), верните «Слишком много одежды». Стиральная машина также не может обрабатывать количество одежды меньше, чем загрузка (max_load). В этом случае верните «Недостаточно одежды».

Ответ следует округлить до ближайших двух десятичных знаков.