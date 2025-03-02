# Домашнее задание к занятию «Инструменты для тестирования мобильных приложений. Среда разработки»

### Цель задания

В процессе работы над заданием вы потренируетесь использовать функционал среды разработки для тестирования, делать анализ логов тестируемого приложения и предоставлять информацию разработчикам о некорректной работе функционала.

В результате выполнения этого задания вы:

1. Научитесь собирать логи с тестируемого устройства
2. Научитесь проводить стресс-тестирование.
3. Научитесь анализировать crash logs.


### Инструкция к заданию

1. Скопируйте шаблон таблицы по [ссылке](https://u.netology.ru/backend/uploads/lms/content_assets/file/4208/%D0%A8%D0%B0%D0%B1%D0%BB%D0%BE%D0%BD_MQA_1.4_%D0%98%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B_%D0%B4%D0%BB%D1%8F_%D1%82%D0%B5%D1%81%D1%82%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F_%D0%BC%D0%BE%D0%B1%D0%B8%D0%BB%D1%8C%D0%BD%D1%8B%D1%85_%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B9._.xlsx).
2. В названии файла введите корректное название лекции, вашу фамилию и имя.
3. Зайдите в “Настройки доступа” и выберите доступ “Просматривать могут все в Интернете, у кого есть ссылка”. Ссылка на инструкцию [Как предоставить доступ к файлам и папкам на Google Диске](https://support.google.com/docs/answer/2494822?hl=ru&co=GENIE.Platform%3DDesktop)
5. В своей таблице прикрепите ссылки на выполненную работу по каждому заданию. Пожалуйста, прикладывайте прямые ссылки на скриншоты(не вставляя их в doc файлы).
6. В личном кабинете прикрепите ссылку на свою таблицу с решениями и ожидайте проверки преподавателя.


## Подготовка к выполнению задания:

1. Установите и настройте Android Debug Bridge (ADB) для выполнения домашнего задания - [ссылка](https://developer.android.com/tools/releases/platform-tools).   

2. Выполните все необходимые настройки вашего Android девайса для отладки (данный материал есть в занятии "Тестирование Android- приложений" - как включить настройки разработчика).   

3. Скачайте на свой компьютер любое тестовое приложение из списка  [apk тестовых приложении](https://drive.google.com/drive/folders/1r4OxKdwMGm5s6h5oMpmvWn77PCOdxS1f).

4. Для выполнения задания вам необходимо узнать имя пакета тестируемого приложения. Используйте либо команды adb (Package Manager https://adbshell.com/), либо специальные приложения в категории Android Manifest Viewer в Google Play, которые позволяют прочитать информацию  Android Manifest  всех приложений на вашем устройстве.



## Задание 1 

- С помощью adb команды установите на физической устройство или эмулятор (если выполняете задание на нем) тестовый apk файл.   
- Запустите логирование **данного тестового приложения**.
- Проведите небольшой функциональный тест приложения, постарайтесь вызвать какую-либо ошибку (вспомните best parctice).   

**Результат выполнения задания:**

Cсылка на сохраненный log файл с ошибкой в txt формате. Если не удалось вызвать ошибку(crash), то ссылка на общий log файл (обязательно должно отображаться имя пакета приложения в логах). 



## Задание 2

Вам дали задание провести стресс-тестирование предоставленного приложения. На основе  [документации](https://developer.android.com/studio/test/other-testing-tools/monkey?hl=ru) составьте свой скрипт, постарайтесь, чтобы запуск теста был только внутри приложения.


**Результат выполнения задания:**

Ссылка на скриншот терминала со скриптом запуска теста и файл с логами тестируемого приложения, если при тестировании оно выйдет из строя или возникнет какое-либо необработанное исключение.



## Задание 3

Проведите анализ стектрейса ошибок ([Crash logs](https://drive.google.com/drive/folders/1TWugoLROQMwPcGBC6wjX4v8r-8jR18db?usp=sharing)).   
1. Оцените стек вызовов при возникновении ошибки, предположите какой модуль приложения был затронут исходя из логов.   
2. Какие действия или условия у пользователя его могли вызвать?  


 
**Результат выполнения задания:**

Ваши рассуждения и предположения по представленным двум ошибкам.    
Для оценки задания нам важно оценить ваше умение анализировать техническую информацию. 100% описания шагов и причин ошибки никто не ждет :)





### Правила приема работы

1. В личном кабинете отправлена ссылка на документ (Google Sheets) с выполненным заданием. Файлы, архивы и ссылки на облако через личный кабинет отправлять не нужно, только ссылку на документ.
2. Документ размещен на личном Google Disk.
3. К документу настроены права доступа “Просматривать могут все в Интернете, у кого есть ссылка”.
4. Дополнительные задачи, помеченные звездочкой (*), выполняются по желанию, но очень способствует дополнительной практике.
5. Выполненные задания можно прислать как по отдельности, так и все вместе. Во время проверки по частям ваша домашняя работа будет со статусом "На доработке".


### Критерии оценки

1. Зачет - выполнены все задания, ответы даны в развернутой форме, в выполненных заданиях нет противоречий и нарушения логики.
2. На доработку - задание выполнено частично или не выполнено, в логике выполнения заданий есть противоречия, существенные недостатки.


Любые вопросы по решению задач задавайте в чате учебной группы.

# [Решение](https://docs.google.com/spreadsheets/d/1-ToBEth9an623HbE_bplgbFkOW6ll4Z_/edit?usp=sharing&ouid=106742038227192767312&rtpof=true&sd=true)
