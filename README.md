Задача №3 - Работа с историей и переключение между коммитами
Легенда
Проект NeuroStartUp всё больше развивается и всё больше разработчиков подключается к проекту. Лендинг постоянно оптимизируется под маркетинговые кампании и запросы. Но тут выясняется, что перестала работать функция «Подписаться на новости», а это достаточно важная функция. Вы знаете лишь, что всё работало в коммите c2e06a, а когда перестало работать - никто не знает.
Вам нужно найти в каком из коммитов функция сломалась и кто её сломал (чтобы он потом починил 😃).
Задача
1.	Клонируйте Git-репозиторий по ссылке;
2.	Переключитесь на коммит c2e06a, удостоверьтесь, что функция работает*;
3.	Переключитесь на последний коммит;
4.	Используя команды переключения между коммитами, определите в каком коммите и кем была внесена ошибка. После переключения между коммитами обновляйте открытый в браузере файл index.html.
Примечание:* чтобы проверить, что функция работает, нужно открыть в браузере файл index.html (просто два раза кликните на этом файле в файловом менеджере), ввести в поле ввода подписки адрес электронной почты и нажать кнопку. В коммите c2e06a форма работает, после отправки формы появляется окошко с текстом.
Окошко с текстом будет выглядеть примерно вот так (если у вас тёмная тема оформления браузера):  
В качестве результата пришлите Имя автора и идентификатор первого коммита, в котором функция перестала работать. Вставьте ответ в поле "Комментарий". Не прикладывайте файлы к решению


ОТВЕТ:
Ошибка произошла в коммите:
commit b557916
Author: Oleg <oleg@localhost>

commit b55791692d102a18cd62e7d92deb915119f2c8b2 (HEAD)
Author: Oleg <oleg@localhost>
Date:   Fri Nov 9 02:27:06 2018 +0300
    Возврат к предыдущей версии подписки новостей. Проверка через regexp
