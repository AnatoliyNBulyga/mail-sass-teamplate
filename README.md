# Шаблон для верстки HTML-писем mail-sass-teamplate

## Запуск сборки проекта
В адресе вашего проекта на ПК не должно быть кириллицы. Идеально — создайте с корне диска С: или D: папку "projects" и разместите в нее папку вашего проекта. У вас может получится что то похожее на это: C:\projects\mail-sass-teamplate

1. Клонирование проекта к себе на ПК               
```sh
git clone https://github.com/AnatoliyNBulyga/mail-sass-teamplate.git
```

2. Переходим в созданную папку
```sh
cd mail-sass-teamplate
```

3. Устанавливаем все зависимости
```sh 
npm install
```

### code guide

Общие правила:

* [sass] - CSS препроцессор
* В готовом проекте можно воспользоваться сервисом https://foundation.zurb.com/emails/inliner-v2.html
для конвертирования стилей из main.css в inline
