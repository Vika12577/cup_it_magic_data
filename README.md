# cup_it_magic_data

Наш дизайн сайта также можно посмотреть в этом репозитории , файл называется "дизайн сайта.pdf"

Файл с кодом называется CupITMagicData.ipynb

1. Самый быстрый и простой способ посмотреть наш код 

1.1 открыть гугл коллаб (colab.google) через сафари или яндекс или гугл , вверху нажать на слово файл, выбрать загрузить блокнот и после выгрузить наш файл с кодом

1.2 при работе гугл коллаб не требовал у нас установки библиотек ,они должны быть встроены, но если будет выдавать ошибку то можно установить
тогда нужно будет раскомментировать следующие библиотеки и запустить код 

pip install numpy

pip install pandas

pip install requests

pip install ipython


1.3 далее в разделе среда выполнения выбрать и нажать выполнить все , тогда запустится весь код 
можно менять параметры: более подробно о возможных параметрах 

1.3.1 city1="Москва" -город отправления ( город обязательно должен указываться в кавычках)

1.3.2 city2="Волгоград" -город прибытия ( город обязательно должен указываться в кавычках)

1.3.3 date = "2025-03-10" -в кавычках нужно указать нужную дату , без кавычек будет ошибка

1.3.4 key = "d78ba33b-42fb-4720-9d5d-d3130fd08607" -мой апи ключ

1.3.5 transport="любой" -вид транспорта,

если transport="любой", то будут показаны все виды транспорта( атвобус, самолет и поезд),

если transport="автобус" , то только автобусы,

если transport="самолет", то только самолеты,

если transport="поезд", то только поезда ( если написать что-то иное в кавычках помимо этих 4 вариантов будет ошибка)

1.3.6 transfers="все" - наличие пересадок , если в кавычках написано все , то в таблице будут все варианты и с пересадками и без ,

если в кавычках написано "да" , то в таблице будут данные рейсов с пересадками,

если transfers="нет", то в таблице будут только прямые рейсы

1.3.7 time="любая" -длительность поездки любая или если time=число (пример: time=4 ) это означает, что длительность поездки не дольше 4 часов


!библиотека concurrent.futures входит в стандартную библиотеку Python, начиная с версии 3.2 и ее не нужно устанавливать отдельно. Если версия питон ниже, то эту библиотеку нельзя будет использовать и код не будет работать , в этом случае можно открыть код в гугл коллабе (colab.google) или обновите Python до последней версии. 


2. Второй способ с установкой анаконды

2.1 перейти на сайт  https://www.anaconda.com/download и скачать анаконду
   
2.2 Откройте Anaconda Navigator на компьютере и выберите в меню Jupyter Notebook или просто выполните в терминале команду jupyter notebook

2.3 загрузите нужный файл и откройте его

2.4 далее нужно будет раскомментировать следующие библиотеки и запустить код 

!pip install numpy

!pip install pandas

!pip install requests

!pip install ipython

( нужно обязательно добавить ! если скачать библиотеки нужно в Jupyter Notebook)

2.5 запустить код 

!библиотека concurrent.futures входит в стандартную библиотеку Python, начиная с версии 3.2 и ее не нужно устанавливать отдельно. Если версия питон ниже, то эту библиотеку нельзя будет использовать и код не будет работать , в этом случае можно открыть код в гугл коллабе (colab.google) или обновите Python до последней версии. 


