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
2. Создать директорию, переместить файл туда.

```
   mkdir Animals

cp -r /home/loona/HumanFriends /home/loona/Animals
```

----
3.  Подключить дополнительный репозиторий MySQL. Установить любой пакет
из этого репозитория.

*добавила репозиторий MySQL*

```
sudo add-apt-repository 'deb http://repo.mysql.com/apt/ubuntu/ bionic mysql-8.0'
```

*установила пакет из нового репозитория*
```
sudo apt install mysql-server
```

---
4.  Установить и удалить deb-пакет с помощью dpkg.

    *Скачала пакет dep Гугл Хром*

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```
![image](https://github.com/user-attachments/assets/240a9910-65f8-41f3-bdce-81fcc88bdd6f)

*установила программу (пакет)*

```
sudo dpkg -i ./google-chrome-stable_current_amd64.deb
```

*Команда удаляет пакет и связанные с ним файлы, но оставляет файлы конфигурации:*
```
sudo dpkg -r google-chrome-stable 
```

*команда для полного удаления:*
```
sudo dpkg -P google-chrome-stable
```

---
5. Выложить историю команд в терминале ubuntu

> 364  cat Pets
  365  cat >Pets
  366  cat >PackAnimals
  367  cat Pets, PackAnimals
  368  cat Pets PackAnimals
  369  cat Pets
  370  cat PackAnimals
  371  cat Pets; cat PackAnimals
  372  cat Pets PackAnimals >HumanFriends
  373  cat HumanFriends
  374  mkdir Animals
  375  pwd HumanFriends
  376  cd Animals
  377  robocopy
  378  cp -r /home/loona/HumanFriends /home/loona/Animals
  379  cat Animals
  380  ls
  381  cd HumanFriends
  382  ls
  383  ld -d
  384  -ls a
  385  -ls
  386  ls -al
  387  deb http://repo.mysql.com/apt/ubuntu/ bionic mysql-8.0
  388  sudo add-apt-repository 'deb http://repo.mysql.com/apt/ubuntu/ bionic mysql-8.0'
  389  sudo apt install mysql-server
  390  sudo apt install ./google-chrome-stable_current_amd64.deb
  391  sudo apt search ./google-chrome-stable_current_amd64.deb
  392  sudo apt install ./google-chrome-stable_current_amd64.deb
  393  wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
  394  sudo apt install ./google-chrome-stable_current_amd64.deb
  395  sudo dpkg -i ./google-chrome-stable_current_amd64.deb
  396  sudo dpkg -r ./google-chrome-stable_current_amd64.deb
  397  ls
  398  sudo dpkg -r google-chrome-stable_current_amd64.deb
  399  upt update
  400  dpkg -list
  401  dpkg --help
  402  apt update
  403  sudo apt update
  404  sudo dpkg -r stable/main amd64 Packages
  405  sudo dpkg -r ./google-chrome-stable_current_amd64.deb
  406  sudo dpkg -r google-chrome-stable_current_amd64.deb
  407  sudo dpkg -r google-chrome-stable
  408  sudo dpkg -purge google-chrome-stable
  409  dpkg -P google-chrome-stable
  410  sudo dpkg -P google-chrome-stable
  411  --force-remove-reinstreq: sudo dpkg --remove --force-remove-reinstreq google-chrome-stable
  412  sudo --force-remove-reinstreq: sudo dpkg --remove --force-remove-reinstreq google-chrome-stable
  413  sudo dpkg –purge  google-chrome-stable
  414  sudo dpkg –purge -r google-chrome-stable
  415  sudo dpkg -P  google-chrome-stable
  416  cat ~/.bash_history
  417  less ~/.bash_history
  418  ...any other pager or output command...


  ---
  6.  Нарисовать диаграмму, в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы).




























