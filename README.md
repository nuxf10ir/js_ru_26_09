# js_ru_26_09

##HT1.1 Создать список комментов к статье
##HT1.2 открывать/закрывать этот список по нажатию на кнопку(менять на ней текст)
##HT1.3 Починить 'close' на статье
##HT1.4 написать для всего propTypes

##HT2.1 Создать декоратор для Аккордеона
##HT2.2 Переиспользовать функционал Аккордеона с помощью наследования

##HT3.1 Добавить на уровне App календарь(https://github.com/gpbl/react-day-picker) с выбором диапазона дат, отображать этот диапазон текстом
##HT3.2 Добавить в CommentList форму нового коммента(user, text), без функционала добавления
##HT3.3 Валидировать форму: подсвечивать красным, если меньше 10 символов, не позволять больше 50.
##HT3.4 Не давать засабмитить невалидную форму, при сабмите чистить поля

##HT4.1 Вынести значение фильтров в стор
##HT4.2 Реализовать фильтрацию для ArticleList(показывать только отфильтрованные статьи)

##HT5.1 Переписать articles редюсер на хранение объекта вместо массива
##HT5.2 Написать middleware для генерации рандомных id
##HT5.3 Реализовать добавление коммента к статье

##HT6.1 Переписать comments редюсер на immutable
##HT6.2 Реализовать загрузку комментов к статье при открытии списка комментов(показывать лоадер, загружать только при первом открытии)

##HT7.1 Завестьи роут для пагинации комментов(/comments/1)
##HT7.2 Реализовать пагинацию всех комментов, по 5 на странице, загружать одир раз каждую, поуазывать лоадер(/api/comment?limit=5&offset=5)