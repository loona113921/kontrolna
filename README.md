Итоговая работа
=

----
1. Используя команду cat в терминале операционной системы Linux, создать
два файла Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы), а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья человека).

*Cоздаю первый файл Домашние животные с названием Pets  и добавляю в него животных: cats, dogs, hamsrersl*

```
cat >Pets
cats
dogs
hamsrersl
```

*Cоздаю второй файл PackAnimals с животными horses, camels, donkeys*

```
cat >PackAnimals
horses
camels
donkeys
```

*Объединяю Pets и PackAnimals и даю название новому объединенному файлу HumanFriends*
```
cat Pets PackAnimals >HumanFriends
```

*Показываю список животных в файле HumanFriends*
```
cat HumanFriends

cats
dogs
hamsrershorses
camels
donkeys
```

![image](https://github.com/user-attachments/assets/6578be64-ac4b-4415-a05b-fd8c3cb6fd16)

----
2. **Создать директорию, переместить файл туда.**
