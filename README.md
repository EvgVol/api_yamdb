### ЯП - Спринт 10 - Проект YaMDb (групповой проект). Python-разработчик (бекенд) (Яндекс.Практикум)
### Описание
Проект YaMDb собирает отзывы (Review) пользователей на произведения (Title).
Сами произведения в YaMDb не хранятся, здесь нельзя посмотреть фильм или послушать музыку
Произведения делятся на категории: «Книги», «Фильмы», «Музыка».
Список категорий (Category) может быть расширен (например, можно добавить категорию «Изобразительное искусство» или «Ювелирка»).

Команда разработки:
- :white_check_mark: [EvgVol (в роли Python-разработчика Тимлид - разработчик 1)](https://github.com/evgvol)
- :white_check_mark: [Mikhail Dudin (в роли Python-разработчика - разработчик 2)](https://github.com/dude-inn)
- :white_check_mark: [saniusster (в роли Python-разработчика - разработчик 3)](https://github.com/saniusster)


Произведению может быть присвоен жанр из списка предустановленных (например, «Сказка», «Рок» или «Артхаус»).

Добавлять произведения, категории и жанры может только администратор.

Благодарные или возмущённые пользователи оставляют к произведениям текстовые отзывы и ставят произведению оценку в диапазоне от одного до десяти (целое число); из пользовательских оценок формируется усреднённая оценка произведения — рейтинг (целое число). На одно произведение пользователь может оставить только один отзыв.

Добавлять отзывы, комментарии и ставить оценки могут только аутентифицированные пользователи.

Полная документация к API находится по эндпоинту /redoc

### Стек технологий использованный в проекте:
- Python 3.7
- Django 2.2.28
- DRF
- JWT