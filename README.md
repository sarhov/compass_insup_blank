## compass_insup_blank
===================


**Нужные  инструменты**

[InSales theme uploader](https://github.com/httplab/insup)

[Compass](http://compass-style.org/)

[Portable Jekyll](https://github.com/madhur/PortableJekyll)

Для удобства редактирование тем для [инсейлс (InSales)](http://insales.ru/), можно воспользоваться отличним инструментом [insup](https://github.com/httplab/insup) которий позволяет нам работать с инсейлс, через их API, для разработчиков темь, это особенно полезно, так как можно редактировать код локально, используя при этом свои привычные инструменты.

Так для большого удобства можно совместить с ՝compass՝,  для быстрого редактирования css файлов в теме insales.

Просто в файле config.rb, надо менять  путь к файлам, еще сами файлы надо держать отдельно от рабочей папки инсейлс, а сам файл ՝.insup՝ держать именно рабочей папке.

Заполняем нужные данные для подключения к сервере в ՝insup՝, потом запускаем compass, и редактируем тему используя compass и все его преимуешства.

```
chcp 65001
```
```
git config core.autocrlf true

```
