# D2Save64kb
Fix to increase the size of the .d2s save file to about 64kb. (fixes the error "Сharacter has too many items",)
Supported game versions 1.09b, 1.09d, 1.10f, 1.11b, 1.12a, 1.13c, 1.13d
and Plugy versions 7.00, 8.00, 9.00, 10.00, 10.01, 11.00, 11.01, 11.02, 12.00, 14.00, 14.01, 14.02
Before installing, ALWAYS make a backup copy of the characters, or better, a backup of the entire \ save folder

Installation via d2mod.ini

[D2MOD]
D2Save64kb = D2Save64kb.dll

or Plugy.ini

[GENERAL]
DllToLoad = D2Save64kb.dll

or D2SE_SETUP.ini

[Protected]
ModDll1=D2Save64kb.dll

If the program incorrectly recognized the version of the game (the game starts to crash, or does not load at all),
then the version can be specified manually - in the same folder (next to D2Save64kb.dll) you need to create an empty text file with the name:

1.09b
1.09d
1.10f
1.11b
1.12a
1.13c
1.13d

If the version is indicated incorrectly, for example, you have 1.10f installed and you specify 1.09b, then most likely there will be a crash.

Based on D2Template	https://github.com/ThePhrozenKeep/D2Template

********************************************************************************************************************


Фикс для увеличения размера файла сохранения .d2s примерно до 64кб. (исправляет ошибку "Сharacter has too many items", )
Поддерживаются версии игры 1.09b, 1.09d, 1.10f, 1.11b, 1.12a, 1.13c, 1.13d
и версии Plugy 7.00, 8.00, 9.00, 10.00, 10.01, 11.00, 11.01, 11.02, 12.00, 14.00, 14.01, 14.02

Перед установкой ОБЯЗАТЕЛЬНО сделайте резервную копию персонажей, а лучше резервную копию всей папки \save

Установка через d2mod.ini

[D2MOD]
D2Save64kb=D2Save64kb.dll

или Plugy.ini

[GENERAL]
DllToLoad=D2Save64kb.dll

или D2SE_SETUP.ini

[Protected]
ModDll1=D2Save64kb.dll

Если программа неправильно распознала версию игры (игра начинает вылетать, или вообще не загружается),
то версию можно указать вручную - в этой же папке (рядом с D2Save64kb.dll) нужно создать пустой текстовый файл с именем:

1.09b
1.09d
1.10f
1.11b
1.12a
1.13c
1.13d

Если версия будет указана неверно, например у вас установлена 1.10f а вы укажете 1.09b то скорее всего будет сбой.

За основу взят D2Template https://github.com/ThePhrozenKeep/D2Template
