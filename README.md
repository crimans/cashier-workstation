# cashier-workstation

Курс обучения ReactJs + NodeJs с созданием кассового приложения

## Информация по выполнению домашней работы

[Страничка, посвящённая Git, если хочется разобраться как следует](https://github.com/deepmipt/dlschl/wiki/%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D1%8F-%D0%BF%D0%BE-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B5-%D1%81-Git)

Пошаговая инструкция для работы с Git для тех, кто хочет удобно работать с домашками:
1. Зарегистрироваться на GitHub
2. Делаете fork нашего репозитория на GitHub (кнопочка Fork в правом верхнем углу)
3. Создаёте себе на компьютере папку где будете выполнять домашнюю работу, например LernJS
4. Запускаете Git (перед этим скачав его с официального сайта git), а именно Git Bash
5. В открывшемся окне командами cd перемещаетесь в папку, которую создали в пункте 3
6. Выполняете в ней (в окне git'а) следующий набор команд:

```
git init
git pull <ссылка на ваш форк на сайте GitHub, вида .../cashier-workstation> master
```
7. Теперь у вас на компьютере в этой папке все файлы, которые есть в Вашем форке на сайте GitHub

8. Делаете ДЗ, изменяете нужные файлы, добавляете файлы и т.д.

9. Теперь Вы хотите, что Ваши изменения появились на GitHub. В папке, в которой всё это лежит, выполняете:

```
git add . 
```

10. Потом сразу эти команды: 

```
git commit -m '<ваше сообщение, комментарий к проделанной работе>'
git push <ссылка на ваш форк на сайте GitHub, вида .../cashier-workstation> master
```

 11. Чтобы подгрузить в Ваш форк актуальные файлы из оригинального репозитория (например, мы сделали новую домашку и Вы хотите её себе скачать), нужно сделать в папке, которую создали в пункте 3:

 ```
 git pull https://github.com/rpulatov/cashier-workstation master
 ```

 12. Git может предложить смёрджить изменения (потому что в Ваших версиях ноутбуков домашки уже сделаны), в таком случае Вам нужно вручную разрулить, какой файл выбирать (удалить файл, в котором нет Ваших изменений), если всё автоматически не разрешилось