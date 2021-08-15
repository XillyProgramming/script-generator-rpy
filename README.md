# script-generator-rpy
Script Generator for Ren'Py (.txt to .rpy) v.1.0

## Summary
Allows you to convert TXT file of your story script into RPY.

***Why would you want something like this?***

In case you prefer to write the story in a more writer friendly software then in Ren'Py script itself. Which is more comfortable for people who is new to programming. And for those, who wants to focus on the story.

Although, this generator only works with TXT files, you can easily copy all your story from MS Word, Google docs or other text editor of your choice, save it in TXT format (in a file or several files) and use the generator to convert it into RPY. And this would take much less time than copying story line by line with intense supervision into RPY script. All you need to do is to follow a defined template for your writing.
## Описание
Генератор позволяет конвертировать (переводить) файлы TXT-формата (\*.txt) в RPY (\*.rpy).

***Зачем оно вам нужно?***

На случай, если вы предпочитаете писать сюжет своей новеллы в более дружелюбной среде, нежели прямо в скриптах от Ren'Py. Что более удобно для творческих людей с малым опытом в программировании. И людей, которые предпочитают сфокусироваться на самом сюжете.

Хотя данный генератор работает только с TXT-файлами, но вы с лёгкостью можете скопировать свою историю из MS Word, документов Google или любой другой предпочитаемой вами программы, сохранить её в TXT-формате (файле или файлах), а затем перевести всё в формат RPY используя данный генератор. Что занимает гораздо меньше времени и сил, чем построчное копирование наработок. Всё, что от вас требуется, это соблюдать определённый шаблон при оформлении текста.

## Installation

Add files to folder your_renpy_project/game

## Usage

1. Open "script.rpy" in your project's "game" folder and find `label start:`. 
2. Add `call screen script_generator_screen` afterwards as follows: 
```
label start:
    call screen script_generator_screen
```
3. Create the folder "generated" in the game folder "/game";
4. Add your story's TXT files in the folder "game/generated";
5. Run your project project, select a file from the menu and generate an RPY file for it;
6. Take the RPY file from the folder "game/generated" and place it in the "game" folder.
7. Delete `call screen script_generator_screen` from "script.rpy", Script Generator's files and "generated" folder from "game" folder to uninstall. 

## Установка и использование
Для установки добавьте файлы генератора в папку проекта your_renpy_project/game.

Для работы генератора необходимо:

1. Открыть файл "script.rpy" из папки "game" вашего проекта и найти строку `label start:`.
2. Вставить вставить под найденной строкой следующую строку `call screen script_generator_screen`, соблюдая пробелы:
```
label start:
    call screen script_generator_screen
```
3. Создать папку "generated" в папке "game";
4. Добавить TXT файл/файлы сюжета в созданную папку "generated";
5. Запустить проект, выбрать файл из появившегося меню и нажать "сгенерировать";
6. Забрать сгенерированный RPY файл из папки "generate" и вставить его в папку "game".
7. Удалить строку `call screen script_generator_screen` из "script.rpy", а также все файлы генератора из папки "game" и всю папку "generated" после использования.
