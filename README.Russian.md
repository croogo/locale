Проект в разработке...

# Description

Базовый код движка: [tree][1]

# Установка 

Админ панель: меню -> Extensions -> Locales, 
ссылка Upload, загрузите [rus.zip][2] и активируйте язык.

Необходимо принимать во внимание разрешения на каталог **locale**.

# Ручная установка

Поместите каталог **rus** в каталоге Croogo **locale** . 

Переактивируйте язык в админ панели: Menu-> Extensions-> Locales.

# Предупреждение

Кроме того, во избежания расползания меню администратора, необходимо внести изменения в файле **webroot/css/admin.css** линии 126:

    #nav ul li a { margin-right: 20px; }

измените 20px на 2px.


  [1]: http://github.com/croogo/croogo/tree/8b0ab6bc5cc842940ab0a202cce81e47ecf875ba
  [2]: http://github.com/downloads/vksee/croogo-russian-translation/rus.zip