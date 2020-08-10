Задание

Реализовать добавление и просмотр списка книг и их удаление. Храним данные в базе данных.

Две страницы. Одна страница - список книг, представляющий собой таблицу со всеми полями
(список полей дальше в задании). Для каждой книги должно быть указано сколько минут назад
была добавлена книга. Напротив каждой книги ссылка или кнопка &quot;Удалить&quot;, удаляющая книгу из
базы данных и из списка на странице. Удаление происходит аяксом без перезагрузки страницы.
После удаления выдать сообщение стандартным окном alert, что книга с названием (указать
название) удалена или не удалось удалить, если по какой-то причине не удалось удалить.

Над таблицей сделать ссылку или кнопку - Добавить книгу.

По клике на ссылке или кнопке перейти на страницу с формой добавления книги. Должны быть
такие поля -

Название, Дата добавления (тип дата время), Краткое описание, количество страниц и цена. Дату
вводим просто строкой, по умолчанию в поле стоит текущая дата.

По кнопке &quot;Добавить&quot; (кнопка, которая сабмитит форму) делать проверку заполненности полей js,
если все поля заполнены - то форма отправляется, и книга добавляется в базу данных, иначе
делаем у незаполненных полей красные границы. После добавления происходит
перенаправление на список книг.

___________________________________________________________________________________________
В phpMyAdmin необходимо создать базу books и импортировать туда базу, расположенную в папке mySQL